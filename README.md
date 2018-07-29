# UNetbootin
UNetbootin (Universal Netboot Installer) is a cross-platform utility that can create live USB systems and can load a variety of system utilities or install various Linux distributions and other operating systems without a CD.
This installation mode creates bootable USB flash drives and bootable USB Hard Disk Drives; it is a Live USB creator.

Cross-platform (available for Windows, Linux and Mac OS X)
Non-destructive install (does not format the device) using Syslinux.
Supports mainstream Linux distributions, such as Ubuntu, Fedora, openSUSE, CentOS, Gentoo, Linux Mint, Arch Linux, Mandriva, MEPIS, Slackware as well as FreeDOS, FreeBSD and NetBSD.
Can load a variety of system utilities, such as Ophcrack, BackTrack.
Other operating systems can be loaded via pre-downloaded ISO image or floppy/hard drive disk image files.
Automatically detects all removable devices.
Supports LiveUSB persistence (preserving files across reboots; this feature is for Ubuntu only)
Multiple installs on the same device are not supported.

To install UNetbootin from the Ubuntu PPA, run the commands:

sudo add-apt-repository ppa:gezakovacs/ppa
sudo apt-get update
sudo apt-get install unetbootin

To run these binaries, download them and run the command chmod +x ./unetbootin-linux, 
or go to Properties->Permissions and check "Execute"), then start the application 
by running ./unetbootin-linux
