# Pemrograman Mobile

A new Flutter project.

## Praktikum 1

![Alt text](https://github.com/03Yuma/master_plan/blob/main/GIFT/Praktikum1.gif)

2. penjelasan langkah 4
   intruksi tersebut bertujuan untuk menyederhanakan proses impor
3. Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat     konstanta ?
   plan digunakan sebagai data utama yang dikelola dalam state widget, dan   
   penggunaan const pada inisialisasi membantu mengoptimalkan kinerja aplikasi dan      menjaga konsistensi nilai awal
5. Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?

   iniState digunakan untuk inisialisasi data atau setup awal ketika widget           pertama kali dibuat. Dalam kasus ini, scrollController diinisialisasi dan          listener ditambahkan untuk menangani perubahan fokus (misalnya, menghilangkan      fokus dari elemen input saat melakukan scroll).

   dispose digunakan untuk membersihkan atau melepaskan sumber daya ketika widget     sudah tidak digunakan lagi. Di sini, scrollController.dispose() memastikan         bahwa scrollController dibersihkan dan tidak menyebabkan kebocoran memori saat     widget dihapus dari widget tree.

## Praktikum 2
![Alt text](https://github.com/03Yuma/master_plan/blob/main/GIFT/Praktikum2.gif)

2. Penggunaan InheritedNotifier  agar dapat membagikan dan melacak perubahan data     Plan di seluruh aplikasi. Menggunakan InheritedNotifier memungkinkan aplikasi 
   untuk mendengarkan perubahan pada ValueNotifier tanpa perlu menggunakan solusi     pengelolaan state lain yang lebih rumit, seperti Provider atau Riverpod.
   
3. Penambahan completedCount berfungsi agar memudahkan untuk mengetahui berapa        banyak tugas yang telah selesai tanpa perlu menulis kode berulang.

   completenessMesaage menunjukkan berapa banyak tugas yang sudah selesai dari        total tugas

## Praktikum 3


