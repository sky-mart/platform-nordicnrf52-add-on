# Nordic nRF52: development platform for [PlatformIO](https://platformio.org) Add-on

The nRF52 Series are built for speed to carry out increasingly complex tasks in the shortest possible time and return to sleep, conserving precious battery power. They have a Cortex-M4F processor which makes them quite capable Bluetooth Smart SoCs.

* [Home](https://registry.platformio.org/platforms/platformio/nordicnrf52) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/nordicnrf52.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Open PIO Home > Platforms and select *Advanced Installation* option. Paste the repository URL to the text input:
`https://gitlab.nsoric.com/mtf/mcu/nrf52/platform-nordicnrf52-add-on.git`
3. Wait until platform is installed.
4. Create PlatformIO project and select one board from the *Nordicnrf52-add-on* folder.

## Stable version

```ini
[env:stable]
platform = nordicnrf52-add-on
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://gitlab.nsoric.com/mtf/mcu/nrf52/platform-nordicnrf52-add-on.git
board = ...
...
```
# Add-on
Added support of Nordic's PCA10059 dongle board equiped with nRF52840 SoC, which has pre-flashed Nordic's DFU bootloader. We have excluded SoftDevice, so it has more FLASH and RAM memory available.

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/nordicnrf52.html).
