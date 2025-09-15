# gis-viewer
skrip sederhana untuk menampilkan file geospasial (SHP, Geojson, ZIP  dll) dan SLD
# 🌍 Bulukumba GeoViewer

**Bulukumba GeoViewer** adalah aplikasi web berbasis **OpenLayers** untuk menampilkan data spasial dalam berbagai format (**GeoJSON**, **SHP**, **ZIP**) dengan dukungan **SLD styling** dan **legend otomatis**.  
Dikembangkan untuk mendukung transparansi data, validasi cepat, dan kolaborasi antar OPD/SKPD di Kabupaten Bulukumba.

---

## ✨ Fitur Utama
- 📂 **Multi-format**: Mendukung `.geojson`, `.json`, `.shp`, `.zip` (shapefile lengkap), dan `.sld`.
- 🎨 **SLD Styling**: Menampilkan layer sesuai aturan style dari file SLD.
- 🗺 **Auto EPSG Detection**: Membaca file `.prj` untuk mendeteksi proyeksi dan menampilkannya dengan koordinat yang benar.
- 📑 **Legend Otomatis**: Membaca aturan warna dari SLD dan menampilkannya di pojok peta.
- 🖱 **Drag & Drop**: Cukup seret file ke peta untuk langsung melihat hasilnya.
- 🎯 **Fallback Style**: Jika SLD tidak ada, layer tetap tampil dengan style default yang jelas.

---

## 🚀 Cara Menggunakan
1. Buka aplikasi di GitHub Pages:  
   **[Klik di sini untuk membuka Bulukumba GeoViewer](https://username.github.io/gis-viewer/)**  
   *(Ganti `username` dengan username GitHub Anda)*

2. Siapkan file data:
   - **GeoJSON** atau **Shapefile** (SHP/ZIP)
   - Opsional: **SLD** untuk styling

3. **Drag & Drop** file ke area peta:
   - GeoJSON/SHP/ZIP → Layer langsung tampil
   - SLD → Style layer akan berubah sesuai aturan SLD
   - Legend otomatis akan muncul jika SLD valid

---

## 📦 Struktur Repo

Oke, aku buatkan template README.md yang siap kamu taruh di repo GitHub untuk Bulukumba GeoViewer.
README ini akan langsung menjelaskan tujuan, fitur, cara pakai, dan panduan kontribusi, sehingga tim OPD/SKPD atau publik yang membuka repo langsung paham.

📄 Template README.md
# 🌍 Bulukumba GeoViewer

**Bulukumba GeoViewer** adalah aplikasi web berbasis **OpenLayers** untuk menampilkan data spasial dalam berbagai format (**GeoJSON**, **SHP**, **ZIP**) dengan dukungan **SLD styling** dan **legend otomatis**.  
Dikembangkan untuk mendukung transparansi data, validasi cepat, dan kolaborasi antar OPD/SKPD di Kabupaten Bulukumba.

---

## ✨ Fitur Utama
- 📂 **Multi-format**: Mendukung `.geojson`, `.json`, `.shp`, `.zip` (shapefile lengkap), dan `.sld`.
- 🎨 **SLD Styling**: Menampilkan layer sesuai aturan style dari file SLD.
- 🗺 **Auto EPSG Detection**: Membaca file `.prj` untuk mendeteksi proyeksi dan menampilkannya dengan koordinat yang benar.
- 📑 **Legend Otomatis**: Membaca aturan warna dari SLD dan menampilkannya di pojok peta.
- 🖱 **Drag & Drop**: Cukup seret file ke peta untuk langsung melihat hasilnya.
- 🎯 **Fallback Style**: Jika SLD tidak ada, layer tetap tampil dengan style default yang jelas.

---

## 🚀 Cara Menggunakan
1. Buka aplikasi di GitHub Pages:  
   **[Klik di sini untuk membuka Bulukumba GeoViewer](https://username.github.io/gis-viewer/)**  
   *(Ganti `username` dengan username GitHub Anda)*

2. Siapkan file data:
   - **GeoJSON** atau **Shapefile** (SHP/ZIP)
   - Opsional: **SLD** untuk styling

3. **Drag & Drop** file ke area peta:
   - GeoJSON/SHP/ZIP → Layer langsung tampil
   - SLD → Style layer akan berubah sesuai aturan SLD
   - Legend otomatis akan muncul jika SLD valid

---

## 📦 Struktur Repo


gis-viewer/ │ ├── index.html        # File utama aplikasi ├── README.md         # Dokumentasi ini └── assets/           # (Opsional) Logo, ikon, atau file pendukung

---

## 🛠 Pengembangan Lokal
Jika ingin menjalankan di komputer lokal:
```bash
# Jalankan server lokal
python -m http.server 8000

# Buka di browser
http://localhost:8000/index.html



🤝 Kontribusi
- Pull Request dipersilakan untuk perbaikan bug, penambahan fitur, atau peningkatan UI.
- Sertakan deskripsi perubahan dan screenshot jika ada perubahan tampilan.

📜 Lisensi
Proyek ini menggunakan lisensi MIT – silakan gunakan, modifikasi, dan distribusikan dengan atribusi.

📧 Kontak
Dinas Komunikasi dan Informatika Kabupaten Bulukumba
📍 Bulukumba, Sulawesi Selatan
🌐 geoportal.bulukumbakab.go.id

--
