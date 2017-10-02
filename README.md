# ArchSnapshot
backup-Recovery Arch system anytime
View video tutorial
install packages
pacman -S cdrkit
pacman -S squashfs-tools
pacman -S terminator
pacman -S dialog
Not supported specials backup /boot /home /root partitions and device-crypt-mapper, only /root partition
Not supported in the setup gpt or uefi, only dos mbr and bios grub
Mount iso and copy snapshot folder to /home root user
