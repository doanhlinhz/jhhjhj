fdisk /dev/sda
mkfs.ext4 /dev/sda1
mkfs.ext4 /dev/sda2
mkfs.ext4 /dev/sda3
mkfs.ext4 /dev/sda5
mkswap /dev/sda4
swapon /dev/sda4
