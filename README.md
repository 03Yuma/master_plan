# Jobsheet 10

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
![Alt text](https://github.com/03Yuma/master_plan/blob/main/GIFT/Praktikum3.gif)

Gambar Diagram
![Alt text](https://github.com/03Yuma/master_plan/blob/main/GIFT/P3_SS.png)

Diagram menunjukkan proses aplikasi berpindah dari satu layar ke layar lainnya.
Layar pertama, yaitu PlanCreatorScreen, menyediakan input untuk memasukkan data serta menampilkan daftar yang bisa di-scroll. Setelah pengguna menavigasi ke layar berikutnya menggunakan Navigator.push, mereka akan dibawa ke PlanScreen. Di layar ini, struktur tampilannya lebih lengkap karena menggunakan Scaffold sebagai kerangka utama layar, dan dilengkapi dengan SafeArea untuk memastikan konten tidak tertutupi elemen UI sistem seperti notch atau status bar.

Struktur semacam ini sering digunakan di Flutter untuk membuat alur navigasi antar layar, terutama dalam aplikasi yang memiliki langkah-langkah atau proses yang saling berkaitan. Dengan menggunakan Navigator.push, pengguna dapat berpindah dari satu layar ke layar lainnya dengan lebih mulus, sehingga menciptakan pengalaman yang terstruktur dan teratur.





