# ERD
ERD (Entity Relationship Diagram) adalah model atau rancangan untuk membuat database, supaya lebih mudah dalam menggambarkan data yang memiliki hubungan atau relasi dalam bentuk sebuah desain. Dengan adanya ER diagram, maka sistem database yang terbentuk dapat digambarkan dengan lebih terstruktur dan terlihat rapi. 
## Model Data ERD
Model ini berguna untuk membuat dokumentasi dari segala bentuk arsitektur data. Model ini dibagi ke dalam tiga model. Berikut adalah penjelasannya.
- Model data konseptual
    Model data ini adalah model data paling tinggi karena di dalamnya berisi data-data yang detail. Tujuan dari pengembangan model data konseptual adalah untuk memberikan gambaran yang jelas mengenai struktur database yang terdiri dari entitas dan relasi antara setiap entitas.
- Model data logis
    Model data logis ini adalah pengembangan dari model data konseptual, itu sebabnya dalam proses pembuatannya model data ini dibuat lebih rinci dari model data konseptual dan dibuat setelah model data konseptual selesai dibuat. Model ini digunakan untuk menambahkan informasi secara eksplisit kedalam unsur-unsur model konseptual.
- Model data fisik
    Model data fisik adalah pengembangan dari masing-masing model data logis. Model data ini biasanya digunakan untuk merancang sebuah database.

## Komponen ERD
- Entitas
Entitas merupakan kumpulan objek yang dapat teridentifikasi secara unik. Di dalam ERD, entitas dilambangkan dengan bentuk persegi panjang. Kemudian, entitas lemah akan digambarkan dengan bentuk persegi panjang kecil di dalam persegi panjang yang besar. Untuk entitas lemah digunakan untuk melambangkan entitas yang memiliki hubungan dengan entitas lain (tidak unik).
- Atribut
Untuk setiap entitas sendiri mempunyai atribut yang berfungsi untuk mendeskripsikan karakteristik dari entitas tersebut.
    - Atribut Kunci
    Atribut kunci atau Key Attributes adalah atribut yang berfungsi untuk menentukan data yang bersifat penting.
    - Atribut Simpel
    Atribut simpel adalah atribut yang tidak dapat dipecah lagi dan bernilai tunggal.
    - Atribut Multinilai
    Atribut multinilai atau Multivalue Attributes adalah atribut yang memiliki atribut lebih dari satu nilai.
    - Atribut gabungan
    Atribut gabungan adalah atribut yang terdiri dari beberapa atribut yang berukuran lebih kecil dan memiliki arti tertentu.
    - Atribut derivvatif
    Atribut derivatif adalah atribut yang dihasilkan dari atribut lain dan atributnya tidak wajib untuk ditulis dalam Entity Relationship Diagram.
- Relasi
Relasi dalam ERD adalah hubungan yang terjadi antara satu atau lebih entitas. Relasi sendiri sering disebut dengan proses. Komponen ini digambarkan dengan lambang belah ketupat. Terdapat tiga jenis relasi yang digunakan dalam ERD dan perlu kamu ketahui, berikut adalah jenisnya.
    - One to One
    Yang berarti, setiap entitas hanya boleh memiliki relasi dengan satu entitas yang lain.
    - One to Many
    Merupakan hubungan antara satu entitas dengan beberapa entitas, dan begitu pula sebaliknya.
    - Many to Many
    Merupakan hubungan antara beberapa entitas yang memiliki lebih dari satu relasi.
- Garis
Garis berfungsi untuk menghubungkan antar atribut sebagai bentuk hubungan entitas yang model dari diagram ER itu sendiri.

## Cara Membuat ERD
1. Identifikasi Entitas
Langkah pertama adalah mengidentifikasi semua jenis entitas yang akan di gunakan. Kita dapat memulai dengan menggambar persegi panjang yang didalamnya terdapat deskripsi singkat terkait nama entitas tersebut.  

2. Deskripsikan Relasi Entitas
Selanjutnya, mulai mengidentifikasi beberapa entitas yang memiliki relasi yang sama dihubungkan dengan menggunakan garis. Lakukan langkah tersebut sesuai dengan kebutuhan database proyek yang akan dikembangkan. Kita dapat menambahkan simbol berbentuk diamond untuk mendeskripsikan hubungan tersebut.

3. Menambahkan Atribut
Berikutnya, menambahkan beberapa atribut. Pastikan juga untuk membuat atribut key pada setiap entitas dengan menggambarkan dalam bentuk oval.

4. Melengkapi Diagram
Dan langkah yang terakhir adalah dengan melengkapi diagram ER tersebut sesuai dengan kebutuhan sistem yang akan di buat. Teliti kembali untuk setiap komponen jika ada simbol yang salah, atau komponen atribut yang tertukar. Kita juga dapat menggunakan warna yang lebih terang untuk menandai setiap atribut yang dianggap penting.

## Contoh ERD
![N|Solid](https://anungyulirachmanto.files.wordpress.com/2015/11/erd.jpg)