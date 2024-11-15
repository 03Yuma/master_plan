# master_plan

A new Flutter project.

## Praktikum 1

1. gift
2. penjelasan langkah 4
   intruksi tersebut bertujuan untuk menyederhanakan proses impor
3. Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat     konstanta ?
   plan digunakan sebagai data utama yang dikelola dalam state widget, dan   
   penggunaan const pada inisialisasi membantu mengoptimalkan kinerja aplikasi dan      menjaga konsistensi nilai awal
4. gift
5. Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?

   iniState digunakan untuk inisialisasi data atau setup awal ketika widget           pertama kali dibuat. Dalam kasus ini, scrollController diinisialisasi dan          listener ditambahkan untuk menangani perubahan fokus (misalnya, menghilangkan      fokus dari elemen input saat melakukan scroll).

   dispose digunakan untuk membersihkan atau melepaskan sumber daya ketika widget     sudah tidak digunakan lagi. Di sini, scrollController.dispose() memastikan         bahwa scrollController dibersihkan dan tidak menyebabkan kebocoran memori saat     widget dihapus dari widget tree.
