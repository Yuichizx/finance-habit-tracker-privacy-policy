# Privacy Policy

Terakhir diperbarui: 27 April 2026

Privacy Policy ini berlaku untuk aplikasi **Finance Habit Tracker** yang
dikembangkan oleh **Yuichizx** atau **IlhamVibeCode**.

Jika ada pertanyaan tentang Privacy Policy ini atau permintaan terkait data,
hubungi:

- Email: `ilhamvibe4@gmail.com`

## Ringkasan

Finance Habit Tracker membantu pengguna mencatat transaksi, kebiasaan finansial,
target tabungan, target pengeluaran, dan pengingat. Aplikasi dapat dipakai dalam
mode guest tanpa login. Login Google bersifat opsional dan hanya digunakan untuk
sinkronisasi serta pemulihan data cloud terenkripsi.

Aplikasi tidak menampilkan iklan dan tidak menjual data pengguna.

## Data yang Diproses

Finance Habit Tracker dapat memproses data berikut, tergantung fitur yang
digunakan:

- Data transaksi: nominal, kategori, sumber/akun, catatan opsional, tanggal,
  dan tipe transaksi.
- Data habit: nama habit, deskripsi, progres, target, jadwal pengingat, dan
  pesan pengingat opsional.
- Data target finansial: target tabungan, target pengeluaran, tanggal mulai,
  dan tanggal target.
- Data preferensi aplikasi: status onboarding, tutorial, tema tampilan, status
  banner, pengaturan rangkuman mingguan, dan installation ID lokal.
- Data akun Google, jika pengguna login: user ID Firebase, email, nama profil,
  dan foto profil yang disediakan oleh Firebase Authentication/Google Sign-In.
- Data dukungan/donasi, jika pengguna melakukan pembayaran via Google Play:
  ID produk, penyedia pembayaran, waktu event, installation ID, dan profile ID
  jika pengguna sedang login.
- Token atau subscription notifikasi, jika Firebase Cloud Messaging aktif untuk
  pengingat.

## Cara Data Digunakan

Data digunakan untuk:

- Menyimpan dan menampilkan catatan keuangan pengguna.
- Menghitung ringkasan pemasukan, pengeluaran, saldo, progres habit, laporan,
  dan target finansial.
- Menjalankan pengingat habit dan rangkuman mingguan.
- Menyinkronkan dan memulihkan data pengguna melalui cadangan cloud terenkripsi
  jika pengguna memilih login Google.
- Memproses dukungan/donasi melalui Google Play Billing.
- Mencatat event dukungan untuk kebutuhan administrasi dan analitik internal
  sederhana.
- Menjaga fungsi dasar aplikasi dan memperbaiki masalah teknis.

## Penyimpanan Lokal

Dalam mode guest, data utama disimpan di perangkat pengguna menggunakan
penyimpanan lokal aplikasi. Data lokal tidak dikirim ke server developer kecuali
pengguna login Google dan fitur sinkronisasi cloud aktif.

Data lokal dapat ikut terhapus jika pengguna menghapus aplikasi, membersihkan
data aplikasi dari pengaturan perangkat, atau keluar dari Google sesuai alur
aplikasi yang mengosongkan data lokal guest setelah backup berhasil.

## Sinkronisasi Cloud Opsional

Jika pengguna login Google, Finance Habit Tracker dapat menyimpan cadangan data
ke Firebase Firestore di path akun pengguna. Cadangan ini dienkripsi sebelum
disimpan ke cloud.

Data cloud digunakan untuk:

- Mencadangkan data dari perangkat.
- Memulihkan data ke perangkat yang sama atau perangkat lain.
- Menjaga data tetap tersedia saat pengguna login kembali dengan akun Google
  yang sama.

Login Google bersifat opsional. Fitur utama aplikasi tetap dapat digunakan tanpa
login.

## Google Play Billing

Dukungan/donasi diproses melalui Google Play Billing sebagai produk in-app
consumable. Informasi pembayaran diproses oleh Google Play. Finance Habit
Tracker tidak menerima atau menyimpan nomor kartu, rekening bank, atau detail
metode pembayaran pengguna.

Aplikasi hanya mencatat event dukungan seperti product ID dan waktu event untuk
kebutuhan administrasi dan analitik internal sederhana.

## Notifikasi

Aplikasi dapat meminta izin notifikasi untuk:

- Pengingat habit harian.
- Rangkuman mingguan.
- Reminder cloud jika Firebase Cloud Messaging aktif.

Pengguna dapat menolak izin notifikasi atau mengubah pengaturan notifikasi dari
pengaturan perangkat.

## Pihak Ketiga

Finance Habit Tracker menggunakan layanan pihak ketiga berikut:

- Google Firebase Authentication untuk login Google.
- Google Firebase Firestore untuk cadangan cloud terenkripsi dan event dukungan.
- Google Firebase Cloud Messaging untuk fitur reminder cloud.
- Google Play Billing untuk pembayaran dukungan/donasi.

Layanan pihak ketiga tersebut dapat memproses data sesuai kebijakan privasi dan
persyaratan masing-masing layanan Google.

## Pembagian Data

Finance Habit Tracker tidak menjual data pengguna.

Data dapat dibagikan atau diproses oleh layanan Google yang digunakan aplikasi,
seperti Firebase dan Google Play, hanya untuk menjalankan fitur yang dijelaskan
dalam Privacy Policy ini.

Developer dapat mengungkapkan data jika diwajibkan oleh hukum, perintah
pengadilan, atau permintaan sah dari otoritas yang berwenang.

## Keamanan Data

Finance Habit Tracker menerapkan langkah keamanan berikut:

- Data backup cloud dienkripsi sebelum disimpan ke Firestore.
- Akses Firestore dibatasi berdasarkan user ID Firebase melalui Firestore
  Security Rules.
- Login Google dikelola melalui Firebase Authentication.
- Detail pembayaran diproses oleh Google Play Billing, bukan oleh aplikasi.

Tidak ada metode penyimpanan atau transmisi data yang sepenuhnya bebas risiko.
Namun, aplikasi dirancang untuk membatasi akses data hanya pada kebutuhan fitur.

## Retensi dan Penghapusan Data

Data lokal disimpan selama aplikasi terpasang atau sampai pengguna menghapus
data aplikasi dari perangkat.

Data cloud disimpan selama akun Google pengguna masih memiliki cadangan cloud di
Firebase. Pengguna dapat meminta penghapusan data cloud dengan menghubungi email
kontak developer di atas.

Permintaan penghapusan data akan diproses secara wajar setelah developer dapat
memverifikasi akun atau identitas data yang diminta untuk dihapus.

## Hak Pengguna

Pengguna dapat:

- Menggunakan aplikasi tanpa login Google.
- Menghapus data lokal dengan menghapus data aplikasi dari pengaturan perangkat
  atau menghapus aplikasi.
- Meminta penghapusan data cloud dengan menghubungi developer.
- Mengikuti instruksi penghapusan akun/data di `docs/account_deletion.md`.
- Mengubah atau menolak izin notifikasi melalui pengaturan perangkat.
- Keluar dari Google melalui menu Profile di aplikasi.

## Anak-Anak

Finance Habit Tracker tidak ditujukan khusus untuk anak-anak. Aplikasi tidak
dengan sengaja mengumpulkan data pribadi anak-anak. Jika orang tua atau wali
mengetahui bahwa anak memberikan data pribadi melalui aplikasi ini, hubungi
developer agar data tersebut dapat ditinjau dan dihapus jika diperlukan.

## Perubahan Privacy Policy

Privacy Policy ini dapat diperbarui dari waktu ke waktu untuk menyesuaikan
fitur aplikasi, perubahan layanan pihak ketiga, atau persyaratan hukum dan
platform. Versi terbaru akan ditampilkan pada halaman Privacy Policy yang
dipublikasikan.
