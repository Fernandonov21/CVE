# SMBGhost (CVE-2020-0796) Automate Exploitation and Detection

This python program is a wrapper from the RCE vulnerability. All the credits for the exploit are for [chompie1337][1]. All the credits for the scanner [ioncodes][2].

I just automate this functions in one program. Many thanks for the [veil project][3], a lot of my code is based from that repo.

This exploit is not really **stable**, use at your own.

# DEMO
![Demo](https://user-images.githubusercontent.com/16231048/84295973-9e013e80-ab4b-11ea-8b92-a1d6ba6b440e.gif)

# Options
```
usage: Smb_Ghost.py [-h] -i IP [-p PORT] [--check] [-e] [--lhost LHOST]
                    [--lport LPORT] [--arch ARCH] [--silent] [--shellcode]
                    [--load-shellcode LOAD_SHELLCODE]

SMBGhost Detection and Exploitation

optional arguments:
  -h, --help            show this help message and exit
  -i IP, --ip IP        IP address
  -p PORT, --port PORT  SMB Port
  --check               Check SMBGhost Vulnerability
  -e                    Directly exploit SMBGhost
  --lhost LHOST         Lhost for the reverse shell
  --lport LPORT         Lport for the reverse shell
  --arch ARCH           Architecture of the target Windows Machine
  --silent              Silent mode for the scanner
  --shellcode           Shellcode Menu to import your shell
  --load-shellcode LOAD_SHELLCODE
                        Load shellcode directly from file

```

# Author
* Alberto Barriuso ([@_Barriuso](https://twitter.com/_Barriuso))

[1]: https://github.com/chompie1337/SMBGhost_RCE_PoC
[2]: https://github.com/ioncodes/SMBGhost
[3]:https://github.com/Veil-Framework/Veil
