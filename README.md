# Alpine initramfs-init

## Introduction
This initramfs-init generate an initramfs which support that /usr directory is 
located an separate partition

## Usage
To regernate the initramfs file copy the initramfs-init from this repo to /usr/share/mkinitfs/initramfs-init amd execute
```BASH
mkinitfs -c /etc/mkinitfs/mkinitfs.conf -b 
```
## Tests

| Date | Alpine Version | Arch |
| --- | --- | --- |
| 21.08.2023 | 3.18.3 | aarch64 |


