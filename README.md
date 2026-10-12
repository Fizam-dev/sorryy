# 💌 Surat Digital Untuk Ain (Daripada Syafizam)

Web surat digital interaktif yang diilhamkan daripada template `letter.for-you-always.my.id` dengan tema elegan **Dusty Rose**, efek amplop terbuka, taburan kelopak bunga (*blooming flower transition*), efek menaip (*typewriter*), muzik latar (*background song*), serta butang simpan surat (*screenshot memory*).

---

### 💖 Kandungan Surat
- **Penerima:** Ain (`Dearest Ain,`)
- **Pengirim:** daripada syafizam
- **Tajuk:** Surat Minta Maaf
- **Mesej:**
  > *"aku minta maaf pasal kemarin tu, jujur cakap aku tiada niat pun nak marah ke apa, tapi kalau nampak macam marah ke kasar ke, aku minta maaf sangat-sangat.*
  >
  > *aku minta maaf kalau terkasar bahasa, buat kau kecewa, sedih, aku minta maaf sangat-sangat."*
- **Lagu Latar:** *She & Him - I Thought I Saw Your Face Today* (tersimpan secara offline di `assets/music.mp3` dan bersedia dengan fallback online).

---

### 🚀 Cara Buka & Uji di Komputer

1. **Buka Terus di Browser:**
   - Cukup klik dua kali (double click) fail `index.html` untuk buka di Chrome / Edge / Safari.

2. **Gunakan Local Server (Pilihan Terbaik):**
   - Jalankan arahan di terminal:
     ```bash
     python -m http.server 8080
     ```
   - Kemudian buka di browser: `http://localhost:8080`

---

### 🌐 Cara Hantar Link Kepada Ain (Online / Hosting Percuma)

Jika anda ingin Ain dapat buka melalui telefon pintar (WhatsApp / Instagram / Telegram):

1. **Vercel (Paling Mudah & Pantas):**
   - Pergi ke [vercel.com](https://vercel.com)
   - Drag & drop folder `I am sorry` ini terus ke dashboard Vercel, atau guna arahan `npx vercel`.
   - Anda akan dapat link percuma seperti `surat-untuk-ain.vercel.app`!

2. **Netlify Drop:**
   - Pergi ke [app.netlify.com/drop](https://app.netlify.com/drop)
   - Drag & drop keseluruhan folder `I am sorry`.
   - Web akan live serta-merta dengan link percuma!

3. **GitHub Pages:**
   - Upload semua fail ke repository GitHub baru dan aktifkan GitHub Pages di bahagian *Settings -> Pages*.

---

### 🛠️ Cara Tukar Mesej, Lagu atau Gambar
Buka fail [`config.js`](./config.js):
- **Tukar Mesej / Ayat:** Ubah nilai pada `message` dan `letter_body`.
- **Tukar Lagu:** Letakkan fail mp3 baru dalam folder `assets/` dan kemaskini nama fail pada `playlist`.
- **Tambah Gambar Rahasia (Polaroid):** Masukkan URL gambar ke dalam `secretMediaList` jika ingin menambah kenangan gambar bersama Ain di akhir surat.
