# mutante
<<<<<<< HEAD
Windows kernel-mode hardware identifier (HWID) spoofer. It does not use any hooking, so it can be completelly unloaded after use. Tested on Windows 10 x64 2004 (19041.264).
=======
Windows kernel-mode hardware identifier spoofer. It does not use any hooking, so it can be completelly unloaded after use.
>>>>>>> parent of 4330194 (readme looks gut)

## Features
- Disk serials (works on both SATA and NVMe drives)
- Disable S.M.A.R.T disk functionality
- SMBIOS (tables 0-3)

## Credits
- Me (@SamuelTulach) - Putting it all together
- n0Lin (@Alex3434) - [Static disk spoofing without hooks](https://github.com/Alex3434/wmi-static-spoofer)
- IChooseYou - [Disable S.M.A.R.T functionality](https://www.unknowncheats.me/forum/2441916-post67.html) and [finding SMBIOS physical address](https://www.unknowncheats.me/forum/2436698-post9.html)
- btdt (@btdt) - [Finding SMBIOS physical address (again)](https://github.com/btbd/hwid/blob/master/Kernel/main.c#L558) and [signanture scanning functions](https://github.com/btbd/hwid/blob/master/Kernel/util.c#L112)