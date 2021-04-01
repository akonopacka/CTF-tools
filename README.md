# CTF-tools

This is collection of useful CTF links/scripts/applications. :mage_man:

[Useful writeups](Writeups/README_WRITEUPS.md)

## FORENSIC :floppy_disk:

### Files :open_file_folder:

| Tool | Description | Sample Usage |
|------|-------------|--------------|
| file | Check filetype extensions. | <pre>file <em>file_name</em></pre> |
| [exiftool](https://linoxide.com/linux-how-to/install-use-exiftool-linux-ubuntu-centos/) | Read metadata | <pre>exiftool <em>file_name</em></pre> |
| strings | Search for all plain-text strings in the file<br>Install: <pre>sudo apt-get install binutils</pre> | <pre>strings <em>file_name</em></pre> |
| hexdump | Creates an hex dump. | <pre>hexdump -C <em>file</em></pre> |
| [binwalk](https://github.com/ReFirmLabs/binwalk) | Tool for analyzing, reverse engineering, and extracting. | <pre>binwalk -e <em>file_name</em><br/>binwalk --dd='.*' <em>file_name</em></pre> |
| [steghide](http://steghide.sourceforge.net/documentation/manpage.php) | Hide data in various kinds of image- and audio-files. Install: <pre>sudo apt install steghide</pre> | - |


### Images :camera:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [Stegsolve](Forensic/Images/Stegsolve.jar) | Image stenography solver.| - |
| [StegoVeritas](https://github.com/bannsec/stegoVeritas) | Perform different image operations and save results in folder.| <pre>stegoveritas <em>file_name</em></pre> |
| [StegOnline](https://stegonline.georgeom.net/upload) | Online Image Steganography Tool for Embedding and Extracting data through LSB techniques.| - |
| [zsteg](https://github.com/zed-0xff/zsteg)| Detect stegano-hidden data in PNG & BMP. <br/>Install: <pre>sudo gem install zsteg</pre> | <pre>zsteg -a <em>file_name</em></pre>|
| [jpdump](https://cyber.meme.tips/jpdump/) | A web app - read metadata| - |
| [Steg0saurus Chex](https://lukeslytalker.pythonanywhere.com/) | Scan for various forms of image steganography.|
| [Steganography Online](https://stylesuxx.github.io/steganography/) | To decode a hidden message from an image. | - |
|  [Image Steganography](https://incoherency.co.uk/image-steganography/#unhide) | Steganographically (un)hide images inside the lower "bits" of other images. | - |


### Audio :headphones:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [Sonic Visualiser](https://www.sonicvisualiser.org/download.html) | Look at spectogram and other few Pane. | - |
| [Morse Decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html) |  Tool to analyse, decode Morse code in audio files. | - |


## CRYPTO :lock:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [CyberChef](https://gchq.github.io/CyberChef/) | A web app for encryption, encoding, compression and data analysis. | - |
| [dcode](https://www.dcode.fr/tools-list) | A toolkit website for decryption, ciphertexts, cheating at letter games, solve riddles etc. | - |
| [CrackStation](https://crackstation.net/) | Pre-computed lookup tables to crack password hashes. | - |
| [Cipher Tools](http://rumkin.com/tools/cipher/) | Web-based tools for ciphers and codes. | - |
| [Vigenere Cipher](https://www.dcode.fr/vigenere-cipher) | Tool to decrypt/encrypt Vigenere automatically. | - |
| [Vigenere Solver](https://www.guballa.de/vigenere-solver) | The online tool breaks Vigenère ciphers without knowing the key. | - |
| [VIGENERE](https://f00l.de/hacking/vigenere.php) | Online vigenere analysis and cracking. | - |


## NETWORKING :globe_with_meridians:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [Wireshark](https://www.wireshark.org/#download) | Analyze the network dumps. | - |
| [NetworkMiner](https://www.netresec.com/?page=NetworkMiner) | Network traffic analysis, extracting artifacts, such as files or credentials from pcap files. | - |
| [A-Packets](https://apackets.com/upload) | A web app for network dumps analysis (Up to 25MB). | - |
| [PacketTotal](https://packettotal.com/) | A web app - analyzing, categorizing, and sharing .pcap files. (Up to 50MB) | - |


## REVERSE :leftwards_arrow_with_hook:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [ODA](https://onlinedisassembler.com/odaweb/) | Online DisAssembler. | - |
| [UNPACME](https://www.unpac.me/#/) | An automated malware unpacking service.  | - |

## REDTEAMING :red_circle:
### Recon :eyes:
| Tool | Description | Sample Usage |
|----------|--------------|-------------|
| [Smbmap](https://github.com/ShawnDEvans/smbmap) | Smb shares discovery. Much the same as smbclient but with some supplementary permission and access. | To try and list shares as the anonymous user ( False negatives happen tho ): </br><pre> smbmap -H 10.10.10.10 -u anonymous </pre></br> And you can also specify a domain: <pre> smbmap -H 10.10.10.10 -d domain.xyz </pre></br> If above returned NO_LOGON_SERVERS try <pre> smbmap -H 10.10.10.125 -u anonymous -d localhost </pre> |

## OSINT :eyes:
| Tool | Description | Sample Usage |
|------|-------------|--------------|
| [Wikimapia](http://wikimapia.org/) | An open-content collaborative mapping project. Find specific landmarks. | - |
| [SunCalc](http://suncalc.net/) |  A web app that shows sun movement and sunlight phases during the given day at the given location. It makes finding location on the picture easier based on the shadows.| - |
