# 📊 Database Analyzer with Streamlit & Paramiko

Database Analyzer adalah aplikasi berbasis **Streamlit** yang memungkinkan pengguna untuk **terhubung ke database MySQL melalui SSH**, menjalankan query SQL, serta menganalisis data dengan **tabel dan visualisasi grafis**.

## 🚀 **Fitur Utama**
- **Koneksi ke server MySQL melalui SSH** tanpa perlu koneksi langsung ke database.
- **Eksekusi query SQL secara real-time** untuk mendapatkan data.
- **Visualisasi data** dalam bentuk tabel dan grafik (seaborn & matplotlib).
- **Antarmuka interaktif** dengan Streamlit.

## 📌 **Persyaratan**
Sebelum menjalankan aplikasi, pastikan Anda memiliki:
- **Python 3.x** terinstal
- **MySQL Server** yang dapat diakses melalui SSH
- **Library yang dibutuhkan** (lihat bagian instalasi)

## 🔧 **Instalasi**

1. **Clone repository ini** (jika tersedia di GitHub):
   ```bash
   git clone https://github.com/genta-bahana-nagari/Database_Analyzer_Project.git
   cd Database_Analyzer_Project   #cek nama direktori (folder) setelah clone
   ```
2. **Buat virtual environment (opsional tetapi disarankan):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Jalankan aplikasi Streamlit:**
   ```bash
   streamlit run database-analyzer.py
   ```

## 🎯 **Cara Penggunaan**
1. **Buka aplikasi** di browser setelah menjalankan perintah di atas.
2. **Masukkan konfigurasi server MySQL** pada sidebar, termasuk:
   - IP Server
   - Username & Password SSH
   - Username & Password MySQL
   - Nama Database
3. **Pilih tabel dari database** untuk dianalisis.
4. **Jalankan query SQL** untuk menampilkan data dalam bentuk tabel.
5. **Lihat visualisasi grafik batang** berdasarkan data yang dipilih.
6. **Keluar & konfigurasi ulang** jika diperlukan.

## 🛠 **Teknologi yang Digunakan**
- **Python**
- **Streamlit** (Frontend Interaktif)
- **Paramiko** (Koneksi SSH ke Server)
- **Pandas** (Manipulasi DataFrame)
- **Seaborn & Matplotlib** (Visualisasi Data)

## 📜 **Struktur Proyek**
```
📁 database-analyzer/
│── database-analyzer.py  # File utama aplikasi Streamlit
│── requirements.txt      # Library yang dibutuhkan
│── README.md             # Dokumentasi proyek ini
```

## 💡 **Catatan**
- Pastikan server MySQL mengizinkan koneksi dari **user yang diberikan**.
- Jika mengalami error koneksi, pastikan **SSH dan MySQL berjalan dengan benar**.
- Jika **grafik tidak muncul**, pastikan data yang dipilih memiliki **kolom yang sesuai (stok & title)**.

## 🤝 **Kontribusi**
Jika Anda ingin berkontribusi, silakan fork repository ini dan buat pull request dengan perubahan yang diusulkan. 😊

## 📜 **Lisensi**
Proyek ini dirilis di bawah lisensi **MIT License**. Silakan gunakan dan modifikasi sesuai kebutuhan Anda!

---
💻 Dibuat dengan ❤️ menggunakan **Python & Streamlit**
