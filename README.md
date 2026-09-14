## Tujuan

Proyek ini bertujuan untuk mempelajari dasar-dasar pengembangan aplikasi
mobile menggunakan Flutter serta memahami proses pengelolaan source code
menggunakan Git dan GitHub.

## Rencana Fitur

1. Tampilan antarmuka aplikasi mobile.
2. Navigasi antarhalaman.
3. Pengelolaan dan penyajian data aplikasi.

## Cara Menjalankan

Sebelum menjalankan aplikasi, pastikan Flutter SDK sudah terpasang dan dikonfigurasi serta perangkat Android atau emulator sudah tersedia.
Seluruh perintah berikut harus dijalankan dari direktori utama (root) proyek Flutter, yaitu direktori yang berisi file pubspec.yaml.

1. Masuk ke direktori utama proyek
   Buka terminal dan arahkan ke direktori proyek Flutter.
   Contoh:
   cd path/ke/proyek
   Pastikan file pubspec.yaml terdapat pada direktori tersebut.

2. Mengambil dependency proyek
   Jalankan perintah berikut dari direktori utama proyek:
   flutter pub get
   Perintah ini digunakan untuk mengambil dan memasang dependency yang tercantum pada file pubspec.yaml.

3. Menjalankan aplikasi
   Setelah dependency berhasil diperoleh, jalankan:
   flutter run
   Perintah tersebut digunakan untuk menjalankan aplikasi pada perangkat atau emulator yang tersedia.

Catatan Setup
Jika Flutter atau emulator belum dikonfigurasi dengan benar, aplikasi belum dapat dijalankan sampai proses setup selesai.
Sebelum menjalankan aplikasi, konfigurasi dapat diperiksa menggunakan:
flutter doctor
Perintah tersebut membantu memeriksa apakah Flutter SDK, Android SDK, perangkat, dan komponen pendukung lainnya telah tersedia dengan benar.
