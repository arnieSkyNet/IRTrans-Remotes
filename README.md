# IRTrans-Remotes

![Bash](https://img.shields.io/badge/language-Bash-yellow)
![Last Commit](https://img.shields.io/github/last-commit/ArnieSkyNet/IRTrans-Remotes)

A curated collection of IRTrans `.rem` remote definition files for Raspberry Pi and other IR automation systems.  
Use these files to control lamps, TVs, soundbars, and other devices via IRTrans.

This repository requires IRTrans hardware and software to work.  
More information can be found at the official IRTrans website: [http://www.irtrans.de/en/](http://www.irtrans.de/en/)

---

## Contents

- **remotes/**: All `.rem` remote-definition files.
- **tools/**: Optional helper scripts (e.g., `test-ir.sh`).

### Key Remote Files

| Device | File |
|--------|------|
| VGAzer Moon Lamp | `VGAzerMoonLamp.rem` |
| Samsung TV | `SamsungTV.rem` |
| LG Soundbar | `LGSoundbar.rem` |

---

## Installation

1. Clone this repository:

    git clone https://github.com/ArnieSkyNet/IRTrans-Remotes.git
    cd IRTrans-Remotes

2. Copy `.rem` files to your IRTrans remotes directory:

    sudo cp remotes/*.rem /usr/local/irtrans/remotes/
    sudo systemctl restart irtrans

*(Adjust the path based on your installation.)*

---

## Contributing

Pull requests with new `.rem` files are welcome. Include:

- Device name  
- Source of IR codes  
- Any quirks or notes  
