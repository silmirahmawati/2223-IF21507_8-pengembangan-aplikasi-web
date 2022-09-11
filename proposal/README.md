
# Proposal : Aplikasi buku tamu berbasis web

## Identitas Penulis
- Nama  : Silmi Rahmawati
- NIM   : 1207050120
- Kelas : Teknik Informatika-F

## Permasalahan
- mahasiswa sering mengantri untuk mengisi buku tamu depan fakultas, sehingga kurang efisien. 

## Rancangan Solusi
- Aplikasi Buku Tamu yang digunakan untuk mencatat pengunjung yang datang, serta melakukan manajemen data kunjungan tamu.

## Use Case
- Admin bisa login, mengelola data tamu.
- tamu bisa mengisi form dengan data :
    - Nama
    - NIM
    - Jurusan
    - Keperluan

## Struktur Data
### Admin
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|Integer|272|
|username|string|Heriyanto|
|password|string|HeriY12|

### Halaman
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|Integer|102|
|Total pengunjung |Integer|786|
|pengunjung Hari ini |Integer|98|

### User (Mahasiswa)
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|Integer|12|
|Nama |string |Silmi Rahmawati|
|NIM |Integer|1207050120|
|Jurusan |string|Teknik Informatika|
|Keperluan |string|ada kelas matkul Peng. App Web |
|Tanggal |date|10-09-2022 |

## UX Wireframe
![Buku Tamu Digital](https://user-images.githubusercontent.com/88075963/189527160-5cd35c49-b168-4323-a964-a1cbdc105f93.png)

