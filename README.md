# 🌡️ ESP32 DHT11 Real-time Monitoring

Sistem monitoring suhu dan kelembaban udara secara real-time menggunakan ESP32 dan sensor DHT11.

## 📋 Fitur

- 🌡️ Monitoring suhu real-time
- 💧 Monitoring kelembaban udara
- 📊 Visualisasi data dashboard
- ⚡ Update data secara real-time
- 🔔 Notifikasi jika parameter di luar batas normal

## 🛠️ Hardware Requirements

- ESP32 Development Board
- Sensor DHT11 (Temperature & Humidity)
- Kabel jumper
- Breadboard
- Koneksi internet (WiFi)

## 🚀 Instalasi & Setup

### 1. Clone Repository
```bash
git clone https://github.com/arapcihuy/realtime-monitoring-dht-11-sensor-with-esp-32.git
cd realtime-monitoring-dht-11-sensor-with-esp-32
```

### 2. Upload ke ESP32
- Buka file `.ino` di Arduino IDE
- Install library DHT sensor library by Adafruit
- Pilih board: ESP32 Dev Module
- Hubungkan ESP32 ke komputer
- Upload kode ke ESP32

### 3. Konfigurasi WiFi
Edit file konfigurasi:
```cpp
const char* ssid = "NAMA_WIFI_ANDA";
const char* password = "PASSWORD_WIFI";
```

### 4. Koneksi Hardware
```
DHT11 DATA pin -> ESP32 GPIO 4
DHT11 VCC -> 3.3V
DHT11 GND -> GND
```

## 📖 Cara Penggunaan

1. Power on ESP32
2. Tunggu koneksi WiFi (indikator LED)
3. Akses dashboard monitoring di browser
4. Pantau suhu dan kelembaban secara real-time

## 📊 Spesifikasi Sensor

| Parameter | Range | Akurasi |
|-----------|-------|---------|
| Suhu | 0-50°C | ±2°C |
| Kelembaban | 20-90% | ±5% |

## 🤝 Kontribusi

Kontribusi terbuka! Silakan:
- Fork repo ini
- Buat branch fitur
- Submit Pull Request

## 📄 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT.

## 📞 Kontak

Rasyid Achmad Fauzi - [@arapcihuy](https://github.com/arapcihuy)

Project Link: [https://github.com/arapcihuy/realtime-monitoring-dht-11-sensor-with-esp-32](https://github.com/arapcihuy/realtime-monitoring-dht-11-sensor-with-esp-32)
