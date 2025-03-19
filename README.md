## 🌡️ DHT11 Temperature & Humidity Monitoring with LCD and Relay Control  
> Draft README — by Kelompok 6 ✨   

---

### ✅ Project Overview
Proyek ini bertujuan memonitor suhu dan kelembaban menggunakan sensor **DHT11**, menampilkan data secara real-time di layar **LCD I2C**, dan mengontrol **relay** otomatis untuk menyalakan atau mematikan perangkat (seperti lampu) berdasarkan suhu tertentu.

---

### 🛠️ Komponen yang Digunakan:
- Arduino UNO / Nano
- Sensor DHT11
- LCD 16x2 I2C
- Modul Relay 1 Channel
- Kabel jumper dan breadboard
- Power supply

---

### ⚙️ Fitur Utama:
- Menampilkan suhu (°C) & kelembaban (%) pada LCD dengan ikon custom.
- Kendali otomatis relay:
  - Suhu < 26°C ➡️ Relay ON (lampu menyala)
  - Suhu ≥ 26°C ➡️ Relay OFF (lampu mati)
- Error handling saat sensor gagal membaca data.
- Cocok untuk simulasi kontrol suhu otomatis rumah pintar / green house.

---

### 📜 Cara Kerja Singkat:
1. Arduino membaca data dari DHT11.
2. Data suhu & kelembaban ditampilkan ke LCD.
3. Jika suhu ≥ 26°C, relay dimatikan secara otomatis.
4. Jika suhu di bawah 26°C, relay dinyalakan.

---

### 🚀 Cara Upload:
1. Upload kode melalui Arduino IDE.
2. Pastikan semua komponen sudah terhubung sesuai skema.
3. Lihat hasil pembacaan suhu & kontrol relay pada rangkaian.

---

### 🎥 Demo:
> *(Opsional, bisa ditambahkan link video YouTube di sini)*

---

### 📝 License:
Proyek ini hanya untuk edukasi dan pengembangan pribadi. Feel free to fork & modify!
