# Repository Identity

- Canonical name: SOLDIER
- Purpose: UART-controlled ESP32-S3 BLE lab companion firmware with NeoPixel status feedback.
- Remote: `leafedbug-cmd/SOLDIER`
- Required base branch: `main`; recovery branch: `agent/normalize-soldier-files`
- Recovery commit: `d7b6460` (`Save CRLF line-ending updates`)
- Entry point: `src/main.cpp`
- Manifest: `platformio.ini` (`sparkle_iot`)
- Build/flash/monitor: `pio run`; `pio run -t upload`; `pio device monitor -b 115200`
- Generated artifacts: `.pio/build/`; ignored.

Search terms: SOLDIER SOLDIER_READY READY_QUERY SWEEP_START sparkle_iot RGB_LED_PIN 48.
