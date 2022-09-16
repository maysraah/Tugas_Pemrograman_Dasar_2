# CHAPTER 1 INTRODUCTION

**CHAPTER CONTENTS**

1. COMPUTER PROGRAMS
2. THE ANATOMY OF A COMPUTER
3. THE JAVA PROGRAMMING LANGUAGE
4. BECOMING FAMILIAR WITH YOUR PROGRAMMING ENVIRONMENT
5. ANALYZING YOUR FIRST PROGRAM
6. ERRORS
7. PROBLEM SOLVING: ALGORITHM DESIGN <br><br>
---

### **1.1 Computer Programs (Program Komputer)**<br><br>
Anda mungkin pernah menggunakan komputer untuk bekerja atau bersenang-senang. Banyak orang menggunakan komputer
untuk tugas sehari-hari seperti perbankan elektronik atau menulis makalah. Komputer
baik untuk tugas-tugas seperti itu. Mereka dapat menangani tugas yang berulang, seperti menjumlahkan angka
atau menempatkan kata-kata di halaman, tanpa bosan atau lelah.

Fleksibilitas komputer adalah fenomena yang cukup menakjubkan. Mesin yang sama
dapat menyeimbangkan buku cek Anda, menyusun makalah Anda, dan bermain game. Sebaliknya,
mesin lain melakukan berbagai tugas yang jauh lebih sempit; sebuah mobil drive dan pemanggang roti
bersulang. Komputer dapat melakukan berbagai tugas karena mereka mengeksekusi berbeda
program, yang masing-masing mengarahkan komputer untuk mengerjakan tugas tertentu. 

Komputer itu sendiri adalah mesin yang menyimpan data (angka, kata, gambar), berinteraksi dengan perangkat (monitor, sound system, printer), dan menjalankan program.
Sebuah **program komputer** memberitahu komputer, secara rinci, urutan langkah-langkah yang:
dibutuhkan untuk memenuhi suatu tugas. Komputer fisik dan perangkat periferal secara kolektif
disebut **perangkat keras**. Program yang dijalankan komputer disebut **perangkat lunak**.

Program komputer saat ini sangat canggih sehingga sulit dipercaya bahwa mereka
terdiri dari instruksi yang sangat primitif. Instruksi tipikal mungkin satu
dari berikut ini:
- Letakkan titik merah pada posisi layar tertentu.
- Jumlahkan dua angka.
- Jika nilai ini negatif, lanjutkan program pada instruksi tertentu.

Pengguna komputer memiliki ilusi interaksi yang lancar karena sebuah program berisi
sejumlah besar instruksi seperti itu, dan karena komputer dapat mengeksekusinya di
kecepatan tinggi.

Tindakan merancang dan mengimplementasikan program komputer disebut **pemrograman**. Dalam buku ini, Anda akan mempelajari cara memprogram komputer—yaitu, cara mengarahkan
komputer untuk menjalankan tugas.

Untuk menulis game komputer dengan efek gerakan dan suara atau pengolah kata
yang mendukung font dan gambar mewah adalah tugas kompleks yang membutuhkan tim yang terdiri dari banyak orang
programmer yang sangat terampil. Upaya pemrograman pertama Anda akan lebih biasa.
Konsep dan keterampilan yang Anda pelajari dalam buku ini membentuk landasan penting, dan
Anda tidak perlu kecewa jika program pertama Anda tidak menyaingi yang canggih
perangkat lunak yang akrab bagi Anda. Sebenarnya, Anda akan menemukan bahwa ada sensasi yang luar biasa
bahkan dalam tugas pemrograman sederhana. Sungguh pengalaman yang luar biasa melihat komputer
tepat dan cepat melaksanakan tugas yang akan memakan waktu berjam-jam, untuk membuat perubahan kecil dalam program yang mengarah pada perbaikan segera, dan untuk melihat
komputer menjadi perpanjangan dari kekuatan mental Anda.

**SELF CHECK**

1. Apa yang diperlukan untuk memutar musik di komputer?
2. Mengapa pemutar CD kurang fleksibel dibandingkan komputer?
3. Apa yang perlu diketahui pengguna komputer tentang pemrograman agar dapat memainkan video game?

---
### **1.2 The Anatomy of a Computer (Anatomi Komputer)** <br><br>
Untuk memahami proses pemrograman, Anda harus memiliki pemahaman dasar dari blok bangunan yang membentuk komputer. Kami akan melihat secara pribadi komputer. Komputer yang lebih besar memiliki komponen yang lebih cepat, lebih besar, atau lebih kuat, tetapimereka pada dasarnya memiliki desain yang sama.

Di jantung komputer terletak **unit pemrosesan utama** atau _Central Processing Unit (CPU)_ (lihat Gambar 1). Bagian dalam pengkabelan CPU sangat rumit. Misalnya, prosesor Intel Core (yang populer CPU untuk per-komputer pribadi pada saat ini tulisan) terdiri dari beberapa ratus juta elemen struktural, yang disebut _transistor_. 

CPU melakukan kontrol program dan data pengolahan. Artinya, CPU menempatkan dan mengeksekusi instruksi program; itu melaksanakan operasi aritmatika seperti penjumlahan, pengurangan,perkalian, dan pembagian; itu mengambil datadari memori eksternal atau perangkat dan tempatdata yang diproses ke dalam penyimpanan.

<p align="center"><img src="img/gambar1.jpeg"></p>
<p align="center">Gambar 1 Unit Pemrosesan Utama</p>

Ada dua macam penyimpanan. Penyimpanan utama,atau memori, dibuat dari sirkuit elektronik yang dapat menyimpan data, asalkan:disuplai dengan tenaga listrik. **Penyimpanan sekunder**, biasanya hard disk (lihat Gambar 2)atau solid-state drive, menyediakan penyimpanan yang lebih lambat dan lebih murah yang bertahan tanpa listrik. 

<p align="center"><img src="img/gambar2.jpeg"></p>
<p align="center">Gambar 2 Hard Disk</p>

Sebuah hard disk terdiri dari piringan berputar, yang dilapisi dengan magnetnbahan. Solid-state drive menggunakan komponen elektronik yang dapat menyimpan informasitanpa daya, dan tanpa bagian yang bergerak.Untuk berinteraksi dengan pengguna manusia, komputer membutuhkan perangkat periferal. Komputer mentransmisikan informasi (disebut _output_) kepada pengguna melalui layar tampilan, speaker, dan printer. Pengguna dapat memasukkan informasi (disebut _input_) untuk komputerdengan menggunakan keyboard atau alat penunjuk seperti mouse.

Beberapa komputer adalah unit mandiri, sedangkan yang lain saling berhubungan melalui **jaringan**. Melalui kabel jaringan, komputer dapat membaca data dan program dari lokasi penyimpanan pusat atau mengirim data ke komputer lain. Untuk penggunadari komputer jaringan, bahkan mungkin tidak jelas data mana yang berada di komputeritu sendiri dan yang ditransmisikan melalui jaringan.

Gambar 3 memberikan gambaran skematis arsitektur komputer pribadi. Instruksi dan data program (seperti teks, angka, audio, atau video) berada di sekunder penyimpanan atau di tempat lain di jaringan. Ketika sebuah program dimulai, instruksinyadibawa ke memori, di mana CPU dapat membacanya. CPU membaca dan mengeksekusi satu instruksi pada suatu waktu. Seperti yang diarahkan oleh instruksi ini, CPU membacadata, memodifikasinya, dan menulisnya kembali ke memori atau penyimpanan sekunder. Beberapa programinstruksi akan menyebabkan CPU menempatkan titik-titik pada layar tampilan atau printer atau kegetaran speakernya. Karena tindakan ini terjadi berkali-kali dan dengan kecepatan tinggi,pengguna manusia akan melihat gambar dan suara. Beberapa instruksi program membaca penggunamasukan dari keyboard, mouse, sensor sentuh, atau mikrofon. Analisis programsifat input ini dan kemudian mengeksekusi instruksi yang sesuai berikutnya.

<p align="center"><img src="img/gambar3.jpeg"></p>
<p align="center">Gambar 3 Desain Skema Komputer Pribadi</p>

**SELF CHECK**

4. Di mana program disimpan saat sedang tidak berjalan?
5. Bagian komputer mana yang melakukan operasi aritmatika, seperti penjumlahan?
dan perkalian?
6. Smartphone modern adalah komputer, sebanding dengan komputer desktop. Manakah
komponen smartphone sesuai dengan yang ditunjukkan pada Gambar 3?<br><br>

**Komputasi & Masyarakat 1.1 Komputer Ada Dimana-mana**

Ketika komputer pertama kali ditemukan pada tahun 1940-an, komputer memenuhi seluruh ruangan.  Foto di bawah menunjukkan ENIAC (_integrator numerik elektronik dan komputer_), selesai pada tahun 1946 di University of Pennsylvania.  ENIAC digunakan oleh militer untuk menghitung lintasan proyektil.  Saat ini, fasilitas komputasi mesin pencari, toko internet, dan jejaring sosial memenuhi gedung-gedung besar yang disebut pusat data.  Di ujung lain spektrum, komputer ada di sekitar kita.  Ponsel Anda memiliki komputer di dalamnya, seperti halnya banyak kartu kredit dan kartu tarif untuk angkutan umum.  Sebuah mobil modern memiliki beberapa komputer––untuk mengontrol mesin, rem, lampu, dan radio. 

<p align="center"><img src="img/eniac.jpeg"></p>
<p align="center">ENIAC</p>

Munculnya komputasi di mana-mana berubah banyak aspek dari kami hidup.  Pabrik digunakan mempekerjakan orang untuk lakukan perakitan berulang tugas-tugas yang hari ini dilakukan oleh komputer- robot yang dikendalikan, operasi dimakan oleh segelintir orang siapa yang tahu caranya bekerja dengan komputer.  Buku, musik, dan film saat ini sering dikonsumsi di komputer, dan komputer hampir selalu terlibat dalam produksi mereka.  Buku yang sedang Anda baca sekarang tidak mungkin ditulis tanpa komputer.

<p align="center"><img src="img/kartu_transit.jpeg"></p>
<p align="center">Kartu transit ini berisi komputer</p>

Mengetahui tentang komputer dan cara memprogramnya telah menjadi keterampilan penting dalam banyak karier.  Insinyur merancang mobil yang dikendalikan komputer dan peralatan medis yang menyelamatkan nyawa.  Ilmuwan komputer mengembangkan program yang membantu orang berkumpul untuk mendukung tujuan sosial.  Misalnya, para aktivis menggunakan jejaring sosial untuk berbagi video yang menunjukkan pelecehan oleh rezim yang represif, dan informasi ini berperan penting dalam mengubah opini publik. Ketika komputer, besar dan kecil, menjadi semakin tertanam dalam kehidupan kita sehari-hari, semakin penting bagi setiap orang untuk memahami cara kerjanya, dan cara bekerja dengannya.  Saat Anda menggunakan buku ini untuk mempelajari cara memprogram komputer, Anda akan mengembangkan pemahaman yang baik tentang dasar-dasar komputasi yang akan membuat Anda menjadi warga negara yang lebih berpengetahuan dan, mungkin, seorang profesional komputasi.<br>

---
### **1.3 The Java Programming Language (Bahasa Pemrograman Java)** <br><br>
Untuk menulis program komputer, Anda perlu memberikan urutan instruksi yang dapat dieksekusi oleh CPU. Sebuah program komputer terdiri dari sejumlah besar program instruksi CPU sederhana, dan membosankan juga rawan untuk kesalahan untuk menentukannya satu persatu. Karena alasan itu, bahasa pemrograman tingkat tinggi telah dibuat. Dalam bahasa tingkat tinggi, Anda menentukan tindakan yang harus dilakukan programnya. Penyusun menerjemahkan instruksi tingkat tinggi ke dalam instruksi yang lebih rinci (disebut kode mesin) yang dibutuhkan oleh CPU. Banyak bahasa pemrograman yang berbeda telah dirancang untuk tujuan yang berbeda.

Pada tahun 1991, sebuah kelompok yang dipimpin oleh James Gosling dan Patrick Naughton di Sun Microsystems merancang sebuah bahasa pemrograman, berkode nama “Green”, untuk kegunaan di perangkat konsumen, seperti “set-top” televisi cerdas. Bahasanya dirancang untuk sederhana, aman, dan dapat digunakan oleh berbagai tipe prosesor yang berbeda. Tidak ada pelanggan yang pernah ditemukan untuk teknologi ini.

<p align="center"><img src="img/james_gosling.jpeg"></p><br>

Gosling menceritakan pada tahun 1994 tim menyadari “Kita bisa menulis browser yang sangat keren. Itu adalah salah satu dari sedikit hal dalam arus utama klien/server yang membutuhkan beberapa hal aneh yang telah kami lakukan: arsitektur netral, waktu nyata, andal, aman.” Java diperkenalkan kepada orang banyak yang antusias di pameran SunWorld pada tahun 1995, bersama dengan browser yang menjalankan **applet**—kode Java yang dapat ditemukan di mana saja di Internet. Gambar di sebelah kanan menunjukkan contoh khas applet.

<p align="center"><img src="img/applet.jpeg"></p><br>

Sejak saat itu, Java telah berkembang dengan kecepatan yang fenomenal. Programmer telah menggunakan bahasa ini karena lebih mudah digunakan daripada saingan terdekatnya, C++. Selain itu, Java memiliki perpustakaan yang kaya yang memungkinkan untuk menulis program portabel yang dapat melewati sistem operasi berpemilik—fitur yang sangat dicari oleh mereka yang ingin menjadi independen dari sistem berpemilik tersebut dan diperjuangkan dengan sengit oleh vendor mereka.

<p align="center"><img src="img/tabel1.jpeg"></p><br>

Karena Java dirancang untuk internet, ia mempunyai dua atrbut yang membuatnya sangat cocok untuk pemula: keamanan dan portabilitas.

Java dirancang sehingga siapapun dapat menjalankan program di browser mereka tanpa takut. Fitur keamanan bahasa Java memastikan program dihentikan apabila mencoba untuk melakukan sesuatu membahayakan. Memiliki lingkungan yang aman juga membantu bagi siapapun yang mempelajari Java. Disaat Anda melakukan error yang mengakibatkan perilaku membahayakan, program Anda dihentikan dan Anda menerima laporan eror yang akurat.

Manfaat lain dari Java adalah portabilitas. Program Java yang sama akan jalan, tanpa perubahan, pada Windows, UNIX, Linux, atau Macintosh. Untuk mencapai portabilitas, penyusun Java tidak menerjemahkan program-program Java langsung ke dalam instruksi CPU. Melainkan, program Java yang tersusun memuat instruksi untuk **mesin virtual** Java, sebuah program yang menyimulasikan CPU nyata. Portabilitas adalah manfaat lain untuk murid pemula. Anda tidak harus belajar bagaimana cara menulis program untuk platform yang berbeda.

Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.

Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.

Java telah diperpanjang berkali-kali selama masa pakainya—lihat Table 1. Dalam buku ini, kami menganggap bahwa Anda memiliki Java versi 8 atau yang lebih baru.

Pada akhirnya, Anda tidak dapat berharap untuk mempelajari keseluruhan dari Java dalam satu pembelajaran. Bahasa Java itu sendiri relatif sederhana, tapi Java berisi sekumpulan library packages yang diperlukan untuk menulis program yang berguna. Ada paket untuk grafik, desain antarmuka pengguna, kriptografi, jaringan, suara, penyimpanan basis data, dan banyak kegunaan lainnya. Bahkan programmer Java yang ahli sekalipun tidak dapat berharap untuk mengetahui isi semua paket—mereka hanya menggunakan yang mereka perlukan untuk proyek tertentu.

Dengan  menggunakan buku ini, Anda diharapkan untuk belajar banyak tentang bahasa Java dan tentang paket yang paling penting. Camkan selalu bahwa tujuan utama dari buku ini bukan untuk Anda mengingat detail kecil Java, tapi untuk mengajari Anda cara berpikir tentang pemrograman.

**SELF CHECK**

7. Apa dua manfaat terpenting dari bahasa Java?
8. Berapa lama waktu yang dibutuhkan untuk mempelajari seluruh perpustakaan Java?


---
### **1.4 Becoming Familiar with Your Programming Environment (Menjadi Familiar dengan Lingkungan Pemrograman Anda)** <br><br>
Banyak siswa menemukan bahwa alat yang mereka butuhkan sebagai pemrogram sangat berbeda dari perangkat lunak yang mereka kenal. Anda harus meluangkan waktu untuk membiasakan diri dengan lingkungan pemrograman Anda. Karena sistem komputer sangat bervariasi, buku ini hanya dapat memberikan garis besar langkah-langkah yang perlu Anda ikuti. Merupakan ide bagus untuk Anda berpartisipasi dalam lab praktik, atau meminta teman yang berpengetahuan luas untuk memberi Anda penjelasan.

<p align="center"><img src="img/gambar4.jpeg">Gambar 4 Menjalankan
Halo Printer Program dalam sebuah Lingkungan Pengembangan Terintegrasi</p><br>

Langkah1 Mulai lingkungan pengembangan Java.

Sistem komputer sangat berbeda dalam hal ini. Pada banyak komputer terdapat **lingkungan pengembangan terintegrasi** di mana Anda dapat menulis dan menguji program Anda. Di komputer Anda pertama kali meluncurkan **editor**, sebuah program yang berfungsi seperti pengolah kata, di mana Anda dapat memasukkan instruksi Java Anda; Anda kemudian membuka jendela konsol dan ketik perintah untuk menjalankan program Anda. Anda perlu mencari tahu bagaimana memulai dengan lingkungan Anda.

Langkah2 Tulis sebuah program yang sederhana.
Pilihan tradisional untuk program pertama dalam bahasa pemrograman baru adalah program yang menampilkan sapaan sederhana: “Halo, Dunia!”. Mari kita ikuti tradisi itu. Inilah "Halo, Dunia!" program di java:

<p align="center"><img src="img/code1.jpeg"></p><br>

Kami akan memeriksa program ini di bagian selanjutnya.

Apa pun lingkungan pemrograman yang Anda gunakan, Anda memulai aktivitas Anda dengan mengetikkan pernyataan program ke dalam jendela editor.

Buat file baru dan beri nama HelloPrinter.java, menggunakan langkah-langkah yang sesuai untuk lingkungan Anda. (Jika lingkungan Anda mengharuskan Anda memberikan nama proyek selain nama file, gunakan namahello untuk proyek tersebut.) Masukkan instruksi program persis seperti yang diberikan di atas. Atau, temukan salinan elektronik dalam kode pendamping buku ini dan tempelkan ke editor Anda.

Saat Anda menulis program ini, perhatikan baik-baik berbagai simbol, dan ingatlah bahwa Java sensitif terhadap huruf besar-kecil. Anda harus memasukkan huruf besar dan kecil persis seperti yang muncul dalam daftar program. Anda tidak dapat mengetikMAIN atauPrintLn. Jika Anda tidak hati-hati, Anda akan mengalami masalah—lihat Kesalahan Umum 1.2.

<p align="center"><img src="img/code2.jpeg">Gambar 5 Jalankan HelloPrinter Program di Dalam sebuah Console Window</p><br>

Langkah3 Jalankan programnya.
 
Proses untuk menjalankan program sangat bergantung pada lingkungan pemrograman Anda. Anda mungkin harus mengklik tombol atau memasukkan beberapa perintah. Saat Anda menjalankan program pengujian, pesannya.

    Hello,World!

akan muncul di suatu tempat di layar (lihat Gambar 4 dan Gambar 5).

Untuk menjalankan program Anda, kompiler Java menerjemahkan **file sumber** Anda (yaitu, pernyataan yang Anda tulis) ke dalam file kelas. (Sebuah file kelas berisi instruksi untuk mesin virtual Java.) Setelah kompilator menerjemahkan kode sumber Anda ke dalam instruksi mesin virtual, mesin virtual akan mengeksekusinya. Selama eksekusi, mesin virtual mengakses pustaka kode yang telah ditulis sebelumnya, termasuk implementasi kelasSystem danPrintStream yang diperlukan untuk menampilkan keluaran program. Gambar 6 merangkum proses membuat dan menjalankan program Java. Di beberapa lingkungan pemrograman, kompilator dan mesin virtual pada dasarnya tidak terlihat oleh pemrogram—mereka dijalankan secara otomatis setiap kali Anda meminta untuk menjalankan program Java. Di lingkungan lain, Anda perlu meluncurkan kompiler dan mesin virtual secara eksplisit.

Langkah4 Rapikan pekerjaamu.
Sebagai seorang programmer, Anda menulis program, mencobanya, dan memperbaikinya. Anda menyimpan program Anda dalam file. File disimpan dalam folder atau direktori. Sebuah folder dapat berisi

<p align="center"><img src="img/gambar6.jpeg">Gambar 6  Dari Kode Sumber ke Program yang Berjalan</p><br>

file serta folder lain, yang dengan sendirinya dapat berisi lebih banyak file dan folder 
(lihat Gambar 7). 

<p align="center"><img src="img/gambar7.jpeg">Gambar 7 Hirarki Folder</p><br>

Hirarki ini bisa sangat besar, dan Anda tidak perlu khawatir dengan semua cabangnya. Namun, Anda harus membuat folder untuk mengatur pekerjaan Anda. Sebaiknya buat folder terpisah untuk pro-tugas mata kuliah tata bahasa. Di dalam folder itu, buat folder terpisah untuk setiap program.Beberapa lingkungan pemrograman menempatkan program Anda ke lokasi default jika Anda tidak menentukan folder sendiri. Dalam hal ini, Anda perlu mencari tahu di mana file-file itu berada.Pastikan Anda memahami di mana file Anda berada dalam hierarki folder. Informasi ini penting ketika Anda mengirimkan file untuk penilaian, danuntukmembuat salinan cadangan (lihat Tip Pemrograman 1.1).

**SELF CHECK**

9. Di mana file HelloPrinter.java disimpan di komputer Anda?
10. Apa yang Anda lakukan untuk melindungi diri Anda dari kehilangan data saat Anda mengerjakan proyek pemrograman?

---
**Tip Pemrograman 1.1**
Salinan Cadangan

Anda akan menghabiskan banyak waktu untuk membuat dan meningkatkan program Java. Sangat mudah untuk menghapus file secara tidak sengaja, dan terkadang file hilang karena kerusakan komputer. Mengetik ulang konten file yang hilang membuat frustrasi dan memakan waktu. Oleh karena itu, sangat penting bagi Anda untuk mempelajari cara melindungi file dan membiasakannya jikamelakukannya sebelum bencana terjadi. Mencadangkan file di memoristick adalah metode penyimpanan yang mudah dan nyaman bagi banyak orang. Bentuk pencadangan lain yang semakin populer adalah penyimpanan file Internet.

Berikut adalah beberapa petunjuk yang perlu diingat:
- Sering-seringlah membuat cadangan. Mencadangkan file hanya membutuhkan beberapa detik, dan Anda akan membenci diri sendiri jika harus menghabiskan banyak waktu untuk membuat ulang pekerjaan yang sebenarnya bisa Anda simpan dengan mudah. Saya sarankan Anda mencadangkan pekerjaan Anda setiap tiga puluh menit sekali.
- Putar cadangan. Gunakan lebih dari satu direktori untuk cadangan, dan putar mereka. Artinya, back up dulu ke direktori pertama. Kemudian kembali ke direktori kedua. Kemudian gunakan yang ketiga, lalu kembali ke yang pertama. Dengan begitu Anda selalu memiliki tiga cadangan terbaru. Jika perubahan terbaru Anda memperburuk keadaan, Anda dapat kembali ke versi yang lebih lama.
- Perhatikan arah pencadangan. Pencadangan melibatkan penyalinan file dari satu tempat ke tempat lain. Anda harus melakukannya dengan benar—yaitu, menyalin dari lokasi kerja Anda ke lokasi pencadangan. Jika Anda melakukannya dengan cara yang salah, Anda akan menimpa file yang lebih baru dengan versi yang lebih lama.
- Periksa cadangan Anda sesekali. Periksa kembali apakah cadangan Anda berada di tempat yang Anda pikirkan. Tidak ada yang lebih membuat frustrasi daripada mengetahui bahwa cadangan tidak ada saat Anda membutuhkannya.
- Santai, lalu pulihkan. Saat Anda kehilangan file dan perlu memulihkannya dari cadangan, kemungkinan besar Anda berada dalam keadaan gelisah dan tidak bahagia. Ambil napas dalam-dalam dan pikirkan proses pemulihan sebelum Anda mulai. Bukan hal yang aneh bagi pengguna komputer yang gelisah untuk menghapus cadangan terakhir ketika mencoba memulihkan file yang rusak.
---

### **1.5 Analyzing Your First Program (Menganalisis Program Pertama Anda)** <br><br>
Pada bagian ini, kita akan menganalisis program Java pertama secara rinci. Di sini adalah kode sumber.

<p align="center"><img src="img/code3.jpeg"></p>
Garis
    
    public class HelloPrinter
menunjukkan deklarasi kelas yang disebut HelloPrinter. 

Setiap program Java terdiri dari satu atau lebih kelas. Kita akan membahas kelas secara lebih rinci di Bab 2 dan 3.

Kata publik menunjukkan bahwa kelas dapat digunakan oleh "publik". Anda kemudian akan menemukan fitur pribadi.

Di Java, setiap file sumber dapat berisi paling banyak satu kelas publik, dan nama kelas publik harus sesuai dengan nama file yang berisi kelas tersebut. Misalnya, kelas HelloPrinter harusdimuat dalam file bernama HelloPrinter.java.

Konstruksi

    public static void main(String[] args)
    {
        . . .
    }
mendeklarasikan metode yang disebut main. Metode berisi kumpulan instruksi pemrograman yang menjelaskan bagaimana melakukan tugas tertentu.

Setiap aplikasi Java harus memiliki metode utama. Sebagian besar program Java berisi metode lain selain utama, dan Anda akan melihat di Bab 3 cara menulis metode lain.

Istilah statis dijelaskan secara lebih rinci dalam Bab 8, dan arti dari String[ ] args dibahas dalam Bab 11. Pada saat ini, cukup pertimbangkan


    public class ClassName
    { 
        public static void main(String[] args) 
        { 
        . . . 
        } 
    } 
sebagai bagian dari "pipa" yang diperlukan untuk membuat program Java. Program pertama kita memiliki semua instruksi di dalam metode main kelas.

Metode main berisi satu atau lebih instruksi yang disebut **pernyataan**. Setiap pernyataan diakhiri dengan titik koma (;). Ketika sebuah program dijalankan, pernyataan dalam metode utama dieksekusi satu per satu.

<p align="center"><img src="img/syntax1.jpeg"></p><br>

Dalam contoh program kita, metode utama memiliki satu pernyataan:

    System.out.println("Hello, World!");
Pernyataan ini mencetak sebaris teks, yaitu “Hello, World!”. Dalam perny ataan ini, kita memanggil metode yang, untuk alasan yang tidak akan kita jelaskan di sini, ditentukan dengan nama System.out.println yang agak panjang.

Kita tidak harus mengimplementasikan metode ini—programmer yang menulis library Java sudah melakukannya untuk kita. Kita hanya ingin metode melakukan tugas yang dimaksudkan, yaitu mencetak nilai.

Setiap kali Anda memanggil metode di Java, Anda perlu menentukan
1. Metode yang ingin Anda gunakan (dalam hal ini, System.out.println).
2. Nilai apa pun yang dibutuhkan metode untuk menjalankan tugasnya (dalam hal ini, "Hello, World!"). Istilah teknis untuk nilai seperti itu adalah **argumen**. Argumen diapit dalam tanda kurung. Beberapa argumen dipisahkan dengan koma.

Urutan karakter yang diapit tanda kutip
    
    "Hello, World!" 
disebut **string**. Anda harus menyertakan isi string di dalam tanda kutip sehingga kompilator mengetahui maksud Anda secara harfiah "Hello, World!". Ada alasan untuk persyaratan ini. Misalkan Anda perlu mencetak kata _main_. Dengan melampirkannya dalam tanda kutip, "main", kompiler tahu maksud Anda urutan karakter m a i n,
bukan metode bernama main. Aturannya sederhana, Anda harus menyertakan semua string teks dalam tanda kutip, sehingga kompilator menganggapnya sebagai teks biasa dan tidak mencoba menafsirkannya sebagai instruksi program.

Anda juga dapat mencetak nilai numerik. Misalnya pernyataan

    System.out.println(3 + 4);
mengevaluasi ekspresi 3 + 4 dan menampilkan angka 7.

MetodeSystem.out.println mencetak string atau angka dan kemudian memulai baris baru. Misalnya, urutan pernyataan

    System.out.println("Hello"); 
    System.out.println("World!");
mencetak dua baris teks:

    Hello 
    World!
Ada metode kedua, System.out.print, yang dapat Anda gunakan untuk mencetak item tanpa memulai baris baru. Misalnya, output dari dua pernyataan

    System.out.print("00"); 
    System.out.println(3 + 4);

adalah garis tunggal

    007
<br>

**SELF CHECK**

11. Bagaimana Anda memodifikasi program HelloPrinter untuk menyambut Anda?
12. Bagaimana Anda memodifikasi program HelloPrinter untuk mencetak kata “Halo”
Tegak lurus?
13. Apakah program akan terus bekerja jika Anda mengganti baris 7 dengan pernyataan ini?
System.out.println(Halo);
14. Apa yang dicetak oleh kumpulan pernyataan berikut?
System.out.print("Angka keberuntungan saya adalah");
System.out.println(3 + 4 + 5);
15. Apa yang dicetak oleh pernyataan berikut?
    - System.out.println("Hello");
    - System.out.println("");
    - System.out.println("World");
<br><br>

**Kesalahan Umum 1.1**
Menghilangkan Titik Koma

Di Java setiap pernyataan harus diakhiri dengan titik koma. Lupa mengetik titik koma adalah kesalahan umum. Ini membingungkan kompiler, karena kompiler menggunakan titik koma untuk menemukan di mana satu pernyataan berakhir dan yang berikutnya dimulai. Kompilator tidak menggunakan jeda baris atau kurung kurawal untuk mengenali akhir pernyataan. Misalnya, kompiler menganggap

    System.out.println("Hello") 
    System.out.println("World!");
satu pernyataan, seolah-olah Anda telah menulis

    System.out.println("Hello") System.out.println("World!");
Kemudian tidak mengerti pernyataan itu, karena tidak mengharapkan kata Sistem mengikuti kurung penutup setelah "Halo". Obatnya sederhana. Pindai setiap pernyataan untuk mencari titik koma, sama seperti Anda akan memeriksa bahwa setiap kalimat bahasa Inggris diakhiri dengan tanda titik. Namun, jangan menambahkan titik koma di akhir public class Hello atau public static void main. Garis-garis ini bukan pernyataan.

---
### **1.6 Errors (Kesalahan)** <br><br>
Bereksperimenlah sedikit dengan program HelloPrinter. Apa yang terjadi jika Anda membuat kesalahan pengetikan seperti

    System.ou.println("Hello, World!"); 
    System.out.println("Hello, Word!");

Dalam kasus pertama, kompiler akan mengeluh. Ini akan mengatakan bahwa ia tidak tahu apa yang Anda maksud dengan ou. Kata-kata yang tepat dari pesan kesalahan tergantung pada lingkungan pengembangan Anda, tetapi mungkin seperti "Tidak dapat menemukan simbol ou". Ini adalah kesalahan waktu kompilasi. Ada yang salah menurut aturan bahasa dan kompiler menemukannya. Untuk alasan ini, kesalahan waktu kompilasi sering disebut kesalahan sintaksis. Ketika kompilator menemukan satu atau lebih kesalahan, ia menolak untuk menerjemahkan program ke dalam instruksi mesin virtual Java, dan sebagai konsekuensinya Anda tidak memiliki program yang dapat dijalankan. Anda harus memperbaiki kesalahan dan mengkompilasi lagi. Faktanya, kompilator cukup pilih-pilih, dan adalah umum untuk melewati beberapa putaran memperbaiki kesalahan waktu kompilasi sebelum kompilasi berhasil untuk pertama kalinya.

Jika kompiler menemukan kesalahan, itu tidak akan berhenti dan menyerah begitu saja. Ini akan mencoba melaporkan kesalahan sebanyak yang dapat ditemukan, sehingga Anda dapat memperbaiki semuanya sekaligus.

Terkadang, kesalahan membuat kompiler keluar jalur. Misalkan, misalnya, Anda lupa tanda kutip di sekitar string: System.out.println(Hello, World!). Kompiler tidak akan mengeluh tentang tanda kutip yang hilang. Sebagai gantinya, itu akan melaporkan "Tidak dapat menemukan simbol Halo". Sayangnya, kompilernya tidak terlalu pintar dan tidak menyadari bahwa Anda bermaksud menggunakan string. Terserah Anda untuk menyadari bahwa Anda perlu menyertakan string dalam tanda kutip.

Kesalahan pada baris kedua di atas adalah jenis yang berbeda. Program akan dikompilasi dan dijalankan, tetapi outputnya akan salah. Ini akan mencetak

    Hello, Word!
Ini adalah kesalahan run-time. Program ini secara sintaksis benar dan melakukan sesuatu, tetapi tidak melakukan apa yang seharusnya dilakukan. Karena kesalahan run-time disebabkan oleh kelemahan logis dalam program, mereka sering disebut kesalahan logika.

Kesalahan run-time khusus ini tidak menyertakan pesan kesalahan. Itu hanya menghasilkan output yang salah. Beberapa jenis kesalahan run-time sangat parah sehingga menghasilkan pengecualian: pesan kesalahan dari mesin virtual Java. Misalnya, jika program Anda menyertakan pernyataan

    System.out.println(1 / 0);
Anda akan mendapatkan pesan kesalahan run-time "Pembagian dengan nol".

Selama pengembangan program, kesalahan tidak dapat dihindari. Begitu sebuah program lebih panjang dari beberapa baris, itu akan membutuhkan konsentrasi manusia super untuk memasukkannya dengan benar tanpa tergelincir satu kali pun. Anda akan menemukan diri Anda menghilangkan titik koma atau tanda kutip lebih sering daripada yang Anda inginkan, tetapi kompilator akan melacak masalah ini untuk Anda.

Kesalahan run-time lebih merepotkan. Kompilator tidak akan menemukannya—sebenarnya, kompilator akan dengan senang hati menerjemahkan program apa pun selama sintaksnya benar—tetapi program yang dihasilkan akan melakukan kesalahan. Ini adalah tanggung jawab pembuat program untuk menguji program dan menemukan kesalahan run-time.

**SELF CHECK**

16. Misalkan Anda menghilangkan karakter "" di sekitar Hello, World! dari HelloPrinter.
program jawa. Apakah ini kesalahan waktu kompilasi atau kesalahan waktu proses?
17. Misalkan Anda mengubah println menjadi printline pada program HelloPrinter.java. Apakah ini
kesalahan waktu kompilasi atau kesalahan waktu proses?
18. Misalkan Anda mengubah main menjadi hello pada program HelloPrinter.java. Apakah ini
kesalahan waktu kompilasi atau kesalahan waktu proses?
19. Saat Anda menggunakan komputer, Anda mungkin pernah mengalami program yang
"crash" (berhenti secara spontan) atau "digantung" (gagal menanggapi masukan Anda). Adalah
perilaku itu kesalahan waktu kompilasi atau kesalahan waktu proses?
20. Mengapa Anda tidak dapat menguji program untuk kesalahan run-time ketika memiliki kesalahan kompiler?

**Kesalahan Umum 1.2**
Kata-kata yang salah eja

Jika Anda secara tidak sengaja salah mengeja kata, maka hal-hal aneh mungkin terjadi, dan mungkin tidak selalu jelas dari pesan kesalahan apa yang salah. Berikut adalah contoh yang baik tentang bagaimana kesalahan ejaan sederhana dapat menyebabkan masalah:

<p align="center"><img src="img/code4.jpeg"></p><br>

Kelas ini mendeklarasikan sebuah metode yang disebut Main. Kompiler tidak akan menganggap ini sama dengan metode utama, karena Main dimulai dengan huruf besar dan bahasa Java peka huruf besar/kecil. Huruf besar dan kecil dianggap benar-benar berbeda satu sama lain, dan bagi kompiler Main tidak lebih cocok untuk main daripada hujan. Kompiler akan dengan senang hati mengkompilasi metode Main Anda, tetapi ketika mesin virtual Java membaca file yang dikompilasi, ia akan mengeluh tentang metode utama yang hilang dan menolak untuk menjalankan program. Tentu saja, pesan "metode utama yang hilang" akan memberi Anda petunjuk di mana mencari kesalahan.

Jika Anda mendapatkan pesan kesalahan yang tampaknya menunjukkan bahwa kompiler atau mesin virtual berada di jalur yang salah, periksa ejaan dan kapitalisasi. Jika Anda salah mengeja nama simbol (misalnya, ou alih-alih keluar), kompilator akan menghasilkan pesan seperti "tidak dapat menemukan sym bol ou". Pesan kesalahan itu biasanya merupakan petunjuk bagus bahwa Anda membuat kesalahan ejaan.

---
### **1.7 Problem Solving: Algorithm Design (Pemecahan Masalah: Desain Algoritma)** <br><br>
Anda akan segera belajar bagaimana memprogram perhitungan dan pengambilan keputusan di Java. Tetapi sebelum kita melihat mekanisme penerapan perhitungan di bab berikutnya, mari kita pertimbangkan bagaimana Anda dapat menjelaskan langkah-langkah yang diperlukan untuk menemukan solusi dari suatu masalah.<br><br>

**1.7.1 Konsep Algoritma**
Anda mungkin telah menemukan iklan yang mendorong Anda untuk membayar layanan terkomputerisasi mencocokkan Anda dengan pasangan cinta. Memikirkan bagaimana ini bisa berhasil. Anda mengisi formulir dan kirimkan. Yang lain melakukan hal yang sama. Data diproses oleh program komputer. Apakah masuk akal untuk asumsikan bahwa komputer dapat melakukan tugasmenemukan pasangan terbaik untuk Anda? Misalkan Anda adik laki-laki, bukan komputer, memiliki semua formulir di mejanya. Instruksi apa yang bisa Anda berikan? memberinya? Anda tidak bisa mengatakan, “Temukan yang paling tampan orang yang suka inline skating dan browsing internet”. Tidak ada standar objektif untuk ketampanan, dan pendapat saudaramu (atau itu program komputer yang menganalisis foto calon mitra) kemungkinan akan berbeda dari milik Anda. Jika Anda tidak dapat memberikan instruksi tertulis kepada seseorang untuk menyelesaikannya masalah, tidak mungkin komputer secara ajaib dapat menemukan solusi yang tepat. Itu komputer hanya dapat melakukan apa yang Anda perintahkan. Itu hanya melakukannya lebih cepat, tanpa mendapatkan bosan atau lelah.

Oleh karena itu, layanan pembuatan jodoh yang terkomputerisasi tidak dapat menjamin untuk menemukanpasangan yang optimal untuk Anda. Sebagai gantinya, Anda mungkin disajikan dengan serangkaian calon mitra yang memiliki minat yang sama dengan Anda. Itu adalah tugas yang program computer dapat memecahkan.

Agar program komputer memberikan jawaban atas masalah yang menghitung
jawaban, itu harus mengikuti urutan langkah-langkah yang
- Jelas
- Dapat dijalankan
- Mengakhiri

Urutan langkah tidak ambigu ketika ada instruksi yang tepat tentang apa yang harus dilakukan pada setiap langkah dan kemana harus pergi selanjutnya. Tidak ada ruang untuk menebak atau pendapat pribadi. Sebuah langkah dapat dieksekusi ketika itu dapat dilaksanakan dalam praktek. Misalnya, komputer dapat mencantumkan semua orang yang memiliki hobi yang sama dengan Anda, tapi itu tidak bisa memprediksi siapa yang akan menjadi pasangan seumur hidup Anda. Akhirnya, urutan langkah berakhir jika pada akhirnya akan berakhir. Sebuah program yang terus bekerja tanpa memberikan jawaban adalah jelas tidak berguna.

Urutan langkah yang tidak ambigu, dapat dieksekusi, dan diakhiri disebut algoritma. Meskipun tidak ada algoritme untuk menemukan pasangan, banyak masalah memiliki algoritme untuk diselesaikan mereka. Bagian berikutnya memberikan contoh.<br><br>

**1.7.2 Algoritma untuk Memecahkan Masalah Investasi**

Pertimbangkan masalah investasi berikut:<br>
Anda memasukkan $10.000 ke dalam rekening bank yang menghasilkan bunga 5 persen per tahun. Berapa banyak tahun yang diperlukan agar saldo akun menjadi dua kali lipat dari aslinya?

Bisakah Anda memecahkan masalah ini dengan tangan? Tentu, Anda bisa. Anda mengetahui keseimbangannya sebagai berikut:

<p align="center"><img src="img/tabel2.jpeg"></p><br>

Anda terus berjalan sampai saldo setidaknya $20.000. Kemudian angka terakhir di tahun ini kolom adalah jawabannya.

Tentu saja, melakukan perhitungan ini sangat membosankan bagi Anda atau adik laki-laki Anda. Tetapi komputer sangat pandai melakukan perhitungan berulang dengan cepat dan tanpa cacat. Yang penting bagi komputer adalah deskripsi langkah-langkah untuk menemukan solusi. Setiap langkah harus jelas dan tidak ambigu, tidak memerlukan tebak-tebakan. Berikut adalah deskripsi seperti itu:<br>
Setel tahun ke 0, saldo ke 10.000.

<p align="center"><img src="img/tabel3.jpeg"></p>

Ketika saldo kurang dari $20,000
Tambahkan 1 ke tabel tahun.
Tetapkan bunga ke saldo x 0,05 (yaitu, bunga 5 persen).
Tambahkan bunga ke saldo

<p align="center"><img src="img/tabel4.jpeg"></p>
Laporan tahun sebagai jawabannya.

Langkah-langkah ini termasuk dalam bahasa yang belum dapat dipahami oleh komputer, tapi kamu akan segera belajar bagaimana merumuskannya dalam Java. Deskripsi ini disebut dengan pseudocode. Kami membahas aturan untuk menulis pseudocode di bagian selanjutnya.<br><br>

**1.7.3 Pseudocode**

Tidak ada persyaratan ketat untuk pseudocode karena dibaca oleh manusia,bukan program komputer. Berikut adalah jenis-jenis pernyataan pseudocode dan bagaimana kita akan menggunakan penerapannya dalam buku ini:

- Gunakan pernyataan seperti berikut ini untuk menjelaskan bagaimana suatu nilai ditetapkan atau diubah:
biaya total = harga beli + biaya operasi
Kalikan nilai saldo dengan 1,05.
Hapus karakter pertama dan terakhir dari kata.
- Jelaskan keputusan dan pengulangan sebagai berikut:
Jika total biaya 1 < total biaya 2<br>
Ketika saldo kurang dari $20,000<br>
Untuk setiap gambar dalam urutan<br>
Gunakan lekukan untuk menunjukkan pernyataan mana yang harus dipilih atau diulang:
Untuk setiap mobil<br>
biaya operasi = 10 x biaya bahan bakar tahunan<br>
biaya total = harga beli + biaya operasi<br>
Di sini, lekukan menunjukkan bahwa kedua pernyataan harus dieksekusi untuk setiap mobil.
- Tunjukkan hasil dengan pernyataan seperti:<br>
Pilih mobil1.<br>
Laporkan tahun sebagai jawabannya.<br><br>

**1.7.4 Dari Algoritma ke Program**

Di Bagian 1.7.2, kami mengembangkan pseudocode untuk menemukan berapa lama waktu yang dibutuhkan untuk menggandakan investasi. Mari kita periksa kembali bahwa pseudocode mewakili suatu algoritma itu . adalah bahwa pseudocode itu jelas, dapat dieksekusi, dan diakhiri.

Pseudocode kami jelas. Ini hanya memberi tahu cara memperbarui nilai di setiap langkah. Pseudocode dapat dieksekusi karena kami menggunakan tingkat bunga tetap. Apakah kami mengatakan untuk menggunakan tingkat bunga aktual yang akan dibebankan di tahun-tahun mendatang, dan bukan tingkat bunga tetap 5 persen per tahun, instruksi tidak akan dapat dieksekusi. Tidak ada jalan bagi siapa pun untuk mengetahui berapa tingkat bunga di masa depan. Ini membutuhkan sedikit berpikir untuk melihat bahwa langkah-langkahnya berakhir: Dengan setiap langkah, keseimbangan naik setidaknya $ 500, jadi akhirnya harus mencapai $ 20.000.

Oleh karena itu, kami telah menemukan algoritme untuk menyelesaikan masalah investasi kami, dan kami tahu kami dapat menemukan solusinya dengan memprogram komputer. Keberadaan algoritma adalah prasyarat penting untuk memprogram tugas. Anda harus terlebih dahulu algoritma untuk tugas anda sebelum Anda memulai pemrograman (lihat gambar 8). Dalam bab-bab berikutnya, Anda akan mempelajari cara mengekspresikan algoritme dalam bahasa Java.

<p align="center"><img src="img/gambar8.jpeg"></p><br>

**SELF CHECK**

21. Misalkan tingkat bunga adalah 20 persen. Berapa lama waktu yang dibutuhkan agar investasi menjadi dua kali lipat?
22. Misalkan operator ponsel Anda menagih Anda $29,95 hingga 300 menit
panggilan, dan $0,45 untuk setiap menit tambahan, ditambah pajak dan biaya 12,5 persen. Memberi
algoritma untuk menghitung biaya bulanan dari sejumlah menit tertentu.
23. Perhatikan pseudocode berikut untuk menemukan foto paling menarik dari
urutan foto:
Pilih foto pertama dan beri nama "yang terbaik sejauh ini".<br>
Untuk setiap foto dalam urutan<br>
Jika itu lebih menarik daripada "terbaik sejauh ini"<br>
 Buang "yang terbaik sejauh ini".<br>
 Sebut foto ini "yang terbaik sejauh ini".<br>
Foto yang disebut "yang terbaik sejauh ini" <br>
adalah foto paling menarik dalam urutan itu.
Apakah ini algoritma yang akan menemukan foto paling menarik?
24. Misalkan setiap foto di Self Check 23 memiliki label harga. Berikan algoritma untuk menemukan foto yang paling mahal.
25. Misalkan Anda memiliki urutan acak kelereng hitam dan putih dan ingin
atur ulang sehingga kelereng hitam dan putih dikelompokkan bersama. Mempertimbangkan
algoritma ini:
Ulangi sampai terurut<br>
Temukan kelereng hitam pertama yang didahului oleh kelereng putih, dan alihkan.<br>
Apa yang dilakukan algoritme dengan urutan ●❍●●? Sebutkan langkah-langkahnya
sampai algoritma berhenti.
26. Misalkan Anda memiliki urutan acak kelereng berwarna. Pertimbangkan kode semu ini:
Ulangi sampai terurut<br>
Temukan kelereng pertama yang didahului oleh kelereng dengan warna berbeda, dan ganti.<br>
Mengapa ini bukan algoritma?<br><br>

**BAGAIMANA 1.1**

**Menjelaskan algoritma dengan Pseudocode**

Ini adalah yang pertama dari banyak cara bagian dalam buku ini yang memberikan Anda langkah-demi-langkah prosedur untuk melaksanakan tugas-tugas penting dalam mengembangkan program komputer.

Sebelum Anda siap untuk menulis sebuah program di Java, Anda perlu mengembangkan metode algorithma untuk tiba di solusi untuk masalah tertentu menggambarkan algoritma di pseudocode urutan langkah-langkah yang tepat dirumuskan dalam bahasa Inggris untuk menggambarkan, kami akan merancang sebuah algoritma untuk masalah ini:

**Pernyataan masalah** Anda memiliki pilihan untuk membeli salah satu dari dua mobil. Satu lebih hemat bahan bakar daripada yang lain, tetapi juga lebih mahal. 
Anda tahu harga dan efisiensi bahan bakar (dalam mil per galon, mpg) dari kedua mobil. Anda berencana untuk menyimpan mobil selama sepuluh tahun. Asumsikan harga $4 per galon gas dan penggunaan 15.000 mil per tahun. Anda akan membayar tunai untuk mobil dan tidak khawatir tentang biaya pembiayaan. Mobil mana yang lebih baik?

- **Langkah 1** Tentukan input dan output. 

Dalam contoh soal kami, kami memiliki input ini:

• **Harga beli1** dan **efisiensi bahan bakar1**, harga dan efisiensi bahan bakar (dalam mpg) mobil pertama.

• **Harga beli2** dan **efisiensi bahan bakar2**, harga dan efisiensi bahan bakar mobil kedua.

Kita hanya ingin tahu mobil mana yang lebih baik dibeli. Itu adalah keluaran (output) yang diinginkan.

- **Langkah 2**	Memecah masalah menjadi tugas-tugas yang lebih kecil. 

Untuk setiap mobil, kita perlu mengetahui total biaya mengemudinya. Mari kita lakukan perhitungan ini secara terpisah untuk setiap mobil. Setelah kita memiliki total biaya untuk setiap mobil, kita dapat memutuskan mobil mana yang lebih baik.

Total biaya untuk setiap mobil adalah **harga beli + biaya operasional**.

Kami mengasumsikan penggunaan konstan dan harga gas selama sepuluh tahun, sehingga biaya operasi tergantung pada biaya mengemudi mobil selama satu tahun.

Biaya operasi adalah **10 x biaya bahan bakar tahunan**.
Biaya bahan bakar tahunan adalah **harga per galon x bahan bakar tahunan yang dikonsumsi**.

Bahan bakar tahunan yang dikonsumsi adalah **jarak tempuh tahunan / efisiensi bahan bakar**. Misalnya, jika Anda mengendarai mobil sejauh 15.000 mil dan efisiensi bahan bakarnya 15 mil/galon, mobil tersebut mengkonsumsi 1.000 galon.

- **Langkah 3**  Jelaskan setiap subtugas dalam pseudocode. 

Dalam uraian Anda, atur langkah-langkahnya sehingga setiap nilai antara dihitung sebelum diperlukan dalam perhitungan lain. Misalnya, daftar langkah:
**biaya total = harga pembelian + biaya operasi**
Setelah Anda menghitung **biaya operasi**. 

Berikut adalah algoritma untuk memutuskan mobilmana yang akan dibeli:
   
Untuk setiap mobil, hitung total biaya sebagai berikut: 
   - konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar
   - biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan 
   - biaya operasional = 10 x biaya bahan bakar tahunan 
   - total biaya = harga beli + biaya operasional 

Jika total biaya mobil1 < total biaya mobil2<br>
Pilih mobil1. 

Lainnya<br>
Pilih mobil2.

- **Langkah 4** Uji pseudocode Anda dengan mengerjakan soal.

Kami akan menggunakan nilai sampel ini: 

Mobil 1: $25.000, 50 mil/galon 

Mobil 2: $20.000, 30 mil/galon 

Berikut adalah perhitungan biaya mobil pertama:
- konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar = 15000 / 50 = 300 
- biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan = 4 x 300 = 1200 
- biaya operasi = 10 x biaya bahan bakar tahunan = 10 x 1200 = 12000 
- total biaya = harga pembelian + biaya operasi = 25000 + 12000 = 37000 

Demikian pula, total biaya untuk mobil kedua adalah $ 40.000. Oleh karena itu, keluaran dari algoritma adalah memilih mobil 1.<br><br>

Contoh Kerja berikut menunjukkan bagaimana menggunakan konsep-konsep dalam bab ini dan langkah-langkah dalam Cara untuk memecahkan masalah lain. Dalam hal ini, Anda akan melihat bagaimana mengembangkan algoritme untuk meletakkan ubin dalam pola warna yang bergantian. Anda harus membaca Contoh yang Dikerjakan untuk meninjau apa yang telah Anda pelajari, dan untuk bantuan dalam mengatasi masalah lain.

Di bab-bab selanjutnya, contoh yang dikerjakan ditunjukkan dengan deskripsi singkat tentang masalah yang ditangani dalam contoh, ditambah pengingat untuk melihatnya di eTeks Anda atau mengunduhnya dari situs web pendamping buku di www.wiley.com/go/bjeo7. Anda akan menemukan kode apa pun yang terkait dengan Contoh yang Dikerjakan yang disertakan dengan kode pendamping buku untuk bab ini. Saat Anda melihat deskripsi Contoh yang Dikerjakan, buka contoh dan lihat dan jalankan kode untuk mempelajari bagaimana masalah tersebut diselesaikan.

---
**CONTOH YANG BERHASIL 1.1**

**Menulis Sebuah Algoritma untuk Memasang Ubin Lantai**

**Rumusan Masalah** Tulis sebuah algoritma untuk memasang ubin lantai kamar mandi persegi panjang dengan ubin hitam putih berselang-seling berukuran 4×4 inci. Dimensi lantai, diukur dalam inci, dengan kelipatan 4.

<p align="center"><img src="img/gambar9.jpeg"></p><br>

**Step 1** Tentukan input dan outputnya.

Inputnya merupakan dimensi lantai (panjang × lebar), diukur dengan inci. Outputnya merupakan lantai keramik.

**Step 2** Pecah masalah ke dalam tugas-tugas kecil.

Subtugas natural yaitu membuat satu baris ubin. Jika kamu bisa selesaikan tugas itu, maka kamu dapat menyelesaikan masalah dengan membuat satu baris di samping yang lain, mulai dari dinding, hingga kamu mencapai dinding yang berlawanan.

Bagaimana cara membuat baris tersebut? Mulailah dengan ubin di satu dinding. Jika tersebut berwarna putih, letakkan yang hitam di sebelahnya. Jika berwarna hitam, taruh ubin putih di sebelahnya. Terus lakukan hal tersebut hingga kamu mencapai dinding yang berlawanan. Baris akan berisi lebar / 4 ubin.

**Step 3** Jelaskan setiap tugas ke dalam pseudocode (kodesemu).

Dalam kodesemu, kamu ingin lebih tepat tentang di mana tepatnya ubin ditempatkan.
- Dalam kodesemu, kamu ingin lebih tepat tentang di mana tepatnya ubin ditempatkan.
- Ulangi lebar / 4 – 1 kali
- Tempatkan ubin di sebelah timur ubin yang ditempatkan sebelumnya. Jika ubin yang ditempatkan sebelumnya berwarna putih, pilih yang hitam; jika tidak, pilih yang putih.
- Kembali pada ubin di awal baris yang baru saja kamu tempatkan. Jika ada
ruang di selatan, letakkan ubin dengan warna yang berlawanan di bawahnya.

**Step 4** Uji kodesemu dengan mengerjakan suatu masalah.

Misalkan kamu ingin memasang ubin di area berukuran 20 × 12 inci. Langkah pertama adalah menempatkan ubin hitam di sudut barat laut.

<p align="center"><img src="img/gambar10.jpeg"></p><br>

Selanjutnya, tempatkan empat ubin secara bergantian hingga mencapai dinding timur. (lebar / 4 – 1 = 20 / 4 – 1 = 4).

<p align="center"><img src="img/gambar11.jpeg"></p><br>

Ada ruang di selatan. Kembali pada ubin di awal baris yang sudah selesai. Warnanya hitam. Tempatkan ubin putih di sebelah selatannya.

<p align="center"><img src="img/gambar12.jpeg"></p><br>

Lengkapi baris.

<p align="center"><img src="img/gambar13.jpeg"></p><br>

Masih ada ruang di selatan. Kembali pada ubin di awal baris yang sudah selesai. Warnanya putih. Tempatkan ubin hitam di selatannya.

<p align="center"><img src="img/gambar14.jpeg"></p><br>

Lengkapi baris.

<p align="center"><img src="img/gambar15.jpeg"></p><br>

Sekarang seluruh lantai terisi dan selesai.

---
### **RINGKASAN BAB**
---
**Mendefinisikan "program komputer" dan pemrograman**
- Komputer menjalankan instruksi yang sangat mendasar secara berurutan.
- Program komputer adalah urutan instruksi dan keputusan.
- Pemrograman adalah tindakan merancang dan mengimplementasikan program komputer.

---
**Penjelasan komponen-komponen komputer**
- Unit pemrosesan pusat (CPU) melakukan kontrol program dan data.
- Perangkat penyimpanan termasuk memori dan penyimpanan sekunder.

---
**Penjelasan proses penerjemahan bahasa tingkat tinggi ke kode mesin**
- Java awalnya dirancang untuk memprogram perangkat konsumen, tetapi pertama kali berhasil digunakan untuk menulis applet internet.
- Java dirancang agar aman dan portabel, bermanfaat bagi pengguna internet dan pelajar.
- Program java didistribusikan sebagai instruksi untuk mesin virtual, menjadikannya platform-independen.
- Java memiliki perpustakaan yang sangat besar, fokuslah untuk mempelajari bagian- bagian perpustakaan yang Anda butuhkan untuk proyek pemrograman Anda.

---
**Menjadi akrab dengan lingkungan pemrograman java Anda**
- Luangkan waktu untuk membiasakan diri dengan lingkungan pemrograman yang akan Anda gunakan untuk tugas kelas Anda.
- Editor adalah program untuk memasukkan dan memodifikasi teks, seperti program java.
- Java peka huruf besar-kecil, Anda harus berhati-hati dalam membedakan antara huruf besar dan huruf kecil.
- Kompiler java menerjemahkan kode sumber ke dalam file kelas yang berisi instruksi untuk mesin virtual java.
- Mengembangkan strategi untuk menyimpan salinan cadangan pekerjaan Anda sebelum masalah terjadi.

---
**Menggambarkan blok bangunan dari program sederhana**
- Kelas adalah blok bangunan dasar dari program java.
- Setiap aplikasi java berisi kelas dengan metode utama, ketika bintang aplikasi, instruksi dalam metode utama dijalankan.
- Setiap kelas berisi deklarasi metode, setiap metode berisi urutan instruksi.
- Sebuah metode dipanggil dengan menentukan metode dan argumennya.
- String adalah urutan karakter yang diapit tanda kutip.

---
**Mengklasifikasikan kesalahan program sebagai kompilasi - kesalahan waktu dan waktu berjalan**
- Kesalahan waktu kompilasi adalah pelanggaran aturan bahasa pemrograman yang dideteksi oleh kompiler.
- Kesalahan run waktu berjalan menyebabkan program mengambil tindakan yang tidak diinginkan oleh programmer.

---
**Tulis kode semu untuk algoritma sederhana**
- Algoritma untuk memecahkan masalah adalah urutan langkah yang jelas dapat dieksekusi dan diakhiri.
- Kode semu adalah deskripsi informal dari urutan langkah-langkah untuk memecahkan masalah.<br><br>
---

### **ITEM PERPUSTAKAAN STANDAR YANG DIPERKENALKAN DALAM BAB INI**<br><br>

java.io.PrintStream	

    print
    println

java.lang.System

    out



































































