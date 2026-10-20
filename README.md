# VERITASK AI - Platform Deteksi Hoaks & Portal Transparansi Informasi Cerdas

> **Karya Inovasi Teknologi Informasi untuk Keterbukaan & Integritas Publik (Kategori Lomba GDI 2026)**  
> Dibangun murni menggunakan arsitektur web modern: **HTML5, CSS3, Vanilla JavaScript (ES6+), Leaflet.js GIS, dan On-Device Machine Learning (TF-IDF + Softmax Classifier)** dengan dukungan **Tesseract.js (In-Browser OCR)**, **Modul Forensik Citra Digital (Error Level Analysis & EXIF Inspector)**, **Radar Titik Spasial Multi-Level (Kecamatan, Kabupaten/Kota, Provinsi)**, **Etalase Berita Lolos Verifikasi (100% Sahih)**, **Speech-to-Text Mikrofon (Web Speech Recognition API)**, **WhatsApp Verification Bot Simulator**, dan opsi **Deep Context Gemini LLM**.

---

## 🌟 Tentang Proyek

Di era ledakan disinformasi digital (*infodemic*), masyarakat sering kali menjadi korban manipulasi psikologis seperti kabar bohong berantai, hoaks bantuan sosial, klaim gempa tanpa dasar sains, maupun penipuan finansial.

Sebagian besar alat pendeteksi hoaks konvensional bekerja sebagai *black box* (hanya memberikan label tanpa alasan jelas) dan hanya fokus pada sanggahan hoaks setelah kabar terlanjur viral. **VERITASK AI** hadir dengan paradigma baru: **Explainable AI, Transparansi Spasial, dan Kurasi Berita Resmi Lolos Verifikasi**:

1. **Model Deteksi Machine Learning On-Device**: Model klasifikasi berbasis ekstraksi fitur n-gram, *Term Frequency-Inverse Document Frequency* (TF-IDF), dan probabilitas Softmax yang berjalan 100% lokal di peramban tanpa memerlukan API key maupun backend server eksternal.
2. **Etalase Berita Lolos Verifikasi (100% Sahih / Non-Hoaks) - *Harga Jual Utama***: Menampilkan kurasi berita dan siaran pers resmi dari otoritas terakreditasi (Kemensos, BMKG, Kemenkes, OJK, Kemendikbudristek, Samsat/Bapenda) lengkap dengan stempel sertifikat integritas `[TERVERIFIKASI SAHIH - 100% NON-HOAKS]` sebagai benteng rujukan informasi utama masyarakat.
3. **Radar Titik Spasial Multi-Level ala Google Maps (Kecamatan, Kabupaten, Provinsi)**: Pemetaan geografis presisi tinggi dengan puluhan koordinat GPS nyata di seluruh Indonesia (mulai dari Coblong Bandung, Cibinong Bogor, Depok Sleman, Klojen Malang, hingga Sepaku IKN dan Jayapura Utara), dilengkapi visual pin cyber berdenyut (*pulsating radar marker*), pencarian instan nama kecamatan, serta inspektur data mikro (*Spatial Threat Inspector*).
4. **Explainable AI (Penalaran Transparan)**: Membedah struktur klaim kalimat per kalimat, memberi highlight interaktif pada kata manipulatif, serta merinci skor multi-faktor secara terbuka.
5. **Modul Forensik Citra Digital (ELA & EXIF Inspector)**: Mengukur anomali kompresi piksel foto (*Error Level Analysis*) dan menginspeksi metadata biner untuk mengungkap manipulasi grafis atau jejak software penyunting (*Adobe Photoshop, Canva, dsb.*).
6. **Input Suara Mikrofon (Speech-to-Text Bahasa Indonesia)**: Menggunakan Web Speech Recognition API bawaan peramban agar masyarakat cukup berbicara untuk memeriksa kabar.
7. **In-Browser OCR (Tesseract.js Engine)**: Ekstraksi teks otomatis dari tangkapan layar chat WhatsApp atau media sosial langsung di peramban tanpa server eksternal.
8. **Live Online Fact-Check Feed & Radar Ticker**: Terhubung langsung dengan feed online berita cek fakta hangat terkini dari konsorsium kredibel (TurnBackHoax/Mafindo, Kominfo).
9. **Simulasi WhatsApp Verification Bot (VERITASK AI Assistant)**: Widget interaktif WhatsApp CekFakta di pojok layar dengan wawasan probabilitas Machine Learning untuk mendemonstrasikan aksesibilitas bagi grup pesan tertutup (*Dark Social*).
10. **Mode Tampilan Gelap & Terang (Dark/Light Mode)**: Fleksibilitas visual dengan tema kontras cyber sentinel berpadu dengan aksen High-Tech Red & Blue.
11. **Ekspor Laporan Transparansi PDF Resmi**: Cetak dokumen audit bukti keaslian informasi dengan nomor tiket verifikasi unik (`VTK-XXXXXX`).

---

## 🚀 Tiga Tab Utama Aplikasi

Aplikasi dirancang fokus, tajam, dan efisien dalam 3 modul inti:

1. **Tab 1: Pindai Berita (Scanner)**
   - Audit teks berbasis **Machine Learning On-Device (TF-IDF + Softmax Classifier)** dan NLP heuristik multi-faktor.
   - Panel visualisasi probabilitas neural ($P(\text{Hoaks})$ vs $P(\text{Valid})$), skor confidence, dan bobot leksikal terkuat (*Feature Importance*).
   - Perekam suara mikrofon (*Speech-to-Text* id-ID).
   - Ekstraksi gambar tangkapan layar (*In-Browser OCR Tesseract.js*).
   - Modul Forensik Citra Digital (*Error Level Analysis Canvas* & *EXIF Metadata Inspector*).
   - Explainable AI text annotations, skor integritas gauge, dan rekomendasi mitigasi.
   - Integrasi opsional Google Gemini 1.5 Flash untuk analisis konteks mendalam.
   - Ekspor Dokumen Laporan Transparansi Resmi (PDF/Print).

2. **Tab 2: Transparansi (Spatial Intelligence & Open Data)**
   - Dashboard statistik keterbukaan publik (KPI Counters dengan animasi odometer).
   - **Radar Titik Spasial ala Google Maps (Leaflet Dark Matter)** dengan data presisi tingkat **Kecamatan, Kabupaten/Kota, dan Provinsi**.
   - Bilah pencarian instan nama kecamatan/kabupaten (misal: "Coblong", "Sleman", "IKN", "Jayapura").
   - Filter dinamis kategori isu spasial (*Pilkada & Politik, Bencana Alam, Penipuan Bansos, Kesehatan*).
   - Pilihan toggle ke Heatmap Choropleth SVG 34 provinsi.
   - Panel *Spatial Threat Inspector* yang merinci status kerawanan lokal dan kasus dominan di titik koordinat yang dipilih.

3. **Tab 3: Live Cek Fakta & Portal Berita Lolos Verifikasi**
   - **🌟 Etalase Berita Lolos Verifikasi (100% Sahih / Non-Hoaks)**: Ditampilkan secara default sebagai nilai jual utama, memuat siaran resmi terkurasi berstempel sertifikat integritas.
   - **🚨 Tab Klarifikasi Hoaks**: Rangkuman sanggahan rumor yang dibantah instansi terkait.
   - Sinkronisasi real-time dengan feed online berita cek fakta hangat (*TurnBackHoax RSS*).
   - Live Running Marquee Ticker di bagian atas halaman untuk pembaruan cepat.
   - Pencarian instan dan filter kategori (*Sosial & Bansos, Kesehatan, Bencana Alam, Pendidikan, Finansial*).
   - Tombol **"Uji Berita Ini di Scanner"** untuk pengujian 1-klik langsung ke modul audit.

---

## 💻 Cara Menjalankan Aplikasi

Aplikasi ini beroperasi murni di sisi klien (**Zero Installation / Zero Backend Dependencies**):
1. Masuk ke folder proyek: `c:\Users\RIDAN NURROZIQIN M\OneDrive\Documents\LOMBA GDI\`
2. Klik ganda (**Double Click**) file `index.html`, atau buka melalui peramban web modern favorit Anda (Google Chrome / Microsoft Edge direkomendasikan untuk Web Speech API).
3. Seluruh fitur langsung aktif dan siap digunakan secara penuh!

---

## 🛠️ Struktur Berkas Proyek

```
LOMBA GDI/
├── index.html              # Antarmuka utama aplikasi (Single Page App 3-Tab responsif, Leaflet CDN)
├── css/
│   └── styles.css          # Desain Cyber High-Tech Red & Blue, marker spasial berdenyut, stempel verifikasi, mode gelap/terang, layout cetak PDF
├── js/
│   ├── database.js         # Repositori berita lolos verifikasi (100% sahih), kamus linguistik Indonesia, dataset cek fakta & live RSS fetcher
│   ├── detector.js         # HoaxMLClassifier (TF-IDF + Softmax), NLP heuristik, modul integrasi Gemini LLM, text highlighter
│   ├── forensics.js        # Modul Forensik Citra: Error Level Analysis (ELA) & EXIF/Photoshop Metadata Inspector
│   ├── map-data.js         # Dataset koordinat titik spasial (Kecamatan, Kabupaten, Provinsi) & SpatialLeafletManager
│   └── app.js              # Controller UI, Speech-to-Text (STT), OCR Tesseract.js, filter berita lolos verifikasi, dan WhatsApp Bot
└── README.md               # Dokumentasi lengkap proyek
```

---

## 🔬 Metodologi Deteksi & Machine Learning

### 1. Klasifikasi Machine Learning On-Device
- **Tokenisasi & Preprocessing**: Penghapusan tanda baca khusus, *lowercasing*, dan eliminasi kata sambung (*stopwords*) bahasa Indonesia.
- **Ekstraksi Fitur N-Gram (Unigram & Bigram)**: Menangkap frasa kritis seperti *"segera sebarkan"*, *"tautan bansos"*, *"dana kaget"*, *"info a1"*, *"siaran pers"*, *"kanal resmi"*.
- **Pembobotan TF-IDF**: Menghitung bobot kepentingan term leksikal relatif terhadap korpus verifikasi.
- **Fungsi Aktivasi Softmax**: Menghasilkan distribusi probabilitas mutlak:
  $$P(\text{Hoaks}) = \frac{e^{z_{\text{hoaks}}}}{e^{z_{\text{hoaks}}} + e^{z_{\text{valid}}}}, \quad P(\text{Valid}) = 1 - P(\text{Hoaks})$$

### 2. Multi-Factor Integrity Matrix
$$\text{Skor Kredibilitas} = (L \times 0.30) + (S \times 0.30) + (U \times 0.25) + (C \times 0.15)$$
Di mana $L$ adalah Integritas Bahasa, $S$ adalah Atribusi Sumber Resmi, $U$ adalah Urgensi Semu/FOMO, dan $C$ adalah Korelasi Basis Data Cek Fakta.

---

## 🏆 Fitur Unggulan Nilai Tambah Juri Lomba

1. **Machine Learning On-Device (Zero Server Leak)**: Memberikan klasifikasi probabilitas tanpa membebani biaya server atau risiko kebocoran privasi data pengguna.
2. **Katalog Berita Lolos Verifikasi (100% Sahih)**: Fitur diferensiasi utama yang berorientasi solusi positif, menghadirkan rujukan berita yang terjamin keasliannya dari instansi pemerintah.
3. **Peta Titik Spasial Multi-Level (Kecamatan, Kabupaten, Provinsi)**: Pemetaan geografis realistis dengan fitur pencarian instan dan marker radar bercahaya ala Google Maps.
4. **Modul Forensik Citra Digital (Error Level Analysis & EXIF Inspector)**: Mendeteksi tempelan visual dan jejak software editor grafis langsung di peramban.
5. **Speech-to-Text Mikrofon (Web Speech API)**: Kemudahan audit suara instan bagi masyarakat awam.
6. **OCR Tangkapan Layar Tesseract.js**: Pembacaan otomatis gambar chat tanpa dependensi server luar.
7. **Simulasi WhatsApp CekFakta Bot**: Menunjukkan kesiapan integrasi aplikasi ke kanal obrolan tertutup (*Dark Social*).
8. **Ekspor Laporan Audit PDF**: Dokumen verifikasi resmi bernomor tiket unik siap cetak.
