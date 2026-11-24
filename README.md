# THE BIRTHDAY — A Moment Made for You

## Lokal
Node.js 20+. Jalankan `ADMIN_PASSWORD='password-kuat' npm start` (Linux/macOS). Windows PowerShell: `$env:ADMIN_PASSWORD='password-kuat'; npm start`. Buka http://localhost:3000/admin.

## Render
1. Ekstrak ZIP dan unggah isi folder ke repository GitHub private.
2. Render Dashboard > New > Blueprint, pilih repository dan render.yaml.
3. Isi ADMIN_PASSWORD dengan password panjang dan unik. Blueprint menggunakan layanan berbayar dengan persistent disk; periksa biaya sebelum konfirmasi.
4. Setelah deploy, buka URL layanan + /admin. Buat ucapan, simpan, preview, salin link atau bagikan WA.

Data disimpan dalam cards.json pada persistent disk. Jangan menggunakan hosting filesystem sementara untuk data produksi. Backup file secara berkala. Gunakan HTTPS. Link penerima tidak memerlukan login; siapa pun yang memiliki link dapat melihat foto dan pesan. Jangan unggah informasi sensitif tanpa izin. Satu admin, satu instance server; belum ada rate limiting, multi-admin, guest book, mini games, video, atau mikrofon. Lilin ditiup melalui sentuhan. Musik opsional dari file yang Anda punya hak gunakan. Jangan commit folder data atau password.
