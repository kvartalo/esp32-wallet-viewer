# esp32-wallet-viewer
esp32 code to monitor wallets

![img01](https://raw.githubusercontent.com/kvartalo/esp32-wallet-viewer/master/img01.png 'img01')

- `main/wifi_cfg.h` example:
```c
#define WIFI_SSID "wifi name"
#define WIFI_PASS "password"
#define CONFIG_URL "ip or domain"
#define CONFIG_PORT "port"
#define CONFIG_PATH "endpoint"
```

- get `u8g2` submodule:
```
git submodule init
```

- run:
```
> make

> make flash
```

---

- Helpful esp32 documentation: https://docs.espressif.com/projects/esp-idf/en/latest/get-started/
- Helpful esp32 examples: https://github.com/lucadentella/esp32-tutorial
