\# DebTracker

DebTracker adalah aplikasi manajemen utang sederhana yang memungkinkan Anda untuk melacak utang dan hutang dengan teman-teman Anda. Aplikasi ini memungkinkan Anda untuk menambahkan teman, memasukkan transaksi, dan mengelola status utang Anda.

\## Fitur

- \*\*Daftar Teman:\*\* Tampilkan daftar teman Anda dan lihat informasi kontak mereka.

- \*\*Transaksi:\*\* Tambahkan transaksi untuk setiap teman, termasuk keterangan, jumlah utang, dan status (lunas, utang, atau dibayar).

- \*\*Pemberitahuan:\*\* Terima pemberitahuan tentang permintaan pertemanan dan permintaan pembayaran utang.

- \*\*Manajemen Utang:\*\* Lacak utang Anda dengan teman-teman Anda dan tampilkan riwayat transaksi.

\## Penggunaan

Anda dapat mengakses DebTracker melalui \[https://debtracker.vercel.app\](https://debtracker.vercel.app).

\## Panduan Pengembangan

1. \*\*Persiapan Lingkungan:\*\*

   Pastikan Anda memiliki Node.js dan npm terinstal di komputer Anda. Jika belum, Anda dapat mengunduhnya dari \[Node.js website\](https://nodejs.org/).

2. \*\*Clone Repositori:\*\*

   Clone repositori ini ke komputer Anda:

   \```bash
   git clone https://github.com/your-username/debtracker.git
   \```

3. \*\*Install Dependencies:\*\*

   Masuk ke direktori proyek dan instal dependensi:

   \```bash
   cd debtracker
   npm install
   \```

4. \*\*Menjalankan Aplikasi:\*\*

   Jalankan aplikasi dalam mode pengembangan:

   \```bash
   npm run dev
   \```

   Aplikasi akan tersedia di \[http://localhost:3000\](http://localhost:3000). Anda dapat mulai mengembangkan dan menyesuaikan aplikasi sesuai kebutuhan Anda.

5. \*\*Menggunakan Supabase:\*\*

   DebTracker menggunakan Supabase sebagai backend untuk menyimpan data. Pastikan Anda memiliki akun Supabase dan konfigurasi API key yang sesuai. Ubah konfigurasi API key Supabase Anda dalam berkas .env:

   \```
   SUPABASE_URL=YOUR_SUPABASE_URL
   SUPABASE_KEY=YOUR_SUPABASE_KEY
   \```

6. \*\*Mengganti Informasi Proyek:\*\*

   Ubah informasi proyek dalam berkas package.json, termasuk nama, deskripsi, dan lainnya sesuai dengan proyek Anda.

\## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, Anda dapat mengirimkan pull request. Pastikan untuk mengikuti panduan kontribusi yang ada.

\## Lisensi

Proyek ini dilisensikan di bawah \[MIT License\](LICENSE).
