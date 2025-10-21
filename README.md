# LAPORAN PRAKTIKUM APLIKASI OCR
## LANGKAH KERJA
### Langkah 1: Buat Proyek Baru
  ![create_project](images/00.png)
### Langkah 2: Tambahkan Plugin
  ![add_plugin](images/01.png)
### Langkah 3: Tambahkan Izin Kamera (Android)
  ![permission](images/02.png)
### Langkah 4: Buat Struktur Folder
  ![folder_structure](images/03.png)

## KODE PROGRAM
### File: lib/main.dart
  ![main_dart](images/04.png)
### File: lib/screens/splash_screen.dart
  ![splash_screen](images/05.png)
### File: lib/screens/home_screen.dart
  ![home_screen](images/06.png)
### File: lib/screens/scan_screen.dart
  ![scan_screen](images/07.png)
  ![scan_screen](images/08.png)
### File: lib/screens/result_screen.dart
  ![result_screen](images/09.png)

## TUGAS PRAKTIKUM
### Jalankan Aplikasi Pada Emulator atau Device
  ![run_app](images/10.gif)

## Pertanyaan
### a. Apakah semua teks terbaca dengan akurat? Mengapa?
- Ya, teks terbaca dengan sangat akurat. Hasil OCR berhasil mengenali hampir semua kata dengan benar. Alasan teks dapat terbaca dengan akurat karena: 1. Teks tulisan cukup rapi dan konsisten; 2. Foto diambil dengan pencahayaan yang cukup terang; 3. Resolusi gambar cukup tajam untuk diproses

### b. Apa kegunaan fitur OCR dalam kehidupan sehari-hari?
- Membantu mengubah dokumen kertas (misalnya surat, kwitansi atau dokumen arsip) menjadi file teks digital.
- Dapat menyalin teks dari foto, papan pengumuman, buku, dll.
- Memudahkan penerjemahan teks dari gambar atau foto bahasa asing.

### c. Sebutkan 2 contoh aplikasi nyata yang menggunakan OCR!
- Google Lens (Dapat scan dan terjemahkan teks secara real-time)
- CamScanner / Microsoft Office Lens (Scan dokumen fisik menjadi PDF digital)