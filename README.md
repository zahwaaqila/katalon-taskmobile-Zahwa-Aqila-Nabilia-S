# katalon-taskmobile-Zahwa-Aqila-Nabilia-S

```markdown
# Pengujian Mobile Menggunakan Appium

Repository ini berisi pengujian otomatis untuk aplikasi mobile menggunakan Appium. Pengujian mencakup dua kumpulan tes utama: `profile` dan `product`, masing-masing memiliki kasus uji spesifik.

## Prasyarat

1. Pastikan Anda telah menginstal Appium. Anda dapat mengikuti petunjuk di [situs web resmi Appium](http://appium.io/docs/en/about-appium/intro/) untuk instalasi.

2. Siapkan Android Studio untuk emulasi perangkat Android.

## Kumpulan Tes

### 1. Profile

#### Kasus Uji:

- **Profile - Nama (Ubah Nama):**
  - Deskripsi: Kasus uji ini memvalidasi kemampuan untuk mengubah nama pengguna di profil.
  - Langkah:
    1. Meluncurkan aplikasi.
    2. Navigasi ke bagian profil.
    3. Edit nama pengguna.
    4. Simpan perubahan.
    5. Verifikasi bahwa nama telah berhasil diperbarui.

- **Profile - Email (Ubah Email):**
  - Deskripsi: Kasus uji ini memvalidasi kemampuan untuk mengubah alamat email pengguna di profil.
  - Langkah:
    1. Meluncurkan aplikasi.
    2. Navigasi ke bagian profil.
    3. Edit alamat email pengguna.
    4. Simpan perubahan.
    5. Verifikasi bahwa email telah berhasil diperbarui.

### 2. Product

#### Kasus Uji:

- **Product - Search (Mencari Produk):**
  - Deskripsi: Kasus uji ini memastikan bahwa fungsi pencarian produk berfungsi seperti yang diharapkan.
  - Langkah:
    1. Meluncurkan aplikasi.
    2. Navigasi ke bagian pencarian produk.
    3. Masukkan kueri pencarian.
    4. Mulai pencarian.
    5. Verifikasi bahwa produk yang relevan ditampilkan.

## Perangkat yang Digunakan

- **Perangkat:** Emulator Android Studio
- **Versi:** [Spesifikasikan versi Android]

## Menjalankan Tes

1. Clone repository ini ke mesin lokal Anda.
2. Buka direktori proyek.
3. Instal dependensi yang diperlukan: `npm install` (asumsikan Anda sudah menginstal Node.js).
4. Jalankan tes:
   - Untuk seluruh kumpulan tes: `npm test`
   - Untuk kumpulan tes tertentu: `npm test -- --suite <nama_kumpulan_tes>`


