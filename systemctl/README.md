# systemctl
Guide: [Self-hosting Vaultwarden on a Raspberry Pi](https://reinhard.codes/2021/04/19/self-hosting-vaultwarden-on-a-raspberry-pi/)

Mounting Commands: [6 Different Ways to List Hard Drives in Linux
](https://linuxhandbook.com/linux-list-disks/)
```
cd systemctl
sudo systemctl enable vaultwarden-backup.service
sudo systemctl enable vaultwarden-backup.timer
sudo systemctl start vaultwarden-backup.timer
sudo systemctl enable media-backup.mount
sudo systemctl enable media-backup.automount
```