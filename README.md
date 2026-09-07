After a lot of changing and hard work, this is the EFI that works for my Dell Xps 13 9380 for macos 15 (Sequoia). I tried it on Tahoe and it didn't work. 
For Wifi to work, Heliport (https://github.com/OpenIntelWireless/heliport) is needed.

### USB Structure 
It has to be on the root of a FAT32 Pendrive (If it's not FAT32 it won't work). You can't have the EFI inside another folder.

```text
Root of Pen USB (FAT32)
└── EFI
    ├── BOOT
    └── OC
```
