# ESPHome – 3×3 Keypad + Encoder (D1 mini / WT32-ETH01)

This repo holds a dual-target ESPHome project:
- **D1 mini (ESP8266)** with Wi‑Fi
- **WT32‑ETH01 (ESP32)** with Ethernet (LAN8720)

## How to use in ESPHome Builder

Paste this in a new device config:

```yaml
packages:
  main: !include https://raw.githubusercontent.com/m-s-e/espdeckenc/main/main.yaml
