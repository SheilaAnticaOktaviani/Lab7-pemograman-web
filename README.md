# Lab7-pemograman-web
# Nama: Sheila Antica Oktaviani
# kelas: TI.24.A1
# NIM: 312410002

# Latihan PHP Dasar

Proyek ini berisi dua file latihan yang digunakan untuk mempelajari dasar pemrograman PHP.  
File pertama (`php_dasar.php`) membahas sintaks dasar seperti variabel, operator, dan fungsi output.  
File kedua (`latihan2.php`) berisi latihan lanjutan seperti penggunaan kondisi, perulangan, dan fungsi sederhana.

---

## Struktur File

| Nama File | Deskripsi |
|------------|------------|
| `php_dasar.php` | Berisi contoh dasar PHP seperti variabel, operator aritmatika, dan perintah `echo`. |
| `latihan2.php` | Berisi latihan lanjutan yang menggunakan `if`, `else`, `for`, `while`, dan fungsi sederhana. |

---

## Penjelasan Kode

### 1. **File: php_dasar.php**

File ini menjelaskan konsep dasar bahasa PHP, meliputi:

- **Pembukaan PHP** menggunakan `<?php ... ?>`
- **Menampilkan teks** menggunakan `echo`
- **Deklarasi variabel**, misalnya:
  ```php
  $nama = "Sheila";
  $umur = 20;
  echo "Nama saya $nama dan umur saya $umur tahun.";

# latihan2.php

File ini berisi latihan lanjutan yang menekankan pada logika pemrograman. Fitur utama yang biasanya terdapat dalam file ini antara lain: Kondisi / Percabangan

if ($nilai >= 75) {
    echo "Lulus";
} else {
    echo "Tidak Lulus";
}
Perulangan

for ($i = 1; $i <= 5; $i++) {
    echo "Perulangan ke-$i <br>";
}

Array dan Looping

$buah = ["Apel", "Jeruk", "Mangga"];
foreach ($buah as $b) {
    echo "$b <br>";
}
Fungsi Sederhana

function salam($nama) {
    return "Selamat datang, $nama!";
}
echo salam("Sheila");
# Tujuan:
Melatih penggunaan logika (kondisi & looping) dan pengenalan konsep fungsi dalam PHP.
# Cara Menjalankan
Install XAMPP atau Laragon.
Simpan file ke direktori:
C:\xampp\htdocs\latihan_php\
Jalankan Apache dari XAMPP Control Panel.
Buka browser dan ketik alamat:
http://localhost/latihan_php/php_dasar.php
atau
http://localhost/latihan_php/latihan2.php

# HASIL WEB LATIHAN2_PHP
![Hasil_latihan2_php](https://github.com/user-attachments/assets/0ee77a95-2c16-406f-ac10-2a126febf5de)

# HASIL WEB PHP_DASAR_PHP
![Hasil php_dasar_php](https://github.com/user-attachments/assets/b58e651f-3acd-437b-98b7-53976a56ccf1)



