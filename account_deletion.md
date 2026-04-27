# Account and Data Deletion

Halaman ini menjelaskan cara meminta penghapusan akun dan data terkait aplikasi
**Finance Habit Tracker**.

## Cara Meminta Penghapusan Data

Kirim email ke:

`ilhamvibe4@gmail.com`

Gunakan subjek:

`Finance Habit Tracker - Request Account/Data Deletion`

Sertakan informasi berikut di isi email:

- Nama aplikasi: Finance Habit Tracker
- Email akun Google yang digunakan untuk login di aplikasi
- Permintaan yang diinginkan:
  - hapus data cloud saja, atau
  - hapus data cloud dan data akun terkait aplikasi

Developer dapat meminta informasi tambahan untuk memverifikasi bahwa permintaan
berasal dari pemilik akun yang sah.

## Data yang Akan Dihapus

Jika permintaan valid, data berikut akan dihapus sejauh data tersebut tersedia
di sistem aplikasi:

- Cadangan cloud Finance Habit Tracker di Firebase Firestore.
- Data transaksi, habit, target tabungan, target pengeluaran, kategori custom,
  dan pengaturan aplikasi yang tersimpan di cloud.
- Event dukungan/donasi yang terhubung dengan profile ID akun, jika dapat
  diverifikasi dan ditemukan.
- Data akun aplikasi yang terkait dengan login Google/Firebase Authentication,
  jika penghapusan akun diminta.

## Data Lokal di Perangkat

Data lokal tersimpan di perangkat pengguna. Untuk menghapus data lokal:

1. Buka pengaturan perangkat.
2. Pilih aplikasi Finance Habit Tracker.
3. Pilih hapus data aplikasi, atau uninstall aplikasi.

Penghapusan data cloud oleh developer tidak otomatis menghapus data lokal yang
masih tersimpan di perangkat pengguna.

## Data yang Mungkin Tetap Disimpan

Beberapa data dapat tetap disimpan sementara jika diperlukan untuk:

- Kewajiban hukum.
- Keamanan, pencegahan penyalahgunaan, atau audit internal.
- Catatan transaksi pembayaran yang dikelola oleh Google Play.

Detail pembayaran seperti nomor kartu, rekening bank, atau metode pembayaran
tidak disimpan oleh Finance Habit Tracker. Data pembayaran diproses oleh Google
Play.

## Waktu Pemrosesan

Permintaan penghapusan data akan diproses dalam waktu wajar setelah verifikasi,
umumnya hingga 30 hari.

## Kontak

Untuk pertanyaan tentang penghapusan akun/data atau privacy policy, hubungi:

`[ISI_EMAIL_KONTAK_DEVELOPER]`
