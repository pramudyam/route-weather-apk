# RouteWeather Android APK

Aplikasi Android pelacak rute dan prediksi cuaca sepanjang perjalanan berbasis WebView, OSRM routing engine, dan Open-Meteo batch weather forecast.

## Fitur Utama
- **Batch Route Weather:** Menghitung prediksi cuaca per titik checkpoint di sepanjang rute perjalanan.
- **GPS Live & Altitude:** Sensor lokasi GPS otomatis dan estimasi elevasi (mdpl).
- **Native AndroidBridge:** Bypass CORS untuk pemanggilan OSRM dan Open-Meteo secara instan dan andal.
- **Dark Mode UI:** Antarmuka responsif bernuansa dark obsidian modern (`#110d26`).

## Build Environment
- Java 17 (Eclipse Temurin)
- Gradle 8.6
- Android SDK 34 / AGP 8.4.2
- Automated Cloud Build via GitHub Actions
