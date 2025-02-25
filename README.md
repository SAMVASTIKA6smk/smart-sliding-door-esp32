# smart-sliding-door-esp32
# README.md - Deskripsi Proyek
"""
# Smart Sliding Door menggunakan ESP32 dan Flask

## Deskripsi
Proyek ini menggunakan ESP32 dengan MicroPython untuk mengontrol pintu geser otomatis. Backend Flask digunakan untuk menghubungkan ESP32 dengan Ubidots untuk monitoring dan kontrol jarak jauh.

## Fitur
- ESP32 membaca dan mengontrol status pintu.
- Backend Flask sebagai API untuk mengontrol pintu.
- Integrasi dengan Ubidots untuk pemantauan real-time.

## Instalasi
1. Clone repository ini:
   ```
   git clone https://github.com/USERNAME/smart-sliding-door-esp32.git
   ```
2. Install dependensi Flask:
   ```
   pip install flask requests
   ```
3. Jalankan Flask:
   ```
   python app.py
   ```
4. Unggah kode MicroPython ke ESP32 menggunakan Thonny atau uPyCraft.

## Konfigurasi
Ubah `SSID`, `PASSWORD`, dan `UBIDOTS_TOKEN` sesuai dengan jaringan dan akun Ubidots Anda.

"""
