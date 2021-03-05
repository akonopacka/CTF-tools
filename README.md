# CTF-tools

This is collection of useful CTF links/scripts/applications. :mage_man:

## Forensic :floppy_disk:

### Files
| Tool | Instalation | Description |
|----------|:-:|-------------|
| file | <center>...</center> | Check filetype extensions. Command: file screenshot.png  |
| exiftool | [exiftool](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/) | Read metadata |
| strings | apt-get install binutils | Search for all plain-text strings in the file |
| hexdump | ... | Creates an hex dump. Command: hexdump -C file |
| binwalk | [binwalk](https://github.com/ReFirmLabs/binwalk) | Tool for analyzing, reverse engineering, and extracting. Usefull commands: <br /> binwalk --dd='.*' file<br /> binwalk -e file|
| steghide | sudo apt install steghide | Hide data in various kinds of image- and audio-files |



### Images :camera:
| Tool | Instalation | Description |
|----------|------|-------------|
| Stegsolve | [Stegsolve](Forensic/Images/Stegsolve.jar) | Image stenography solver (TODO Update functions) |
