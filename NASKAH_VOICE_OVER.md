# 🎙️ Naskah Lengkap Voice Over (VO) & Narasi Suara
## Platform Belajar Anak Usia Dini "Taman Pintar" 🦉✨

Dokumen ini berisi seluruh transkrip naskah suara (*voice-over / speech narration script*), arahan pengisi suara (*voice acting direction*), dan pembagian kategori teks narasi yang digunakan di dalam aplikasi **Taman Pintar**.

---

## 📋 Informasi & Profil Karakter Pengisi Suara

| Profil Persona | Ikon | Karakter Suara | Nada & Tempo | Rekomendasi Karakteristik |
| :--- | :---: | :--- | :--- | :--- |
| **Si Huki Ceria** *(Default)* | 🦉 | Suara laki-laki tegas, ceria & bertenaga (Bariton Cowok Ramah) | Pitch: 0.82 – 0.92, Rate: 1.04 | Suara laki-laki yang mantap, ramah, energik, artikulasi jernih dan bersemangat. |
| **Bunda Ramah** | 👩‍🏫 | Ibu guru / sosok bunda penyayang | Pitch: 1.22, Rate: 0.94 | Suara lembut, keibuan, menenangkan, artikulasi jelas. |
| **Sahabat Cilik** | 👦 | Teman sebaya anak laki-laki yang lincah | Pitch: 0.88 – 1.02, Rate: 1.08 | Suara anak laki-laki ceria & ekspresif. |

---

## 1. 🌟 Layar Pembuka (*Splash Screen*) & Navigasi Utama

| ID / Pemicu | Teks Naskah Voice Over | Arahan Intonasi / Konteks |
| :--- | :--- | :--- |
| `VO_SPLASH_START` | *"Selamat datang di Taman Pintar! Pilih dunia belajarmu ya!"* | Sangat ceria, hangat, menyambut anak memasuki dunia belajar. |
| `VO_SPLASH_HUKI` | *"Halo! Aku Si Huki! Yuk tekan tombol Mulai Petualangan!"* | Mengajak dan memberi petunjuk ramah saat maskot disentuh. |
| `VO_TOPIC_HERO` | *"Halo Sahabat Cilik! Aku Si Huki! Geser komidi putar dan pilih tema yang kamu suka ya!"* | Panduan eksplorasi saat berada di komidi putar topik. |

---

## 2. 🎡 Sambutan 11 Dunia Belajar (*Topic Welcome Speeches*)

Naskah ini disuarakan secara otomatis saat anak memilih salah satu dunia belajar dari komidi putar:

| ID Topik | Nama Topik | Teks Sambutan Voice Over |
| :--- | :--- | :--- |
| `VO_TOPIC_NUMBERS` | **Angka & Berhitung** | *"Selamat datang di Dunia Angka & Berhitung! Ayo bermain angka seru bersama Si Huki!"* |
| `VO_TOPIC_LETTERS` | **Huruf & Kata** | *"Selamat datang di Dunia Huruf & Kata! Yuk kenali huruf-huruf manis dan kosakata baru!"* |
| `VO_TOPIC_ANIMALS` | **Dunia Hewan** | *"Selamat datang di Dunia Hewan! Meong, Guk, Moo! Ayo kenali suara dan sahabat satwa!"* |
| `VO_TOPIC_COLORS` | **Warna & Bentuk** | *"Selamat datang di Dunia Warna & Bentuk! Ayo ciptakan keindahan warna-warni bersama!"* |
| `VO_TOPIC_HABITS` | **Kebiasaan Baik** | *"Selamat datang di Dunia Kebiasaan Baik! Senyum ceria, hidup bersih dan sehat!"* |
| `VO_TOPIC_MUSIC` | **Suara & Musik** | *"Selamat datang di Dunia Suara & Musik! Ayo mainkan melodi gembira bersama Si Huki!"* |
| `VO_TOPIC_VEHICLES` | **Kendaraan Ceria** | *"Selamat datang di Dunia Kendaraan Ceria! Nguung, tuut-tuut! Ayo kenali berbagai transportasi hebat!"* |
| `VO_TOPIC_NATURE` | **Alam & Cuaca** | *"Selamat datang di Dunia Alam & Cuaca! Lihat langit yang indah, matahari cerah, dan pelangi warna-warni!"* |
| `VO_TOPIC_FRUITS` | **Buah & Sayur** | *"Selamat datang di Dunia Buah & Sayur! Makan buah dan sayur segar membuat tubuh kuat dan pintar!"* |
| `VO_TOPIC_BODY` | **Tubuh & Panca Indra** | *"Selamat datang di Dunia Tubuh & Panca Indra! Ayo kenali bagian tubuh kita yang hebat dan cara merawatnya!"* |
| `VO_TOPIC_PROFS` | **Ragam Profesi** | *"Selamat datang di Dunia Ragam Profesi! Apa cita-citamu saat besar nanti? Ayo kenali sahabat profesi!"* |

---

## 3. 👥 Pemilihan Mode & Menu Panduan (*Game Hub*)

| ID / Pemicu | Teks Naskah Voice Over | Arahan Intonasi |
| :--- | :--- | :--- |
| `VO_MODE_SOLO` | *"Mode Main Sendiri yang santai dan ceria!"* | Santai, menyenangkan, fokus mandiri. |
| `VO_MODE_2P` | *"Mode Main Berdua! Ajak temanmu bermain bersama!"* | Bersemangat, mengajak kolaborasi / duel. |
| `VO_HERO_MASCOT` | *"Aku Si Huki! Senang sekali belajar [Nama Topik] bersamamu!"* | Riang, akrab, menyemangati belajar. |

---

## 4. 🐾 Pemilihan Karakter Hewan (*Avatar Picker*)

| ID / Pemicu | Teks Naskah Voice Over | Keterangan |
| :--- | :--- | :--- |
| `VO_AVATAR_INTRO` | *"Pilih karakter hewan favoritmu ya!"* | Panduan awal masuk layar avatar. |
| `VO_AVATAR_LION` | *"Singa"* | Pengucapan nama karakter singa 🦁 |
| `VO_AVATAR_PANDA` | *"Panda"* | Pengucapan nama karakter panda 🐼 |
| `VO_AVATAR_RABBIT` | *"Kelinci"* | Pengucapan nama karakter kelinci 🐰 |
| `VO_AVATAR_TIGER` | *"Harimau"* | Pengucapan nama karakter harimau 🐯 |
| `VO_AVATAR_ELEPHANT` | *"Gajah"* | Pengucapan nama karakter gajah 🐘 |
| `VO_AVATAR_PENGUIN` | *"Penguin"* | Pengucapan nama karakter penguin 🐧 |
| `VO_AVATAR_GIRAFFE` | *"Jerapah"* | Pengucapan nama karakter jerapah 🦒 |
| `VO_AVATAR_MONKEY` | *"Monyet"* | Pengucapan nama karakter monyet 🐵 |
| `VO_AVATAR_BEAR` | *"Beruang"* | Pengucapan nama karakter beruang 🐻 |
| `VO_AVATAR_CROCODILE` | *"Buaya"* | Pengucapan nama karakter buaya 🐊 |

---

## 5. 🎮 Instruksi & Narasi Gameplay Interaktif

### A. 🌻 Kebun Panen Ceria (*Garden Collect*)
- **Instruksi Mulai Ronde:**  
  *"Cari dan pilih hanya [Jumlah] [Nama Benda] ya! Hati-hati jangan pilih benda lain!"*
- **Hitungan Petikan Benar:**  
  *"Satu!"*, *"Dua!"*, *"Tiga!"*, *"Empat!"*, *"Lima!"*
- **Salah Petik (Distractor):**  
  *"Bukan yang itu! Cari [Nama Benda] ya!"*

### B. 📖 Cerita Petualangan (*Story Map Quest*)
- **Sapaan Maskot di Pos:**  
  *"Bantu Si Huki menyelesaikan pos petualangan ini ya!"*
- **Membacakan Soal Pos:** *(Sesuai soal pos yang aktif)*

### C. 🌉 Jembatan Logika Urut (*Bridge Sequence*)
- **Instruksi Susun Jembatan:**  
  *"Tarik dan lepaskan balok ke kotak jembatan yang tepat ya!"*

### D. ✨ Cocokkan Ceria (*Solo Matching*)
- **Instruksi Ronde:**  
  *"Pilih gambar yang sama dengan [Nama Benda] ya!"*
- **Jawaban Benar:**  
  *"[Nama Benda] cocok!"*
- **Jawaban Salah:**  
  *"Coba cari yang sama ya!"*

### E. 🛒 Toko Ceria Si Huki (*Shop Drag & Drop*)
- **Instruksi Belanja:**  
  *"Tolong tarik dan masukkan [Jumlah] [Nama Benda] ke dalam keranjang ya!"*
- **Hitungan Barang Masuk:**  
  *"Satu!"*, *"Dua!"*, *"Tiga!"*, *"Empat!"*
- **Salah Masukkan Barang:**  
  *"Bukan yang itu, cari [Nama Benda] ya!"*
- **Barang Diklik Tanpa Ditarik:**  
  *"Tarik ke keranjang ya!"*

### F. 🧩 Puzzle Pasang Gambar (*Jigsaw Picture Puzzle*)
- **Instruksi Susun Puzzle:**  
  *"Tarik dan satukan 4 kepingan puzzle [Nama Benda] ke bingkai kanvas ya!"*

### G. 🎹 Piano & Tangga Nada Musik (*Music Playground*)
- **Instruksi Bermain Musik:**  
  *"Mainkan piano nada sesukamu bersama Si Huki!"*

### H. 🚂 Kereta Logika Urutan (*Train Sequence*)
- **Instruksi Gerbong Kosong:**  
  *"Gerbong keretanya kosong satu! Huruf atau Angka berapa yang hilang?"*

### I. 🎈 Letup Balon Bergiliran (*Balloon Pop Duel*)
- **Giliran Pemain:**  
  *"Giliran [Pemain 1 / Pemain 2]! [Teks Soal Target]"*

---

## 6. ❓ Template Pertanyaan Edukatif (*Dynamic Question Prompts*)

Format naskah pertanyaan yang dibacakan secara dinamis pada mode kuis/balapan:

| Topik Pembelajaran | Format Naskah Pertanyaan | Contoh Narasi |
| :--- | :--- | :--- |
| **Angka & Berhitung** | `"Ada berapa jumlah [Nama Benda]? Hitung lalu pilih angkanya!"` | *"Ada berapa jumlah Apel? Hitung lalu pilih angkanya!"* |
| **Huruf & Kata** | `"Manakah yang berawalan huruf '[Huruf]'?"` | *"Manakah yang berawalan huruf 'B'?"* |
| **Dunia Hewan (Suara)** | `"Siapakah yang suaranya '[Suara Hewan]'?"` | *"Siapakah yang suaranya 'Moo-moo'?"* |
| **Dunia Hewan (Makanan)** | `"Makanan kesukaan [Nama Hewan] apa ya?"` | *"Makanan kesukaan Kelinci apa ya?"* |
| **Warna & Bentuk (Bentuk)** | `"Manakah yang berbentuk [Nama Bentuk]?"` | *"Manakah yang berbentuk Segitiga?"* |
| **Warna & Bentuk (Warna)** | `"Manakah yang berwarna [Nama Warna]?"` | *"Manakah yang berwarna Kuning?"* |
| **Kebiasaan Baik** | `"Pilihan yang tepat kita pakai untuk [Nama Kebiasaan] adalah..."` | *"Pilihan yang tepat kita pakai untuk Menggosok Gigi adalah..."* |
| **Suara & Musik** | `"Alat musik yang bunyinya '[Bunyi/Nada]' adalah..."` | *"Alat musik yang bunyinya 'Ting-ting' adalah..."* |
| **Kendaraan (Suara)** | `"Kendaraan apakah yang suaranya '[Suara Kendaraan]'?"` | *"Kendaraan apakah yang suaranya 'Tuut-tuut'?"* |
| **Kendaraan (Jalur)** | `"Manakah yang berjalan di [Darat / Udara / Air]?"` | *"Manakah yang berjalan di Udara?"* |
| **Alam & Cuaca** | `"Pilihan manakah yang [Deskripsi Fenomena Alam]?"` | *"Pilihan manakah yang Terbit di pagi hari menghangatkan bumi?"* |
| **Buah & Sayur** | `"Manakah yang berwarna [Warna] dan [Manfaat/Ciri Nutrisi]?"` | *"Manakah yang berwarna Oranye dan Bagus untuk kesehatan mata?"* |
| **Tubuh & Panca Indra** | `"Manakah yang kita gunakan untuk [Fungsi Organ/Indra]?"` | *"Manakah yang kita gunakan untuk Melihat pemandangan indah?"* |
| **Ragam Profesi** | `"Siapakah yang bertugas [Tugas/Profesi]?"` | *"Siapakah yang bertugas Memadamkan api saat kebakaran?"* |

---

## 7. 🏆 Layar Kemenangan & Hadiah Koleksi Stiker

| ID / Pemicu | Teks Naskah Voice Over | Konteks |
| :--- | :--- | :--- |
| `VO_WIN_SOLO` | *"Hore! Hebat sekali! Kamu pintar dan menyelesaikan petualangan dengan luar biasa!"* | Selesai menyelesaikan mode solo / 3 bintang. |
| `VO_WIN_DUEL` | *"Hore! Hebat sekali [Pemain 1 / Pemain 2]! Kamu luar biasa!"* | Menang pada mode kompetisi 2 pemain. |
| `VO_WIN_COOP` | *"Hore! Kita berhasil menang bersama! Kerja sama yang luar biasa!"* | Menang pada mode gotong royong bintang. |
| `VO_STICKER_UNLOCKED` | *"Hore! Kamu dapat stiker baru, [Nama Stiker]!"* | Membuka kotak hadiah misteri stiker. |
| `VO_STICKER_CARD` | *"Stiker [Nama Stiker]! [Deskripsi Stiker]"* | Membuka detail stiker di album koleksi. |

---

## 8. ⚙️ Pengaturan Suara & Uji Profil Narator

| Pemicu Pengaturan | Teks Naskah Voice Over |
| :--- | :--- |
| **Mengaktifkan Suara Narasi** | *"Suara narasi ceria aktif!"* |
| **Memilih Persona Si Huki** | *"Halo! Aku Si Huki ceria! Ayo kita bertualang dan belajar seru bersama!"* |
| **Memilih Persona Bunda Ramah** | *"Halo sayang! Bunda siap menemani belajarmu!"* |
| **Memilih Persona Sahabat Cilik** | *"Hai kawan! Ayo bermain dan belajar seru bareng aku!"* |
| **Memilih Tingkat Mudah** | *"Mode Mudah dan Santai ceria!"* |
| **Memilih Tingkat Normal** | *"Mode Normal seru!"* |

---

*Dokumen ini dibuat otomatis sebagai panduan narasi resmi aplikasi **Taman Pintar**.*
