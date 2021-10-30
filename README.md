# Soal 01 UTS  PBO

Buatlah sebuah kelas bernama DriverOjol. Kelas ini memiliki kriteria sebagai berikut:

* Memiliki properti `Nama`, `no plat motor`, `saldo`, `status`
* Property `nama`, `no plat motor` hanya dapat dibaca saja oleh kelas lain dan diinisalisasi oleh dalam `constructor`
* Kelas ini memiliki 2 buah `constructor`, salah satunya digunakan digunakan untuk menset `saldo`. 
* Kelas ini memiliki method `topUp` yang digunakan untuk menambah saldo. Saldo bisa ditambahkan jika saldo > 0 dan saldo <= 1 jt.
* Buatkan metod getter dan setter untuk properti `status`. pastikan `status` hanya bernilai 0, 1, 2 dimana 0 berarti tidak aktif, 1 berarti menunggu penumpang, 2 sedang dalam misi. Property `status` bertipe integer.
* Kelas ini memiliki method `hitung tarif`. Method ini memiliki 2 argumen yaitu jarak bertipe integer dan macet bertipe boolean. Perhitungan tarif dilakukan sebagai berikut. Jika macet = false , Rp 3000 untuk 1km pertama, selanjutnya Rp 200 untuk setiap 100m. Sementara itu jika macet Rp 4000 untuk 1km pertama dan Rp 300 untuk 100m berikutnya.

Buatlah 2 buah object dari kelas driver ojol diatas dengan nilai property sebagai berikut

* Nama : Udin
* No Plat : BA 751 AB
* Saldo : 5600
* status : Sedang menunggu penumpang.

Setelah object tersebut dibuat
* Tampilkan informasi dari object tersebut (nama, no plat, saldo dan status)
* Hitung dan tampilkan tarif untuk 4558 m pada kondisi macet dan pada kondisi normal.

Seluruh identifier ditulis mengikuti sarang penamaan Java.