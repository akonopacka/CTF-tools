# CTF-tools

This is collection of useful CTF links/scripts/applications. :mage_man:

[Useful writeups](Writeups/README_WRITEUPS.md)

## Forensic :floppy_disk:

### Files :open_file_folder:
| Tool | Installation | Description |
|----------|------|-------------|
| file | -| Check filetype extensions. Command: file screenshot.png  |
| exiftool | [exiftool](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/) | Read metadata |
| strings | apt-get install binutils | Search for all plain-text strings in the file |
| hexdump | - | Creates an hex dump. Usage: hexdump -C file |
| binwalk | [binwalk](https://github.com/ReFirmLabs/binwalk) | Tool for analyzing, reverse engineering, and extracting. Usage: <br/> binwalk --dd='.*' file<br /> binwalk -e file|
| steghide | sudo apt install steghide | Hide data in various kinds of image- and audio-files |


### Images :camera:
| Tool | Installation | Description |
|----------|------|-------------|
| Stegsolve | [Stegsolve](Forensic/Images/Stegsolve.jar) | Image stenography solver.|
| StegOnline | [StegOnline](https://stegonline.georgeom.net/upload) | Online Image Steganography Tool for Embedding and Extracting data through LSB techniques.|
| zsteg | [zsteg](https://github.com/zed-0xff/zsteg)<br/>sudo gem install zsteg | Detect stegano-hidden data in PNG & BMP.<br/>Usage: zsteg -a file|
| jpdump | [jpdump](https://cyber.meme.tips/jpdump/) | A web app - read metadata|
| Steg0saurus Chex | [Steg0saurus Chex](https://lukeslytalker.pythonanywhere.com/) | Scan for various forms of image steganography.|
| Steganography Online | [Steganography Online](https://stylesuxx.github.io/steganography/) | To decode a hidden message from an image. |
| Image Steganography | [Image Steganography](https://incoherency.co.uk/image-steganography/#unhide) | Steganographically (un)hide images inside the lower "bits" of other images. |


### Audio :headphones:
| Tool | Installation | Description |
|----------|------|-------------|
| Sonic Visualiser | [Sonic Visualiser](https://www.sonicvisualiser.org/download.html) | Look at spectogram and other few Pane. |
| Morse Decoder | [Morse Decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html) |  Tool to analyse, decode Morse code in audio files. |


## Crypto :lock:
| Tool | Installation | Description |
|----------|------|-------------|
| CyberChef | [CyberChef](https://gchq.github.io/CyberChef/) | A web app for encryption, encoding, compression and data analysis. |
| dcode | [dcode](https://www.dcode.fr/tools-list) | A toolkit website for decryption, ciphertexts, cheating at letter games, solve riddles etc. |
| CrackStation | [CrackStation](https://crackstation.net/) | Pre-computed lookup tables to crack password hashes. |
| Cipher Tools | [Cipher Tools](http://rumkin.com/tools/cipher/) | Web-based tools for ciphers and codes. |
| Vigenere Cipher | [Vigenere Cipher](https://www.dcode.fr/vigenere-cipher) | Tool to decrypt/encrypt Vigenere automatically. |
| Vigenere Solver | [Vigenere Solver](https://www.guballa.de/vigenere-solver) | The online tool breaks Vigenère ciphers without knowing the key. |
| VIGENERE | [VIGENERE](https://f00l.de/hacking/vigenere.php) | Online vigenere analysis and cracking. |


## Networking :globe_with_meridians:
| Tool | Installation | Description |
|----------|------|-------------|
| Wireshark  | [Wireshark](https://www.wireshark.org/#download)<br/>sudo apt install wireshark | Analyze the network dumps. |
| A-Packets  | [A-Packets](https://apackets.com/upload) | A web app for network dumps analysis (Up to 25MB). |
| PacketTotal | [PacketTotal](https://packettotal.com/) | A web app - analyzing, categorizing, and sharing .pcap files. (Up to 50MB) |


## REVERSE :leftwards_arrow_with_hook:
| Tool | Installation | Description |
|----------|------|-------------|
| ODA | [ODA](https://onlinedisassembler.com/odaweb/) | Online DisAssembler. |
| UNPACME | [UNPACME](https://www.unpac.me/#/) | An automated malware unpacking service.  |


## OSINT :eyes:
| Tool | Installation | Description |
|----------|------|-------------|
| Wikimapia | [Wikimapia](http://wikimapia.org/) | An open-content collaborative mapping project. Find specific landmarks. |
| SunCalc | [SunCalc](http://suncalc.net/) |  A web app that shows sun movement and sunlight phases during the given day at the given location. It makes finding location on the picture easier based on the shadows.|
