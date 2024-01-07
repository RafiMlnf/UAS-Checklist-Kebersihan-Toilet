# UAS - Sistem Checklist Kebersihan Toilet (Kelompok 8)

```
Mata Kuliah : Pemrograman Web
Dosen       : Agung Nugroho, S.Kom., M.KOM
```

```
Anggota Kelompok

312210382 - Rafi Maulana Firdaus 
312210405 - Rizjky Dito Ridwansyah 
312210279 - Ricky Alfian
```
----------------

## Sistem Checklist Kebersihan Toilet
Sistem Checklist Kebersihan Toilet adalah aplikasi web yang dirancang untuk membantu pengelola gedung atau fasilitas memonitor dan mengelola kebersihan toilet. Dengan menggunakan PHP sebagai bahasa pemrograman utama dan database MySQL untuk menyimpan data, sistem ini memberikan cara yang efisien untuk melakukan penilaian dan pelaporan kebersihan toilet.

## Fitur Utama
1. Login/Daftar:
    - Sistem membedakan antara admin dan petugas kebersihan.
2. Dashboard:
    - Menampilkan ringkasan status kebersihan toilet.
3. Manajemen Toilet:
    - Menambahkan, mengedit, dan menghapus informasi toilet.
    - Setiap toilet memiliki daftar item kebersihan yang dapat dicentang.
4. Checklist Kebersihan:
    - Setiap petugas dapat melakukan checklist pada setiap toilet yang ditangani.
    - Checklist mencakup item-item: kebersihan lantai, dinding, kloset, wastafel, kaca, bau ruangan, dan stok sabun
    - Sistem mencatat tanggal dan waktu checklist dilakukan.
5. Pelaporan:
    - Pengguna dapat sortir laporan berdasarkan tanggal.
    - Pengguna dapat sortir laporan berdasarkan rusak/kotor
    - Laporan diunduh dalam format PDF.

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
- Memberikan konfirmasi sebelum menghapus data toilet.

### 2. Transaksi Checklist

#### a. Daftar Toilet
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





