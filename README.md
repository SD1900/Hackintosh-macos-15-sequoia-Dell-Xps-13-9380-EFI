After a lot of changing and hard work, this is the EFI that works for my Dell Xps 13 9380 for macos 15(Sequoia).
I tried it on Tahoe and it didnt work.
For Wifi to work, Heliport (https://github.com/OpenIntelWireless/heliport) is needed.
You cant have EFI inside another folder, it has to be
Raiz da Pen USB (FAT32)
└── EFI
    ├── BOOT
    └── OC

It also has to be on root of a Fat32 Pendrive (If its not fat32 it wont work).
