# QIDI Q1 Pro on Klipper

Configs and firmware settings for the QIDI Q1 Pro on Klipper
[LibreQ1Pro/klipper](https://github.com/LibreQ1Pro/klipper) and the display
[LibreQ1Pro/xindi](https://github.com/LibreQ1Pro/xindi).

## Contents

```
klipper/
├── printer.cfg        # printer configuration
└── gcode_macro.cfg    # macros (included from printer.cfg)
firmware/
├── klipper/           # Klipper firmware .config files for the boards
└── katapult/          # Katapult .config files for the boards
```

| Board | MCU | Klipper config | Katapult config |
|---|---|---|---|
| mainboard (`[mcu U_1]`) | STM32F401 | `firmware-mainboard[-katapult].config` | `katapult-mainboard.config` |
| toolhead (`[mcu]`) | RP2040 | `firmware-toolhead[-katapult].config` | `katapult-toolhead.config` |

## License

The code is based on [QIDITECH/QIDI_Q1_Pro](https://github.com/QIDITECH/QIDI_Q1_Pro)
and is licensed under the GNU Affero General Public License v3.0, see
[LICENSE](LICENSE).
