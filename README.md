# Generate PLDTHOMEFIBR Default Password 🔑 <img src="https://img.shields.io/badge/by-OrangeMintz-016eea.svg?logo=github&labelColor=181717&">

The wordlist can be generated using crunch v3.6 on Linux.

<div align="center">
    <img src="https://raw.githubusercontent.com/OrangeMintz/PLDTHOMEFIBR-Generate-Default-Password-Guide/main/img/pic1.png" height="300" alt="image" />
</div>
<br>

In this guide, you'll learn how to use crunch to create a list of possible passwords for cracking the WPA/WPA2 security of the PLDTHOMEFIBR network. 
With this list and data collected from the network, you can use aircrack-ng and airodump-ng to test different passwords and find the correct one to unlock the network.

## Download Crunch

```bash
apt-get install crunch
```

## How to generate wordlist?

```bash
crunch 13 13 abcdefghijklmnopqrstuvwxyz0123456789 -t PLDTWIFI@@@@@ -o PLDTdfpd2024.txt
```

<div align="center">
    <img src="https://raw.githubusercontent.com/OrangeMintz/PLDTHOMEFIBR-Generate-Default-Password-Guide/main/img/pic2.png" height="300" alt="image" />
</div>

## Software Requirements:

The following OS can run crunch:

- Kali
- Arch
- Manjaro
- BlackArch
- Deepin
- Elementary
- Fedora
- Linux Mint
- Parrot Security
- Ubuntu
- Void
- etc..

The following OS are likely to be able to run crunch:

- Windows OS
- macOS

## Disclaimer

This guide is intended solely for educational purposes and to promote ethical hacking practices. It is crucial to use the information responsibly and only on networks you own or have explicit permission to test. Unauthorized access to networks is illegal and unethical. Always ensure you have proper authorization before conducting any security assessments.
