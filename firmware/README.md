#ATX Firmware 

- Install Python 3.11 or higher
- Install ESPHome: `pip install esphome`

- create `secrets.yaml` file based on comments from `config.yaml`:
  - `wifi_ssid`: Your Wi-Fi SSID
  - `wifi_password`: Your Wi-Fi password
  - `openthread_tlv`: OpenThread TLV (if applicable)

- Compile and upload: `esphome run config.yaml`


