## 1.1 Latar Belakang
Game ini bernama GetCoin, game ini diciptakan karna saya ingin menuangkan isi pikiran saya tentang seorang petani yang sedang menggarap kebunnya di sekitaran hutan. Di dalam game tersebut, petani ini menemukan segumpalan koin ketika dia pergi kehutan, tak lama kemudian, petani tersebut berfikir untuk mencari koin tersebut di dalam hutan yang penuh dengan jebakan.

## 1.2. Deksripsi Teknologi Informasi
GetCoin adalah sebuah game yang bertemakan sebuah cerita yang dimana ada tokohnya, bisa kita sebut Petani. Petani ini hidup disebuah tempat yang jauh dari keramaian, beliau tinggal di dekat hutan. 
Petani ini memiliki kesibukannya sehari-hari yaitu berkebun di hutan. Dan pada suatu hari, ketika beliau sedang menggarap sebuah tanaman, tiba-tiba beliau ini menemukan segumpalan koin yang sangat berkilau, lalu beliau menghampirinya, dan mengambilnya. Akhirnya beliau membawa koin ini ke rumah beliau.
Pada esok harinya, beliau pergi ke hutan untuk mencari koin tersebut, apakah masih ada atau tidak, petani ini berusaha mencari koin tersebut dengan mengelilingi seluruh tempat yang ada dihutan tersebut dengan melewati rintangan-rintangan yang begitu berbahaya yang dilakukan oleh pihak-pihak yang tidak bertanggung jawab. disinilah saya ingin menggambarkan kisah petani itu kedalam sebuah game yang berjudul GetCoin
## 1.3. Branding
- Merek              : Get Coin
- Tagline            : Coin is My Life
- Kampanye           : Sebuah aplikasi game guna menjadi sebuah sarana hiburan
- Pengguna Sasaran   : Usia 9+
- Tema UI/UX         : Sederhana

## 2. User Story

Sebagai | Saya Ingin | Agar | Priority
---|---|---|---
User | Petani bisa bergerak | bisa menjelajahi hutan | ⭐⭐⭐⭐⭐
User | Petani bisa melewati rintangan | bisa melanjutkan perjalanannya | ⭐⭐⭐⭐⭐
User | Petani bisa membawa alat kebun | untuk melindungi diri | ⭐⭐⭐⭐⭐
User | Game ini ada fitur multiplayer | bisa bermain bersama teman disatu aplikasi | ⭐⭐⭐⭐⭐
Develop | Membuat berbagai macam map | tidak merasa bosan dengan satu map | ⭐⭐⭐⭐
Develop | Membuat tambahan fitur dan tampilan yang bagus | bisa membuat nyaman para user | ⭐⭐⭐⭐⭐

## 3. Struktur Data

---
title: Order example
---
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses

## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

Saya membuat game ini dengan device 
1. Lenovo dengan processor intel core I5 Gen 10 , SSD 512GB dengan grapics nvidia.
2. Smartphone Poco M4 Pro 4G
3. Firefox
4. Youtube
Saya membuat game ini menggunakan HTML, CSS, dan JavaScript dengan Visual Studio Code.


## 6. Desain User Experience dan User Interface

 <img width="960" alt="Screenshot 2024-01-02 134723" src="https://github.com/disyyy/syafiqalbariii/assets/148996770/5a583fd1-048d-43f0-ab32-00943e2e3fb6">
48996770/c301925c-6130-4d21-968c-4b793680000a">


## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

1. Mesin Komputasi:
   - Mesin komputasi (komputer atau perangkat lainnya) bertanggung jawab untuk menjalankan permainan Get Coin. Ini melibatkan pemrosesan semua instruksi dan perhitungan yang diperlukan untuk menjalankan permainan.
   - Mesin komputasi juga bertanggung jawab untuk mengendalikan grafik, suara, dan interaksi dengan pemain. Ini termasuk menggambar karakter, objek, dan latar belakang, memainkan efek suara, dan menanggapi input dari pemain.
2. Sistem Operasi:
   - Sistem operasi (seperti Windows, macOS, atau Android) menyediakan lingkungan di mana permainan Get Coin ini dapat berjalan. Ini menyediakan antarmuka antara perangkat keras dan perangkat lunak permainan.
   - Sistem operasi mengelola sumber daya perangkat keras seperti memori, CPU, dan perangkat input/output. Ini memastikan bahwa permainan Get Coin dapat berjalan dengan lancar dan efisien.
   - Sistem operasi juga menyediakan layanan dan fungsi yang digunakan oleh permainan, seperti manajemen file, jaringan, dan akses ke perangkat keras tambahan seperti gamepad atau mouse.
Dalam konteks permainan Get Coin, mesin komputasi dan sistem operasi bekerja sama untuk menjalankan permainan dengan lancar dan memberikan pengalaman bermain yang baik. Mesin komputasi bertanggung jawab untuk menjalankan semua aspek permainan, sementara sistem operasi menyediakan lingkungan dan layanan yang diperlukan untuk menjalankan permainan dengan baik.


## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

1. Algoritma
   - Algoritma pergerakan Petani: Dalam game Get Coin, petani bergerak ke depan secara terus-menerus. Algoritma yang digunakan adalah algoritma loop sederhana yang menggerakkan petani ke depan dengan kecepatan konstan.
   - Algoritma deteksi rintangan: Dalam game ini, rintangan muncul secara acak di layar. Algoritma deteksi rintangan digunakan untuk mendeteksi apakah petani bertabrakan dengan rintangan. Jika petani bertabrakan, permainan berakhir.
   - Algoritma skor: Algoritma skor digunakan untuk menghitung skor pemain berdasarkan jarak yang ditempuh oleh petani. Semakin jauh petani berlari, semakin tinggi skornya.
2. Struktur Data
   - Array: Array digunakan untuk menyimpan rintangan yang muncul di layar. Setiap rintangan memiliki posisi dan ukuran yang berbeda.
   - Variabel: Variabel digunakan untuk menyimpan informasi seperti posisi petani, kecepatan, skor, dan status permainan (berjalan atau berakhir).
3. Bahasa Pemrograman
   - JavaScript: Game Get Coin dikembangkan menggunakan bahasa pemrograman JavaScript. JavaScript adalah bahasa pemrograman yang sering digunakan untuk pengembangan game web. Dalam game ini, JavaScript digunakan untuk mengontrol pergerakan petani, deteksi rintangan, menghitung skor, dan mengatur tampilan game.
Selain JavaScript, game Get Coin juga menggunakan HTML5 untuk membuat tampilan dan struktur dasar game. HTML5 digunakan untuk membuat elemen-elemen seperti canvas, tombol, dan teks yang diperlukan dalam game.
Dan juga ada CSS, bisa digunakan untuk mengubah teks, tampilan background, transparasi, dan animasi yang diperlukan dalam game.


## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?
1. Perencanaan dan Analisis:  Tahap awal pengembangan perangkat lunak melibatkan pemahaman yang mendalam tentang kebutuhan dan tujuan game Get Coin. Maka pengembang akan menganalisis fitur yang diinginkan, merencanakan tata letak permainan, dan membuat rencana pengembangan yang terperinci.
2. Desain: Desain perangkat lunak melibatkan merancang struktur permainan, antarmuka pengguna, karakter, level, dan elemen visual lainnya. Desain ini mencakup aspek tampilan, tata letak, animasi yang akan digunakan dalam game Get Coin.
3. Pengkodean: Tahap pengkodean melibatkan implementasi desain permainan Get Coin menggunakan bahasa pemrograman dan kerangka kerja yang sesuai. Maka pengembang akan menulis kode untuk mengatur perilaku karakter, dll.


## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?
Dalam game Get Coin, penggunaan database memungkinkan pengembang untuk menyimpan dan mengelola data pemain, skor, dan lainnya. Ini memberikan fleksibiltas, personalisasi, dan fitur-fitur yang meningkatkan pengalaman bermain pemain.
