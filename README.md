We Work Detok Not Only Tok Detok
```
echo -e "net.ipv6.conf.all.disable_ipv6 = 1\nnet.ipv6.conf.default.disable_ipv6 = 1\nnet.ipv6.conf.lo.disable_ipv6 = 1" >> /etc/sysctl.conf && sysctl -p
```

```
apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo lsof socat net-tools bc coreutils build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot
```

```
screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/vermiliion/udp-lite/main/udp.sh && chmod +x udp.sh && ./udp.sh; read -p 'Tekan enter untuk keluar...'"
```
Perintah Update Script
```
wget -q https://raw.githubusercontent.com/vermiliion/udp-lite/main/update.sh && chmod +x update.sh && ./update.sh && rm -f update.sh
```

```
screen -r -d setup
```