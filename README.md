# hello_world
# Jobsheet 05 | Aplikasi Pertama dan Widget Dasar Flutter

## **Nama      : Yayun Eldina**
## **NIM     : 2241720065**
## **Kelas     : TI-3F**

---
# **Praktikum 1 : Membuat Project Flutter Baru**
## **Langkah 1**
Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.

 ![Screenshot hello_word](images/s1.png)

 ![Screenshot hello_word](images/s2.png)

## **Langkah 2**
Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

![Screenshot hello_word](images/s2,.png)

## **Langkah 3**
Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.

![Screenshot hello_word](images/s3.png)

## **Langkah 4**
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.

![Screenshot hello_word](images/s4.png)

# **Praktikum 2 : Menghubungkan Perangkat Android atau Emulator**
Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

**Menjalankan aplikasi di perangkat Android menggunakan Wi-Fi**

**Mulai**
1. Pastikan komputer dan perangkat Anda terhubung ke jaringan nirkabel yang sama.
2. Pastikan perangkat Anda menjalankan Android 11 atau yang lebih baru. Untuk informasi selengkapnya, lihat Memeriksa & mengupdate versi Android.
3. Pastikan komputer Anda telah memiliki Android Studio versi terbaru. Untuk mendownloadnya, lihat Android Studio.
4. Pastikan komputer Anda memiliki SDK Platform Tools versi terbaru.

**Menyambungkan perangkat Anda**
1. Di Android Studio, pilih Pair Devices Using Wi-Fi dari menu drop-down konfigurasi run.

![Screenshot hello_word](images/d1.png)

Dialog Pair devices over Wi-Fi akan terbuka.

![Screenshot hello_word](images/d1,.png)

2. Buka Developer options, scroll ke bawah ke bagian Debugging, lalu aktifkan Wireless debugging.

![Screenshot hello_word](images/d2.jpg)

3. Pada pop-up Izinkan proses debug nirkabel di jaringan ini?, pilih Allow

![Screenshot hello_word](images/d3.jpg)

4. Jika Anda ingin menyambungkan perangkat dengan kode QR, pilih Pair device with QR code, lalu pindai kode QR di komputer Anda. Atau, jika Anda ingin menyambungkan perangkat dengan kode penghubung, pilih Pair device with pairing code, lalu masukkan 6 digit kode.

![Screenshot hello_word](images/d4.png)

5. Klik jalankan dan Anda dapat men-deploy aplikasi ke perangkat.

![Screenshot hello_word](images/d5.jpg)

# **Praktikum 3 : Membuat Repository GitHub dan Laporan Praktikum**
## **Langkah 1**
Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"


## **Langkah 2**
Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.

![Screenshot hello_word](images/t1.png)

## **Langkah 3**
Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

![Screenshot hello_word](images/t3.png)

## **Langkah 4**
Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.

![Screenshot hello_word](images/t4.png)

## **Langkah 5**
Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

![Screenshot hello_word](images/t5.png)

## **Langkah 6**
Lakukan push dengan klik bagian menu titik tiga > Push

![Screenshot hello_word](images/t6.png)

## **Langkah 7**
Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"

![Screenshot hello_word](images/t6,.png)

## **Langkah 8**
Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

![Screenshot hello_word](images/t7.png)

Setelah berhasil, tulis remote name dengan "origin"

![Screenshot hello_word](images/t8,.png)

## **Langkah 9**
Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

![Screenshot hello_word](images/t9.png)

## **Langkah 10**
Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

![Screenshot hello_word](images/t10.png)

## **Langkah 11**
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

A new Flutter project.

![Screenshot hello_word](images/t11.png)

![Screenshot hello_word](images/02.jpg)

## **Langkah 12**
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

![Screenshot hello_word](images/T12.png)


# **Praktikum 4 : Menerapkan Widget Dasar**
## **Langkah 1 : Text Widget**
* Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.

![Screenshot hello_word](images/e1.png)


* Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.

![Screenshot hello_word](images/e1,.png)

![Screenshot hello_word](images/e1...jpg)

## **Langkah 2 : Image Widget**
* Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.

![Screenshot hello_word](images/e2.png)

* Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.

![Screenshot hello_word](images/e2,.png)

* Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

![Screenshot hello_word](images/e2..png)

![Screenshot hello_word](images/e2hasil.jpg)

# **Praktikum 5 : Menerapkan Widget Material Design dan iOS Cupertino**
## **Langkah 1 : Cupertino Button dan Loading Bar**
Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Screenshot hello_word](images/l1.png)

![Screenshot hello_word](images/l1..jpg)

## **Langkah 2 : Floating Action Button (FAB)**
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Screenshot hello_word](images/l2.png)

![Screenshot hello_word](images/l2..jpg)

## **Langkah 3 : Scaffold Widget**
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut.

![Screenshot hello_word](images/l3.png)

![Screenshot hello_word](images/l3,.png)

![Screenshot hello_word](images/l3..jpg)

## **Langkah 4 : Dialog Widget**
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.

![Screenshot hello_word](images/l4.png)

![Screenshot hello_word](images/l4,.png)

![Screenshot hello_word](images/l4..jpg)

## **Langkah 5 : Input dan Selection Widget**
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:

![Screenshot hello_word](images/l5.png)

![Screenshot hello_word](images/l5..jpg)

## **Langkah 6 : Date and Time Pickers**
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

![Screenshot hello_word](images/l6.png)

![Screenshot hello_word](images/l6,.png)

![Screenshot hello_word](images/l6.jpg)

![Screenshot hello_word](images/l6..jpg)
