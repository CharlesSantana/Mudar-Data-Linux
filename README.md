# Mudar-Data-Linux

timedatectl status

sudo timedatectl set-ntp false

sudo systemctl stop systemd-timesyncd

sudo hwclock --utc

sudo hwclock --systohc --utc

sudo rm /etc/localtime

sudo ln -s /usr/share/zoneinfo/America/Fortaleza /etc/localtime

sudo date -s "2025-06-27 23:30:46 -03"

sudo systemctl start systemd-timesyncd

sudo timedatectl set-ntp true
