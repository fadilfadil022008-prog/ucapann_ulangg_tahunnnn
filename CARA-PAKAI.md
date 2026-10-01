# Cara Pakai Web Ucapan Ini

Kamu tidak perlu bisa coding untuk memakai ini. Ikuti saja langkah di bawah.

## 1. Isi File

Buka file `index.html` pakai VS Code (atau Notepad juga bisa). Cari 3 bagian ini
dengan `Ctrl+F` lalu ganti teksnya:

| Cari teks ini | Ganti dengan |
|---|---|
| `Alwaa` (di bagian `<h1 id="namaDia">`) | Nama panggilan orangnya |
| `Nama Kamu` (di bagian `<span id="namaPengirim">`) | Nama kamu |
| Teks di dalam `<p id="isiUcapan">...</p>` | Ucapanmu sendiri (hapus tulisan dalam kurung siku, ganti dengan kalimatmu) |

## 2. Masukkan Foto

1. Buka folder `foto` yang sudah disediakan di sebelah file `index.html`
2. Drag & drop foto-fotomu ke folder itu
3. **Ganti nama setiap file foto** jadi: `foto1.jpg`, `foto2.jpg`, `foto3.jpg`, dan seterusnya
   sampai `foto15.jpg` (atau sesuai jumlah foto kamu)
   - Kalau fotonya format `.png`, ganti juga bagian `.jpg` di file `index.html`
     pada baris `img.src = \`foto/foto${i}.jpg\`;` jadi `.png`
4. Kalau foto kamu kurang dari 15, itu tidak masalah — kotak yang belum terisi
   otomatis akan menampilkan tulisan "taruh foto di sini", jadi web tetap rapi

## 3. Cek Hasilnya di Komputer Sendiri

Klik dua kali file `index.html` — akan otomatis terbuka di browser. Cek apakah
foto dan teksnya sudah muncul dengan benar.

## 4. Upload ke GitHub Pages (biar bisa dibuka orang lain)

1. Buat akun GitHub di [github.com](https://github.com) kalau belum punya
2. Klik tombol **"New repository"** (repository baru)
3. Kasih nama terserah kamu, misal `ucapan-untuk-alwaa`, lalu klik **Create repository**
4. Di halaman repository yang baru dibuat, klik **"uploading an existing file"**
5. Drag & drop **seluruh isi folder** ini (file `index.html` dan folder `foto` beserta isinya)
6. Klik **Commit changes**
7. Setelah terupload, klik menu **Settings** (di repository itu) → cari bagian **Pages** di sidebar kiri
8. Di bagian **Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**
9. Tunggu 1-2 menit, lalu refresh halaman itu — akan muncul link seperti:
   `https://namakamu.github.io/ucapan-untuk-alwaa/`
10. Itu link publik yang sudah bisa dibuka siapa saja, dan bisa juga diubah jadi QR code
    lewat situs seperti [qr-code-generator.com](https://www.qr-code-generator.com/) —
    tinggal paste link-nya di sana

## Catatan

- Tanggal hitung mundur sudah diatur ke **2 Oktober 2026, jam 00:00**. Kalau mau ubah,
  buka `index.html`, cari baris `const targetDate`, dan sesuaikan angkanya
  (format: Tahun, Bulan dikurangi 1, Tanggal, Jam, Menit)
