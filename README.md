# 🦉 Taman Pintar — Platform Belajar Anak Usia Dini Ceria

**Taman Pintar** adalah aplikasi web interaktif, edukatif, dan ramah anak usia dini (PAUD/TK) yang dirancang untuk merangsang kognitif, motorik, bahasa, logika, dan kreativitas anak melalui petualangan belajar yang menyenangkan bersama maskot **Si Huki**.

---

## ✨ Fitur Utama

- 🎙️ **Voice Narasi Interaktif (Text-to-Speech)**: Memandu anak dengan suara ramah berbahasa Indonesia di setiap tema, instruksi, dan pujian.
- 🎠 **Komidi Putar Tema (Carousel)**: Navigasi tema belajar yang ceria, interaktif, dan mudah digeser baik di layar sentuh (*touch*) maupun desktop (*mouse*).
- 🎮 **2 Mode Bermain Utama**:
  - **Petualangan Sendiri (Mode Solo)**: Fokus pada eksplorasi, belajar bertahap, dan penguasaan materi secara mandiri.
  - **Main Berdua (Mode 2 Pemain / Duel Ceria)**: Bermain bersama teman atau orang tua dalam kompetisi sehat dan kooperatif di satu perangkat.
- 🎨 **Desain Khusus Anak (Kid-Friendly UI/UX)**:
  - Font ceria dan mudah dibaca (*Fredoka*, *Baloo 2*, *Nunito*).
  - Warna-warni permen cerah (*Candy Palette*) dengan animasi tombol bergoyang (*jelly button*), efek partikel bintang, dan balon konfeti.
  - Bebas tombol membingungkan dan ramah sentuhan jari anak.
- 🔊 **Efek Suara Sintetis Web Audio API**: Suara nada piano, letupan balon, tepuk tangan riang, dan jingle kemenangan tanpa ketergantungan file audio eksternal yang berat.

---

## 📚 Tema Pembelajaran

Tersedia **10 Tema Edukasi Lengkap** untuk tumbuh kembang anak:

| No | Tema | Ikon | Deskripsi |
|---|---|---|---|
| 1 | **Angka & Berhitung** | 🔢 | Mengenal angka, berhitung benda, dan perbandingan santai |
| 2 | **Huruf & Kata** | 🔤 | Mengenal alfabet A–Z, mencocokkan bunyi awal huruf dan kosakata benda |
| 3 | **Dunia Hewan** | 🐱 | Mengenal fauna, suara khas satwa, makanan kesukaan, dan habitat |
| 4 | **Warna & Bentuk** | 🎨 | Mengenal warna-warni cerah dan aneka bangun geometri dasar |
| 5 | **Kebiasaan Baik** | 🪥 | Mengenal pola hidup sehat, kebersihan diri, sopan santun & kemandirian |
| 6 | **Suara & Musik** | 🎵 | Eksplorasi alat musik, piano interaktif Do-Re-Mi, dan irama ceria |
| 7 | **Kendaraan Ceria** | 🚗 | Mengenal transportasi darat, laut, udara beserta ciri khasnya |
| 8 | **Alam & Cuaca** | ☀️ | Mengenal matahari, hujan, awan, pelangi, dan fenomena alam |
| 9 | **Buah & Sayur** | 🍎 | Mengenal aneka buah manis, sayur segar, dan nutrisi tubuh sehat |
| 10 | **Tubuh & Panca Indra** | 👀 | Mengenal fungsi mata, telinga, hidung, tangan, dan merawat tubuh |
| 11 | **Ragam Profesi** | 👨‍🚒 | Mengenal dokter, pemadam kebakaran, guru, koki, polisi & cita-cita |

---

## 🕹️ Ragam Mini-Game Seru

### 🌟 Mode Petualangan Sendiri (Solo)
1. **🌻 Kebun Koleksi Ceria**: Mengumpulkan objek sesuai instruksi soal kuis tematik interaktif.
2. **📖 Cerita Petualangan**: Menjelajahi 5 pos petualangan bertahap dengan tantangan bertingkat.
3. **🌉 Jembatan Urut Logika**: Menyusun dan menempatkan balok kayu urutan angka/huruf/pola untuk menyeberang.
4. **✨ Cocokkan Ceria**: Menjodohkan gambar dan pasangan konsep yang tepat.
5. **🛒 Toko Ceria Si Huki**: Belanja interaktif dengan menarik (*drag & drop*) barang pesanan langsung ke dalam keranjang rotan belanjaan besar.
6. **🧩 Puzzle Pasang Gambar**: Menyusun kepingan puzzle gambar tematik.
7. **🎹 Piano & Tangga Nada** *(Khusus Tema Musik)*: Keyboard piano virtual interaktif dengan tangga nada C-D-E-F-G-A-B-C.

### 👥 Mode Main Berdua (2 Pemain / Duel)
1. **🏎️ Balap Cepat**: Adu kecepatan menjawab soal kuis untuk melajukan mobil balap / roket menuju garis finis.
2. **🎈 Letup Balon Bergiliran**: Adu ketangkasan dan fokus meletupkan balon sasaran bergantian.
3. **🧠 Kartu Memori Berdua**: Menguji daya ingat dengan membuka dan mencocokkan pasangan kartu tertutup.
4. **🚂 Kereta Logika**: Melengkapi gerbong kereta api dengan memilih urutan gerbong yang tepat.
5. **🎯 Papan Bingo Ceria**: Mengisi garis bingo dengan menjawab pertanyaan tematik.
6. **🧺 Tangkap Objek Jatuh**: Menangkap buah/benda jatuh yang tepat ke keranjang masing-masing pemain.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik dan antarmuka ramah mobile/desktop.
- **CSS3 (Vanilla)**:
  - Flexbox & Grid Layout yang sepenuhnya responsif.
  - Animasi CSS keyframes (*Jelly Buttons*, *Pulse*, *Drop In*, *Cart Jiggle*).
  - Modern Glassmorphism & Claymorphism style.
- **JavaScript (Vanilla ES6+)**:
  - Logika state management, carousel gestur drag & touch.
  - Web Audio API (Osilator synthesizer untuk efek suara & piano).
  - Web Speech API (`speechSynthesis`) untuk suara narator Bahasa Indonesia.
  - Drag and Drop API + Touch Event Fallback.

---

## 🚀 Cara Menjalankan Aplikasi

Aplikasi ini bersifat **standalone (tanpa instalasi runtime/server khusus)**:

1. **Unduh / Clone Repository**:
   ```bash
   git clone https://github.com/username/media-belajar-anak.git
   ```
2. **Buka Aplikasi**:
   - Cukup buka file `index.html` langsung menggunakan web browser modern (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, atau Opera).
   - Atau gunakan ekstensi seperti **Live Server** di VS Code.
3. **Tips Pengalaman Terbaik**:
   - Pastikan volume suara perangkat menyala untuk mendengarkan suara Si Huki dan efek musik.
   - Gunakan resolusi layar tablet atau desktop untuk tampilan visual optimal.

---

## 📂 Struktur File

```
media-belajar-anak/
│
├── index.html          # File utama aplikasi (berisi markup, styling CSS, dan logika JavaScript)
├── README.md           # Dokumentasi resmi proyek
├── assets/             # Direktori aset pendukung
└── avatar 3D.png       # Aset grafis maskot Si Huki
```

---

## 📜 Lisensi & Penggunaan

Proyek ini dibuat untuk keperluan media edukasi anak usia dini dan pembelajaran interaktif. Bebas digunakan, dikembangkan, dan dimanfaatkan untuk media pembelajaran di rumah maupun sekolah. 🌟
