I ported Flash Player Projector to Linux

Tested on:
Arch Linux 5.8.12 KDE Plasma 5.19.5

Dependiences:
-wine (this must be 32 bit version)
-zenity

DOWNLOAD:
0.1-linuz-alpha: http://github.com/glowiak/flashplayer-dbg-linux/releases/download/0.1linuz/flashplayer-linux.txz

Good news Arch users! ArchLinux package is out!
Get it here: https://github.com/glowiak/flashplayer-dbg-linux/releases/download/0.1linuz/flashplayer-dbg-0.1linuz-1-x86_64.pkg.tar.zst


How to install & run:
!NOTE! You must have installed 32 bit wine and zenity!
Extract .txz file and open terminal in extracted directory,
type:
$ ./setup
In winecfg window select "Windows 2000", apply and close winecfg,
Installation completed, to run it type (in extracted directory):
$ ./run
