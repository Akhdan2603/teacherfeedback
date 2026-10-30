Feedback Generator (PWA, offline)

Isi folder: index.html (aplikasi + 270 template), sw.js (offline), manifest.webmanifest, icon-192.png, icon-512.png.

Cara pasang:
1. Netlify: buka app.netlify.com/drop, lalu seret folder ini ke halaman itu. Selesai, dapat URL https.
   (Vercel/GitHub Pages juga bisa, cukup hosting semua file di folder yang sama.)
2. Buka URL itu di HP sekali saat online.
3. Android Chrome: menu titik tiga > "Instal aplikasi" / "Tambahkan ke layar utama".
   iPhone Safari: Bagikan > "Tambah ke Layar Utama".
4. Setelah itu aplikasi jalan tanpa internet.

Mengubah data: edit index.html (variabel SAMPLE), lalu ubah angka versi di sw.js (feedback-gen-v2 -> v3) dan upload ulang.
PWA hanya bisa diinstal lewat https atau localhost, bukan dengan membuka file langsung (file://).
