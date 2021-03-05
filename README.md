# CTF-tools

This is collection of useful CTF links/scripts/applications. :mage_man:

## Forensic :floppy_disk:

### Files :open_file_folder:
| Tool | Instalation | Description |
|----------|:-:|-------------|
| file | <center>...</center> | Check filetype extensions. Command: file screenshot.png  |
| exiftool | [exiftool](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/) | Read metadata |
| strings | apt-get install binutils | Search for all plain-text strings in the file |
| hexdump | ... | Creates an hex dump. Usage: hexdump -C file |
| binwalk | [binwalk](https://github.com/ReFirmLabs/binwalk) | Tool for analyzing, reverse engineering, and extracting. Usage: <br/> binwalk --dd='.*' file<br /> binwalk -e file|
| steghide | sudo apt install steghide | Hide data in various kinds of image- and audio-files |



### Images :camera:
| Tool | Instalation | Description |
|----------|------|-------------|
| Stegsolve | [Stegsolve](Forensic/Images/Stegsolve.jar) | Image stenography solver.|
| StegOnline | [StegOnline](https://stegonline.georgeom.net/upload) | Online Image Steganography Tool for Embedding and Extracting data through LSB techniques.|
| zsteg | [zsteg](https://github.com/zed-0xff/zsteg)<br/>sudo gem install zsteg | Detect stegano-hidden data in PNG & BMP.<br/>Usage: zsteg -a file|
| jpdump | [jpdump](https://cyber.meme.tips/jpdump/) | A web app - read metadata|



### Audio :headphones:
| Tool | Instalation | Description |
|----------|------|-------------|
| Sonic Visualiser | [Sonic Visualiser](https://www.sonicvisualiser.org/download.html) | Look at spectogram and other few Pane. |


## Crypto :lock:
| Tool | Instalation | Description |
|----------|------|-------------|
| CyberChef | [CyberChef](https://gchq.github.io/CyberChef/) | A web app for encryption, encoding, compression and data analysis. |
| dcode | [dcode](https://www.dcode.fr/tools-list) | A toolkit website for decryption, ciphertexts, cheating at letter games, solve riddles etc. |

## Networking :globe_with_meridians:
| Tool | Instalation | Description |
|----------|------|-------------|
| Wireshark  | [Wireshark](https://www.wireshark.org/#download)<br/>sudo apt install wireshark | Analyze the network dumps. |
| A-Packets  | [A-Packets](https://apackets.com/upload) | A web app for network dumps analysis. |


