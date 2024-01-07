![header](https://github.com/RafiMlnf/UAS-Checklist-Kebersihan-Toilet/assets/115614668/1faea710-764e-4926-b481-2e0568465dac)
# UAS - Sistem Checklist Kebersihan Toilet (Kelompok 8)

```
Mata Kuliah : Pemrograman Web
Dosen       : Agung Nugroho, S.Kom., M.KOM
```

```
Anggota Kelompok

312210382 - Rafi Maulana Firdaus 
312210405 - Rizjky Dito Ridwansyah 
312210279 - Ricky Alfian Saputra
```
----------------

## Sistem Checklist Kebersihan Toilet
Sistem Checklist Kebersihan Toilet adalah aplikasi web yang dirancang untuk membantu pengelola gedung atau fasilitas memonitor dan mengelola kebersihan toilet. Dengan menggunakan PHP sebagai bahasa pemrograman utama dan database MySQL untuk menyimpan data, sistem ini memberikan cara yang efisien untuk melakukan penilaian dan pelaporan kebersihan toilet.

## Fitur Utama
1. `Login/Daftar:`
Sistem ini menyediakan fungsi login dan pendaftaran dengan perbedaan peran antara admin dan petugas kebersihan. Admin dan petugas memiliki akses yang berbeda sesuai dengan tugas dan tanggung jawab masing-masing.

2. `Dashboard:`
Dashboard utama menyajikan ringkasan status kebersihan toilet. Informasi yang ditampilkan mencakup parameter-parameter kunci untuk memberikan gambaran cepat mengenai kondisi kebersihan secara umum.

3. `Manajemen Toilet:`
Fasilitas manajemen toilet memungkinkan pengguna untuk menambahkan, mengedit, dan menghapus informasi toilet. Setiap toilet dilengkapi dengan daftar item kebersihan yang dapat dicentang, memberikan fleksibilitas dalam mengelola persyaratan kebersihan.

4. `Checklist Kebersihan:`
Petugas kebersihan dapat melakukan checklist pada setiap toilet yang menjadi tanggung jawabnya. Checklist mencakup item-item seperti kebersihan lantai, dinding, kloset, wastafel, kaca, bau ruangan, dan stok sabun. Sistem mencatat tanggal dan waktu ketika checklist dilakukan, memberikan transparansi terhadap aktivitas kebersihan.

5. `Pelaporan:`
Fasilitas pelaporan memungkinkan pengguna untuk menyortir laporan berdasarkan tanggal atau kondisi rusak/kotor. Laporan dapat diunduh dalam format PDF, memberikan kemudahan akses dan dokumentasi untuk pemantauan dan evaluasi kebersihan toilet.

## Implementasi Tambahan
### 1. Mengelola Data Toilet (CRUD)
#### a. Daftar Toilet
- Halaman ini menampilkan daftar toilet yang sudah terdaftar di sistem.
- Menyajikan informasi seperti nama toilet, lokasi, dan opsi untuk mengedit atau menghapus.
#### b. Tambah Data Toilet
- Form untuk menambahkan informasi toilet baru ke dalam database.
- Memasukkan data seperti nama toilet, lokasi, dan item kebersihan awal.
#### c. Ubah Data Toilet
- Form untuk mengubah informasi toilet yang sudah ada.
- Memungkinkan pengguna mengedit nama toilet, lokasi, atau item kebersihan.
#### d. Hapus Data Toilet
- Memungkinkan pengguna untuk menghapus toilet dari database.

### 2. Transaksi Checklist
a. Daftar Toilet  
- Halaman ini menampilkan daftar toilet yang tersedia.  
- Memberikan opsi untuk memilih toilet sebelum melakukan checklist.
#### b. Checklist berdasarkan Tanggal dan Pengguna
- Form checklist yang memungkinkan pengguna memilih toilet, memasukkan tanggal, dan memilih item kebersihan.
- Setiap transaksi checklist tercatat dengan mencatat tanggal dan pengguna yang melakukan checklist.

### 3. Laporan

#### a. Tampilkan Daftar Checklist per Tanggal
- Halaman laporan yang menampilkan daftar checklist berdasarkan tanggal yang dipilih.
- Menampilkan informasi seperti nama toilet, item kebersihan, dan status.
#### b. Tampilkan Daftar yang Belum Diperiksa per Tanggal
- Menampilkan daftar checklist yang belum diperiksa oleh pihak yang berwenang.
- Memberikan opsi untuk pemeriksaan lebih lanjut atau verifikasi.
#### c. Tampilkan Daftar Toilet yang Rusak/Kotor
- Laporan yang menampilkan daftar toilet yang dinilai sebagai rusak atau kotor.
- Memberikan informasi tambahan tentang item kebersihan yang memerlukan perhatian lebih.

Sistem Checklist Toilet ini adalah sebuah solusi untuk me-manage kebersihan toilet. Dengan fitur login, manajemen toilet, checklist kebersihan, dan pelaporan, sistem ini memberikan pengguna kemudahan dalam mengelola, memonitor, dan melaporkan kondisi kebersihan toilet secara efisien.

## <img src="img/youtube.png" width=20> Link Youtube penjelasan  
https://youtu.be/gFzq38aTG-k

## <img src="img/google-drive.png" width=20> Link Laporan Proyek
https://drive.google.com/file/d/11iFd2PZtbjJp1MGF3SsYYPsWyNcY4dDA/view?usp=sharing

## <img src="img/web.png" width=20> URL Web
https://k8toiletchecklistuas.000webhostapp.com







