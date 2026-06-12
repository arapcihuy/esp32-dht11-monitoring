# ESP32 DHT11 Real-time Monitoring

[![CodeQL](https://github.com/arapcihuy/esp32-dht11-monitoring/actions/workflows/codeql.yml/badge.svg)](https://github.com/arapcihuy/esp32-dht11-monitoring/actions/workflows/codeql.yml)
[![GitHub repo](https://img.shields.io/badge/GitHub-arapcihuy%2Fesp32--dht11--monitoring-blue?logo=github)](https://github.com/arapcihuy/esp32-dht11-monitoring)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license)

Sistem monitoring suhu dan kelembaban real-time berbasis ESP32 + sensor DHT11. Proyek ini menampilkan kemampuan IoT, integrasi sensor, konektivitas WiFi, dan dashboard monitoring sederhana.

## Ringkasan

- Platform: ESP32
- Sensor: DHT11 temperature & humidity
- Fokus: IoT monitoring, data real-time, embedded prototyping
- Status: Portfolio project

## Fitur

- Monitoring suhu real-time
- Monitoring kelembaban udara
- Koneksi WiFi ESP32
- Dashboard/serial output untuk pemantauan data
- Struktur proyek sederhana dan mudah dikembangkan

## Hardware

- ESP32 Development Board
- Sensor DHT11
- Breadboard
- Kabel jumper
- Koneksi WiFi

## Wiring

| DHT11 | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| DATA | GPIO 4 |

## Instalasi

```bash
git clone https://github.com/arapcihuy/esp32-dht11-monitoring.git
cd esp32-dht11-monitoring
```

Buka file `.ino` di Arduino IDE, lalu install library:

- DHT sensor library by Adafruit
- Adafruit Unified Sensor

Konfigurasi WiFi:

```cpp
const char* ssid = "NAMA_WIFI";
const char* password = "PASSWORD_WIFI";
```

Upload ke board ESP32.

## Penggunaan

1. Hubungkan sensor sesuai wiring.
2. Upload sketch ke ESP32.
3. Buka Serial Monitor / dashboard.
4. Pantau suhu dan kelembaban secara real-time.

## Spesifikasi Sensor

| Parameter | Range | Akurasi |
|---|---:|---:|
| Suhu | 0-50°C | ±2°C |
| Kelembaban | 20-90% RH | ±5% RH |

## Security Notes

- Jangan commit SSID/password asli.
- Gunakan file konfigurasi lokal atau environment secret untuk deployment lanjutan.
- Aktifkan GitHub CodeQL untuk pemeriksaan keamanan otomatis.

## Roadmap

- Integrasi MQTT/HTTP API
- Dashboard web real-time
- Alert threshold suhu/kelembaban
- Penyimpanan data historis

## Author

Rasyid Achmad Fauzi — https://github.com/arapcihuy

## License

MIT License.
