# myportofolio_mobile

A Flutter project to show off my portofolio, for PBP course.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Tugas 7

1. Widget tree adalah struktur hierarki berbentuk pohon yang menggambarkan susunan seluruh elemen UI dalam Flutter. Di Flutter, hampir semua elemen, seperti teks, tombol, gambar, hingga tata letak halaman adalah sebuah widget. Widget tree berfungsi sebagai template yang dibaca oleh sistem untuk menggambar tampilan di layar. Sebuah widget induk membungkus widget anak di dalamnya melalui properti child jika hanya menampung satu widget, atau children jika menampung banyak widget sekaligus.

2. MyHomePage, InfoCard, ItemCard, MyApp
   - MyApp berfungsi untuk menampilkan aplikasi secara keseluruhan.
   - MyHomePage berfungsi untuk menampilkan menu aplikasi utama.
   - InfoCard berguna untuk menampung informasi nama, NPM, dan kelas.
   - ItemCard berguna untuk menampilkan teks "Kamu telah menekan tombol" yang disesuaikan dengan tombol yang ditekan dari ItemHomePage

3. MaterialApp adalah widget root utama yang menginisialisasi aplikasi dan membungkus seluruh komponen aplikasi dengan panduan Material Design. Ini berfungsi untuk mengatur tema, navigasi, dan konfigurasi global lainnya, serta memfasilitasi penggunaan widget Material.

4. Stateless Widget adalah widget yang dibangun hanya dengan konfigurasi yang telah diinisiasi sejak awal. Jadi, Stateless Widget adalah widget yang tidak akan pernah berubah. Stateful Widget adalah Widget yang dapat berubah dinamis. Gunakan stateless widget ketika tidak ada perubahan data internal atau tidak ada interaksi pengguna. Gunakan stateful widget ketika widget dapat berubah secara dinamis.

5. BuildContext adalah object khusus yang sudah disediakan oleh Flutter. BuildContext akan selalu membawa informasi meta tentang suatu widget yang akan diteruskan ke build widget selanjutnya. Informasi tersebut dapat digunakan oleh widget tree selanjutnya. Metode build menampilkan konteks dari BuildContext yang berisi informasi suatu widget.

6. Hot reload adalah fitur yang beruga untuk melihat perubahan kode secara instan tanpa perlu memulai ulang aplikasi. Hot restart adalah proses yang lebih menyeluruh dibandingkan dengan hot reload. Ketika melakukan hot restart, Flutter akan menghapus state aplikasi yang ada dan memulai aplikasi dari awal. Ini berarti semua variabel akan diinisialisasi ulang dan aplikasi akan kembali ke state awalnya. Hot reload sebaiknya digunakan ketika ada perubahan pada UI atau penambahan widget, sedangkan hot restart digunakan lebih dari itu, seperti perubahan state global atau modifikasi struktur aplikasi.