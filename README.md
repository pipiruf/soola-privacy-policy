<!doctype html>
<html lang="id">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Kebijakan Privasi aplikasi Soola POS.">
    <title>Kebijakan Privasi Soola POS</title>
    <style>
      :root { color-scheme: light; font-family: system-ui, sans-serif; }
      body { color: #23332d; line-height: 1.65; margin: 0 auto; max-width: 900px; padding: 32px 20px 56px; }
      h1, h2 { line-height: 1.25; }
      h1 { font-size: 2rem; }
      h2 { font-size: 1.2rem; margin-top: 2rem; }
      .updated { color: #586860; }
    </style>
  </head>
  <body>
    <main>
      <h1>Kebijakan Privasi Soola POS</h1>
      <p class="updated">Terakhir diperbarui: 10 November 2026</p>
      <p>Soola POS adalah aplikasi point-of-sale lokal-first. Kebijakan ini menjelaskan data yang diproses aplikasi, kapan data dikirim ke pihak lain, dan pilihan Anda.</p>

      <h2>1. Data yang diproses</h2>
      <p>Soola POS menyimpan data usaha dan transaksi di penyimpanan privat perangkat. Data dapat mencakup nama dan profil usaha, produk, harga, stok, transaksi, metode dan jumlah pembayaran, nama pelanggan dan catatan jika Anda mengisinya, akun pengguna, PIN dalam bentuk hash, serta riwayat audit, ekspor, backup, dan restore.</p>
      <p>Aplikasi tidak mengirim data ini ke server milik pengembang dan tidak menjalankan analitik atau iklan.</p>

      <h2>2. Pengiriman data yang Anda pilih</h2>
      <p>Jika Anda mengaktifkan Google Sheets webhook, ringkasan transaksi—nomor dan waktu transaksi, unit usaha, nama kasir, metode pembayaran, total, uang diterima, kembalian, serta rincian item—dikirim melalui internet ke URL yang Anda masukkan. Penerima dan kebijakan retensi data tersebut ditentukan oleh Anda dan penyedia URL. Anda dapat menghapus URL webhook di Pengaturan. Nama pelanggan, catatan transaksi, dan PIN tidak disertakan dalam payload webhook.</p>
      <p>Fitur bagikan, ekspor, cetak, dan simpan file hanya berjalan saat Anda memilih tindakan tersebut. Data kemudian ditangani oleh aplikasi atau lokasi tujuan yang Anda pilih.</p>

      <h2>3. Penyimpanan dan backup</h2>
      <p>Database disimpan di penyimpanan privat aplikasi. Android Auto Backup dinonaktifkan; backup hanya dibuat secara manual melalui aplikasi. Jika Anda membagikan atau menyimpan file backup/ekspor, salinannya berada di lokasi atau layanan yang Anda pilih dan tunduk pada kebijakan layanan tersebut. Menghapus aplikasi atau data aplikasi akan menghapus data lokal yang belum Anda ekspor.</p>

      <h2>4. Keamanan</h2>
      <p>PIN disimpan sebagai hash PBKDF2-SHA256 dengan salt acak. Kontrol role membatasi akses melalui aplikasi. Database lokal tidak dienkripsi oleh aplikasi; keamanan data juga bergantung pada keamanan perangkat dan kunci layar Anda. Jangan membagikan PIN atau file backup kepada pihak yang tidak dipercaya.</p>

      <h2>5. Retensi dan kendali Anda</h2>
      <p>Data lokal tetap ada sampai Anda menghapusnya di aplikasi (jika fitur tersedia), menghapus data aplikasi, atau menghapus aplikasi. Anda dapat membuat dan menghapus backup, serta mengekspor atau membagikan data melalui fitur aplikasi. File yang telah disalin atau dibagikan harus dihapus dari tujuan tersebut secara terpisah.</p>

      <h2>6. Anak-anak dan perubahan kebijakan</h2>
      <p>Soola POS ditujukan untuk pengelolaan usaha, bukan untuk anak-anak. Kami tidak dengan sengaja mengumpulkan data anak-anak. Kebijakan ini dapat diperbarui; versi terbaru akan disediakan di halaman kebijakan publik dan di dalam aplikasi.</p>

      <h2>7. Kontak</h2>
      <p>Untuk pertanyaan privasi, hubungi <a href="mailto:f.triatmojo@outlook.co.id">f.triatmojo@outlook.co.id</a>.</p>
    </main>
  </body>
</html>
