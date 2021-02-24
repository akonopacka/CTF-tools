# CTF-tools

This is collection of useful CTF links/scripts/applications. 

## Forensic

### Files
| Tool | Instalation | Description |
|----------|------|-------------|search for all plain-text strings in the file
| file | ... | Check filetype extensions. Command: file screenshot.png  |
| exiftool | [exiftool](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/) | Read metadata |
| strings | apt-get install binutils | Search for all plain-text strings in the file |
| hexdump | ... | Creates an hex dump. Command: hexdump -C file |
| binwalk | [binwalk](https://github.com/ReFirmLabs/binwalk) | Tool for analyzing, reverse engineering, and extracting. Usefull commands: binwalk --dd='.*' file |

### Images

| Stegsolve | [Stegsolve](Forensic/Images/Stegsolve.jar) | Image stenography solver (TODO Update functions) |
