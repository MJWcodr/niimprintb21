# (WIP) Niimbot printer client

This is a fork of [niimprint](https://github.com/kjy00302/niimprint) with added support for the Niimbot B21 printer and a few other improvements.

## Usage
```
    usage: niimprint [-h] -a ADDRESS [--no-check] [-d DENSITY] [-t TYPE] [-n QUANTITY] image

    Niimbot printer client

    positional arguments:
    image                 PIL supported image file

    options:
    -h, --help            show this help message and exit
    -a ADDRESS, --address ADDRESS
                            MAC address of target device
    --no-check            Skips image check
    -d DENSITY, --density DENSITY
                            Printer density (1~3)
    -t TYPE, --type TYPE  Label type (1~3)
    -n QUANTITY, --quantity QUANTITY
                            Number of copies
```

## Prerequisites

- Python 3.12+ compiled with bluetooth support ([Install with Bluetooth](https://stackoverflow.com/a/75203662))
