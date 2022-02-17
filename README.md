* turn Arc-them font color to black
  #+BEGIN_SRC shell
  sudo find /usr/share/themes/Arc -name "*" -type f -exec sed -i 's/'5C616C'/'000000'/gI' {}  \;
  #+END_SRC





sudo blkid 
/dev/sda5: UUID="db56ca25-7435-480e-9e04-59c05b0b01af" BLOCK_SIZE="4096" TYPE="ext4" PARTUUID="4845497a-05"
/dev/sda6: UUID="e9fb3aee-df0a-4cbf-87fa-d286e06dc853" BLOCK_SIZE="4096" TYPE="ext4" PARTUUID="4845497a-06"
/dev/sda7: UUID="7dd5d079-efab-48a8-899b-b0869eaf5181" TYPE="swap" PARTUUID="4845497a-07"
/dev/sda8: UUID="5b10a735-a67e-4d19-93f5-93050482c82a" BLOCK_SIZE="4096" TYPE="ext4" PARTUUID="4845497a-08"
/dev/sda9: BLOCK_SIZE="512" UUID="36FC9C5734D03F0D" TYPE="ntfs" PARTUUID="4845497a-09"
/dev/sda10: BLOCK_SIZE="512" UUID="4BF601D3016FCAD3" TYPE="ntfs" PARTUUID="4845497a-0a"

sudo emacs -nw /etc/fstab 

UUID=4BF601D3016FCAD3   /media/ahmed/4BF601D3016FCAD3     ntfs    defaults        0       0
