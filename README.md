# 📊 Sistem Crawling Data Perusahaan KarirHub

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Selenium](https://img.shields.io/badge/Selenium-4-green?logo=selenium)

Implementasi sistem *web scraping* untuk mengekstrak informasi perusahaan dari platform KarirHub secara otomatis menggunakan Jupyter Notebook.

## ✨ Fitur Utama

- **🤖 Crawling Otomatis**: Mengekstrak data perusahaan berdasarkan kata kunci pencarian secara efisien.
- **🎨 Antarmuka Interaktif**: Menggunakan *IPython Widgets* untuk kontrol yang mudah tanpa perlu mengubah kode sumber.
- **⚙️ Konfigurasi Cepat**: Pengaturan *Selenium WebDriver* dilakukan secara otomatis di latar belakang.
- **📄 Output Terstruktur**: Menghasilkan data dalam format yang rapi dan siap untuk dianalisis lebih lanjut menggunakan Pandas.
- **🇮🇩 Dokumentasi Lengkap**: Panduan dan penjelasan disediakan dalam Bahasa Indonesia yang mudah dipahami.

## 🔧 Tumpukan Teknologi (Tech Stack)

- **Bahasa**: `Python`
- **Automasi & Crawling**: `Selenium`
- **Antarmuka**: `IPython Widgets`
- **Manipulasi Data**: `Pandas`
- **Lingkungan**: `Jupyter Notebook`

## 🚀 Cara Memulai

### Prasyarat
- **Python 3.x** sudah terinstal di sistem Anda.
- **Jupyter Notebook** atau **Visual Studio Code** dengan ekstensi Jupyter.
- **Browser Google Chrome** yang terinstal.

### Instalasi & Penggunaan

1.  **Unduh Notebook**: Dapatkan file `search_company.ipynb` dari *repository* proyek.

2.  **Buka di Jupyter**: Buka *notebook* tersebut di lingkungan Jupyter pilihan Anda.

3.  **Jalankan Sel Berurutan**: Eksekusi setiap *cell* dari atas ke bawah. Skrip akan mengurus instalasi dan konfigurasi yang diperlukan.

4.  **Masukkan Kata Kunci**: Gunakan *widget* interaktif yang muncul untuk mengetik kata kunci perusahaan yang ingin dicari.

5.  **Mulai Crawling**: Klik tombol pencarian pada *widget* dan tunggu hingga proses ekstraksi data selesai. Hasil akan ditampilkan di bawahnya.

## 📊 Struktur Data Output

Data yang berhasil diekstrak akan disajikan dalam DataFrame Pandas dengan kolom-kolom berikut:

| Field          | Deskripsi                               | Contoh                                       |
| -------------- | --------------------------------------- | -------------------------------------------- |
| `nama_perusahaan`| Nama resmi dari perusahaan              | "PT Inovasi Digital Nusantara"               |
| `industri`     | Sektor industri utama perusahaan        | "Teknologi Informasi & Layanan"              |
| `lokasi`       | Lokasi atau kota utama perusahaan       | "Jakarta Selatan, DKI Jakarta"               |
| `deskripsi`    | Ringkasan singkat mengenai perusahaan   | "Menyediakan solusi digital untuk UKM..."    |
| `url_profil`   | Tautan ke halaman profil di KarirHub    | "https://karirhub.com/perusahaan/..."        |

## ⚖️ Lisensi & Etika

- **Lisensi**: Proyek ini dilisensikan di bawah **Lisensi MIT**.
- **Etika Penggunaan**:
    - Harap patuhi **Terms of Service** dari platform KarirHub.
    - Gunakan *delay* yang wajar antar *request* untuk tidak membebani server.
    - Hormati privasi data dan gunakan informasi yang dikumpulkan secara bertanggung jawab.

## 👨‍💻 Author

- **Ferdian Bangkit Wijaya**
- Universitas Sultan Ageng Tirtayasa (UNTIRTA)
- Versi: 1.0.0 (Agustus 2025)

---

> Didesain untuk mempermudah pengumpulan data perusahaan dari KarirHub untuk keperluan penelitian dan analisis data.
