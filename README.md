# Asus-NovaGo-TP370QL

Debug information about Asus NovaGo TP370QL to get a proper Linux running on it.

Main resources: <https://github.com/aarch64-laptops/build/>

## /dev/sdb1

One UEFI bootloader is on /dev/sdb1 (XBL eXtensible BootLoader), called "Boot1 Partition" in [section1.raw.txt](https://github.com/monperrus/Asus-NovaGo-TP370QL/tree/master/uefi//volume-520912/file-9e21fd93-9c72-4c15-8c4b-e77f1db2d792/section0/section1/volume-ee4e5898-3914-4259-9d6e-dc7bd79403cf/file-a1e235de-e825-4591-9623-c43175811826/section1.raw.txt)

```
$ file /dev/sdb1
/home/martin/sdb1: ELF 64-bit LSB executable, ARM aarch64, version 1 (SYSV), statically linked, no section header
```

Content extracted with [uefi-firmware-parser](https://github.com/theopolis/uefi-firmware-parser), see `uefi-firmware-parser.txt` and folder `uefi`

## /dev/sdb2

Second bootlader / boot2


## Troubleshooting

```
UEFI Version : Qualcomm Inc. NovaGo TP370QL.254, 04/24/2018
Code base: 1076
```

