# WeatherFinder v2 🌤️

Aplikasi pencari cuaca berbasis React Native. User mengetik nama kota, aplikasi mengambil data lokasi dan cuaca terkini dari Open-Meteo API, lalu menampilkannya dalam bentuk kartu cuaca dengan tema warna yang menyesuaikan siang/malam.

## Fitur

- Pencarian cuaca berdasarkan nama kota
- Loading state, error state, dan empty state
- Mapping kode cuaca WMO ke label & emoji berbahasa Indonesia

**Fitur Level 2 yang dipilih:**
- ✅ Debounce input pencarian (500ms) + cancel request lama dengan `AbortController`
- ✅ Tombol refresh untuk memuat ulang data kota yang sama
- ✅ Dynamic theming (warna latar & teks berubah otomatis sesuai siang/malam)

## Screenshot (Expo Go)
<img width="717" height="1600" alt="wf3" src="https://github.com/user-attachments/assets/0c029eb2-e524-4846-87bb-aae027ce015c" />
<img width="717" height="1600" alt="wf2" src="https://github.com/user-attachments/assets/20d0356a-2e7e-40b0-8ad8-7b873fe6339c" />
<img width="717" height="1600" alt="wf1" src="https://github.com/user-attachments/assets/3b3b74c8-ee08-45c4-8925-26f21a8a55dc" />


## Cara Menjalankan

```bash
npm install
npx expo start
```

Lalu scan QR code yang muncul menggunakan aplikasi **Expo Go** di HP (Android/iOS).

## Tech Stack

- React Native
- Expo
- Open-Meteo API (Geocoding + Forecast) — gratis, tanpa API key

## Expo Snack
https://snack.expo.dev/@meisyananda/per10_
