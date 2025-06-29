# 🗂️ Perhitungan Zeller's Congruence 

## 🔍 Tentang Repository Ini

Selamat datang di **task repository** saya!  
Repository ini dibuat sebagai dokumentasi perjalanan belajar dan eksplorasi saya dalam dunia pemrograman. Di dalamnya terdapat kumpulan latihan coding dari program Eco Techno Leader. 

### 🧮 Langkah-Langkah Perhitungan Zeller's Congruence 
----
Zeller's Congruence adalah algoritma matematika yang dikembangkan oleh Christian Zeller pada abad ke-19 untuk menghitung hari dalam seminggu dari tanggal tertentu dalam kalender Julian atau Gregorian. Algoritma ini menggunakan aritmetika modular untuk menentukan hari yang sesuai dengan tanggal yang diberikan.
Rumus Zeller untuk Kalender Gregorian
Untuk kalender Gregorian, rumus Zeller adalah sebagai berikut:
![zeller rumus](https://github.com/Asfa-Asfialana/TASK-REPOSITORY/blob/main/zeller%20rumus.jpg)

#### 1. Penyesuaian Bulan dan Tahun:
![gambar1](https://github.com/Asfa-Asfialana/TASK-REPOSITORY/blob/main/gambar1.png)

Dalam Zeller's Congruence, bulan Januari dan Februari dianggap sebagai bulan ke-13 dan ke-14 dari tahun sebelumnya. Oleh karena itu, jika bulan adalah 1 (Januari) atau 2 (Februari), kita menambahkan 12 ke nilai bulan dan mengurangi 1 dari tahun.
#### 2. Menghitung Nilai K dan J:
![gambar2](https://github.com/Asfa-Asfialana/TASK-REPOSITORY/blob/main/gambar2.png)
K adalah dua digit terakhir dari tahun (tahun dalam abad tersebut).
J adalah dua digit pertama dari tahun (abad).
Misalnya, untuk tahun 1999:
K = 1999 % 100 = 99
J = 1999 // 100 = 19

#### 3. Menghitung Nilai h:
![gambar3](https://github.com/Asfa-Asfialana/TASK-REPOSITORY/blob/main/gambar3.png)

Rumus ini adalah implementasi dari Zeller's Congruence untuk kalender Gregorian.
tanggal adalah hari dalam bulan.
((13 * (bulan + 1)) // 5) menyesuaikan perbedaan jumlah hari dalam bulan.
K dan K // 4 memperhitungkan tahun dalam abad dan tahun kabisat.
J // 4 dan -2 * J menyesuaikan perbedaan antara abad.
% 7 memastikan hasil h berada dalam rentang 0 hingga 6, yang mewakili hari dalam seminggu.
#### 4. Menentukan Hari dalam Seminggu:
![gambar4](https://github.com/Asfa-Asfialana/TASK-REPOSITORY/blob/main/gambar4.png)

Nilai h yang diperoleh digunakan untuk menentukan hari dalam seminggu:
0: Sabtu
1: Minggu
2: Senin
3: Selasa
4: Rabu
5: Kamis
6: Jumat

Dengan program Python ini, kita tidak hanya belajar tentang konsep tahun kabisat dan algoritma Zeller's Congruence, tetapi juga memahami bagaimana matematika dapat diaplikasikan dalam kehidupan sehari-hari. Mengetahui hari apa kita lahir atau peristiwa penting lainnya bisa menjadi hal yang menyenangkan dan informatif.
Terima kasih telah mengunjungi repository ini!  
Semoga apa yang saya pelajari dan dokumentasikan di sini bisa berguna, tidak hanya bagi saya, tapi juga bagi siapa pun yang sedang belajar seperti saya. 🚀

> **“Learning to write programs stretches your mind, and helps you think better.” – Bill Gates**
