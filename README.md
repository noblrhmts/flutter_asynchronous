**NAMA: NOBEL RAHMAT SANI**

**KELAS: 2A TRPL**

**NIM: 362358302075**


1. Praktikum 1
   
   ![2](https://github.com/user-attachments/assets/e4863828-6ced-4f21-a170-46165e19d59d)

   Soal:
   
   Jelaskan maksud kode langkah 5 tersebut terkait substring dan catchError!?

   Jawab:
   
   Substring adalah sebuah metode yang berfungsi untuk mengambil sebagian dari nilai string. value.body merujuk pada isi (body) dari respons HTTP yang diterima, biasanya berupa teks atau data dalam format JSON. toString() digunakan untuk mengonversi body, yang mungkin berupa objek seperti JSON atau Map, menjadi sebuah string. Sementara itu, substring(0, 450) digunakan untuk mengekstrak bagian string yang dimulai dari indeks ke-0 hingga indeks ke-450.

2. Praktikum 2

   ![3](https://github.com/user-attachments/assets/0e88f574-1c51-4814-8ee8-01a73453a552)

   Soal:

   Jelaskan maksud kode langkah 1 dan 2 tersebut?

   Jawab:
   
   Langkah pertama adalah mendefinisikan tiga fungsi asynchron, yaitu returnOneAsync, returnTwoAsync, dan returnThreeAsync. Sedangkan di Langkah kedua, ketiga fungsi tersebut digabungkan ke dalam satu fungsi bernama count().

3. Praktikum 3

   ![4](https://github.com/user-attachments/assets/79fc6855-36e8-4c0c-bd0a-79ef5ddbf7a5)

   Soal:
   
   1. Jelaskan maksud kode langkah 2 tersebut!
      
   2. Jelaskan maksud perbedaan kode langkah 2 dengan langkah 5-6 tersebut!

   Jawab:

   1. Fungsi getNumber() menghasilkan sebuah Future yang akan terselesaikan setelah fungsi calculate() menyelesaikan prosesnya, yaitu mengembalikan nilai 42 setelah jeda selama 5 detik.
   
   2. Langkah kedua bertujuan hanya untuk menunggu dan menyelesaikan Future dengan hasil yang diberikan tanpa menangani kesalahan. Pada langkah 5-6, ditambahkan mekanisme penanganan error menggunakan try-catch dan completeError(), serta menangani kesalahan pada getNumber().then() menggunakan catchError().

4. Praktikum 4

   ![5](https://github.com/user-attachments/assets/74603812-91cd-4000-9ec9-8366cf1d3b60)

   Soal:
   
   Jelaskan maksud perbedaan kode langkah 1 dan 4!

   Jawab:

   FutureGroup memungkinkan pengelolaan beberapa Future secara dinamis, menambahkan satu per satu dan menutup grup setelah selesai. Sebaliknya, Future.wait() lebih sederhana, menerima daftar Future sekaligus dan menyelesaikannya bersama. FutureGroup cocok untuk skenario kompleks, sedangkan Future.wait() ideal untuk kasus sederhana tanpa perlu pengelolaan tambahan.

5. Praktikum 5

   ![6](https://github.com/user-attachments/assets/864750b6-ed11-47f5-a7be-eff56c7a1926)

   Soal:

   Jelaskan perbedaan kode langkah 1 dan 4?

   Jawab:

   - Langkah 1: Menggunakan returnError() dengan struktur try-catch-finally untuk menangani error sekaligus memastikan blok finally tetap dijalankan, terlepas dari apakah terjadi error atau tidak.
  
   - Langkah 4: ElevatedButton memanggil metode handleError() saat ditekan. Perbedaannya terletak pada penanganan antarmuka pengguna (UI), di mana setState() digunakan untuk memperbarui tampilan dengan hasil error yang ditangkap.

6. Praktikum 6

   ![7](https://github.com/user-attachments/assets/117959e2-b01a-42c0-a63d-77e604cae32a)

   Soal:

   Apakah Anda mendapatkan koordinat GPS ketika run di browser? Mengapa demikian?

   Jawab:

   Iya, saya dapat karena saya menggunakan future getPosition.

7. Praktikum 7

   ![8](https://github.com/user-attachments/assets/6445c7cf-af60-4ff5-badf-c065fde36a57)

   Soal:
   
   1. Apakah ada perbedaan UI dengan praktikum sebelumnya?
  
   2. Apakah ada perbedaan UI dengan langkah sebelumnya?
  
   Jawab:

   1. Perbedaan UI aplikasi browser dan mobile terletak pada akses hardware, responsivitas, dan interaksi. Mobile dioptimalkan untuk layar sentuh dan sensor seperti GPS, sedangkan browser lebih fokus pada mouse, keyboard, dan akses hardware terbatas.
  
   2. Perbedaan UI yang saya alami bisa disebabkan oleh akses hardware (GPS, sensor), responsivitas yang kurang optimal di browser, dan pengaturan izin yang berbeda antara perangkat mobile dan browser. Di mobile, UI lebih responsif dan akses sensor lebih langsung.
  
8. Praktikum 8

   ![9](https://github.com/user-attachments/assets/bdb76b9d-37eb-43df-8589-64edebbe49a1)

   ![10](https://github.com/user-attachments/assets/e450092b-0477-4ec3-b1c7-022d7e7f4366)

   Soal:

   Cobalah klik setiap button, apa yang terjadi ?

   Jawab:

   Menampilkan warna merah, biru, dan hijau dengan tombol yang mengubah latar belakang saat "Red", "Green", atau "Blue" diklik, untuk memanggil fungsi pengubah warna latar belakang utama.

9. Praktikum 9

   ![11](https://github.com/user-attachments/assets/d07e48fc-5ead-4f77-974a-53d95c65044f)

   Soal:

   Cobalah klik setiap button, apa yang terjadi ?

   Jawab:

   Mengganti dan memilih warna latar belakang dilakukan karena aplikasi menyediakan tombol dengan pilihan warna yang memungkinkan pengguna untuk memilih warna sesuai keinginan. Setiap tombol warna yang ada akan mengubah latar belakang sesuai dengan warna yang dipilih, memberikan fleksibilitas bagi pengguna untuk menyesuaikan tampilan aplikasi sesuai preferensi mereka.

