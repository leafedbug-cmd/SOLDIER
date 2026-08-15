# SOLDIER

ESP32-S3 companion firmware that handshakes with a Commander board over UART, reports state through a WS2812 LED, and runs controlled BLE advertising bursts for RF lab work.

## Find this repo again

Search for `SOLDIER_READY`, `READY_QUERY`, `SWEEP_START`, `sparkle_iot`, or `RGB_LED_PIN 48`.

See [Repository identity and recovery details](docs/REPOSITORY-IDENTITY.md).

## Build

```bash
pio run
pio run -t upload
pio device monitor -b 115200
```

Use only in authorized, controlled RF test environments.
