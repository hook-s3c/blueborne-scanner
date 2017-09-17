# VPN Gate auto-grabber

## Greetz

shouts to sh3llg0d, an0n_l1t3, daemochi, akatz!!!!

## Overview

Bluetooth scanner for blueborne-vulnerable devices, Android only for the moment

## Quickstart
```
git clone https://github.com/hook-s3c/blueborne-scanner.git
cd blueborne-scanner
sudo chmod +x ./bluebornescan.py
pip install -r ./requirements.txt

./bluebornescan.py
```
## Breakdown

1. Scans for local bluetooth devices
2. Looks up the OUI of the MAC to see if it matches vulnerable devices

## Notes

I'm still learning python, there are no unit tests, sorry.

There is no support, fork/PR as you wish. 
MIT license, so attribution is mandatory.

- CVE-2017-0785
- CVE-2017-0781
- CVE-2017-0782
- CVE-2017-0783
- https://www.youtube.com/watch?v=Az-l90RCns8

## References

- https://www.armis.com/blueborne/
- https://www.youtube.com/watch?v=KiNr1kXAh-A
- https://pastebin.com/raw/RhN6mkqd
- https://github.com/terry2012/BlueBorneVulnScanner

- https://stackoverflow.com/questions/3342760/how-can-i-make-pybluez-return-a-list-of-discovered-devices-every-x-seconds-and-t
- https://networkengineering.stackexchange.com/questions/36843/do-bluetooth-devices-have-mac-address-with-the-same-specification-as-the-mac-add/36846
- https://stackoverflow.com/questions/663171/is-there-a-way-to-substring-a-string-in-python
- https://stackoverflow.com/questions/3765533/python-array-with-string-indices
- https://stackoverflow.com/questions/9244909/python-conditional-string-formatting