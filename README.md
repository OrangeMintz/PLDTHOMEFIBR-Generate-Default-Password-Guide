# PLDTHOMEFIBR Default Password 2024 🔑 <img src="https://img.shields.io/badge/by-OrangeMintz-016eea.svg?logo=github&labelColor=181717&">

The wordlist can be generated using crunch v3.6 on Linux.

<div align="center">
    <img src="https://raw.githubusercontent.com/OrangeMintz/PLDTHOMEFIBR-Generate-Default-Password-Guide/main/img/pic1.png" height="200" alt="image" />
</div>

The purpose of this tutorial for wordlist is to crack the encryption key of a wireless network by using the captured WPA Handshake of
a network and testing the possible keys listed in the wordlist. If the correct key is in the wordlist, aircrack-ng will find it and display it.

## Download Crunch

```bash
apt-get install crunch
```

## How to generate similar wordlist?

```bash
crunch 13 13 abcdefghijklmnopqrstuvwxyz0123456789 -t PLDTWIFI@@@@@ -o PLDTdfpd2024.txt
```

## Software Requirements:

The following OS can run crunch:

- Arch Linux
- Manjaro Linux
- BlackArch Linux
- Deepin
- Elementary
- Fedora
- Linux Mint
- Parrot Security
- Ubuntu
- Void Linux
- etc..

The following OS are likely to be able to run crunch:

- Windows OS
- macOS

## Usage

In this guide you'll learn how to use crunch to create a list of possible passwords for cracking WPA/WPA2 network security. With your
generated wordlist, you can use aircrack-ng and airodump-ng to try different passwords against the data you’ve collected to unlock the network.
