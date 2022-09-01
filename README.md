Unix Command Line artinya baris perintah dalam *Unix* (sebuah sistem operasi komputer).

*Command Line Interface* (CLI) adalah antarmuka pengguna berbasis teks (UI) yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer. Setelah sistem komputer berjalan, CLI-nya terbuka di layar kosong dengan prompt perintah dan perintah dapat dimasukkan.

*Shell* adalah antarmuka pengguna yang bertanggung jawab untuk memproses semua perintah yang diketik di CLI. *Shell* membaca dan menafsirkan perintah dan menginstruksikan sistem operasi untuk melakukan tugas seperti yang diminta.

File *System* merupakan sebuah proses yang mengatur di mana dan bagaimana sebuah data disimpan dan diakses dalam *disk* penyimpanan. 

Di *Windows Shell*, kita dapat mengetikkan perintah dan itu akan berjalan di jendela prompt perintah hitam untuk melakukan tugas. Kita dapat mengetikkan satu perintah pada jendela CMD atau kombinasi perintah tergantung pada kebutuhan. Perintah akan berjalan dalam urutan di mana satu perintah akan dieksekusi setelah satu sama lain.

1. Materi Git

GIT adalah sebuah version control system yang telah digunakan oleh para developer untuk dapat mengembangkan software secara bersamaan.

Fungsi utama dari GIT adalah mengatur versi source code program dengan memberikan tanda baris serta code mana yang perlu ditambah ataupun diganti.

Perintah Dasar GIT

Untuk dapat mengetahui bagaimana cara menggunakan GIT, berikut ini beberapa perintah dasar dari GIT.

GIT init ini untuk membuat sebuah repository yang berada pada file lokal dimana nantinya file tersebut bernama .git.
GIT status ini untuk mengetahui status dari sebuah repository lokal.
GIT add ini untuk menambahkan file baru yang ada pada repository yang telah dipilih.
GIT commit ini untuk menyimpan perubahan yang telah dilakukan.
GIT push ini digunakan untuk mengirimkan perubahan file setelah di commit ke remote repository.
GIT branch ini melihat seluruh branch yang ada dalam repository.
GIT checkout ini dapat menukar branch yang aktif dengan branch yang telah dipilih.
GIT merge ini untuk menggabungkan branch yang aktif dan yang telah dipilih.
GIT clone ini dapat membuat salinan repository lokal.


# Berikut fitur-fitur yang ada pada GIT:

A. Version control system yang terdistribusi
GIT ini menggunakan pendekatan peer to peer, dimana tidak seperti Subversion atau SVN dimana menggunakan model client server.

B. GIT memungkinkan developer untuk memiliki branch kode
GIT disini memungkinkan para developer memiliki branch kode yang independent dan juga massive. Membuat, menghapus dan juga menggabungkan branch menjadi lebih cepat, lancar serta tidak membutuhkan waktu lama.

C. GIT bersifat atomic
Bersifat atomic merupakan sebuah tindakan yang akan benar-benar diselesaikan dengan lengkap atau bisa juga sama sekali gagal. 
Hal ini akan sangat penting karena pada beberapa version control system seperti CVS operasinya bersifat non atomic.
Bila ada operasi yang tergantung dan terkait dengan repository maka kondisi repository akan menjadi tidak stabil.

D. Media penyimpanan GIT berada dalam folder .git
Berbeda dari VCS lain seperti CVS dan atau SVN dimana metadata file disimpan dalam folder yang tersembunyi seperti .svn, .cvs, dan juga .etc.

E. GIT memiliki data model
GIT ini memiliki data model yang bisa membantu memastikan integritas cryptographic yang berada di dalam repository. Sehingga pada setiap kali sebuah file ditambahkan ataupun di commit, checksum nya akan diciptakan sama seperti retrieve melalui checksum nya juga.

F. GIT memiliki staging area atau index
Dengan adanya stagin area ini, para developer dapat memformat commit serta dapat membuatnya dapat di review sebelum benar diterapkan.

G. GIT sederhana dalam penggunaannya
Untuk dapat memulai Anda dapat membuat repository ataupun men checkout yang telah ada.

# Git dan GitHub Dasar
Git dan GitHub merupakan dua platform yang didirikan oleh satu perusahaan dengan tujuan sama serta fitur yang berbeda. Kedua platform ini sangat membantu pekerjaan programmer dalam menyusun kode script secara tim.
### Perintah Dasar Git
1. **git init** digunakan untuk membuat repositori baru.
2. **git status** digunakan untuk menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit.
3. **git add** bisa digunakan untuk menambahkan file ke index.
4. **git commit** digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. *Commit* menyimpan riwayat perubahan data pada file.
5. **git log** merupakan perintah yang akan menampilkan daftar commits yang ada di branch beserta detail-nya.
6. **git checkout** digunakan untuk mengembalikan kondisi file proyek seperti waktu yang dituju. Akan tetapi, ini bersifat temporer (sementara). Pengembalian ini tidak disimpan dalam database Git. Bisa dikatakan perintah **git checkout** sebagai perintah untuk mengecek kondisi file di setiap commit. Selain itu juga, perintah ini digunakan untuk berpindah dan membuat cabang. Ini bisa digunakan untuk membuat perubahan baru berdasarkan kode di masa lalu.
7. **git reset**, akan mengembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit beikutnya. Perintah ini memiliki tiga argumen atau opsi utama, yaitu:
   - **--soft** akan mengebalikan dengan kondisi file dalam keadaan staged.
   - **--mixed** akan mengebalikan dengan kondisi file dalam keadaan *modified*.
   - **--hard** akan mengebalikan dengan kondisi file dalam keadaan *commited*.
8. **git revert** akan mengembalikan file dengan tidak menghapus sejarah *commit*. Jika menggunakan **git reset**, *commit* terakhir akan hilang. *Revert* akan akan mengambil kondisi file yang ada di masa lalu, kemudian menggabungkannya dengan commit terakhir.
9. **git branch** bisa digunakan untuk me-*list*, membuat atau menghapus *branch*.
10. **git merge** digunakan untuk menggabungkan sebuah *branch* ke *branch* aktif.
11. **git config** digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll.
12. **git push** digunakan untuk mengirimkan perubahan ke *master branch* dari *remote repository* yang berhubungan dengan direktori kerja.
13. **git remote** akan membuat *user* terhubung ke *remote repository*.

## GitHub *Introduction*
GitHub merupakan layanan *cloud* yang berguna untuk menyimpan dan mengelola sebuah *project* yang dinamakan *repository*. Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-*install* sebuah *software* ke dalam perangkat keras. Hal ini memberikan keringanan penyimpanan komputer yang digunakan karena file *project* tersimpan oleh *cloud* GitHub. 

Konsep kerja GitHub pada dasarnya sama dengan Git yaitu dapat menulis *source code* secara individu atau tim. *User interface* yang tersedia pada GitHub lebih menarik dan mudah dipahami oleh pengguna awal. Pekerjaan secara tim, pengguna juga bisa melihat siapa penulis kode dan tanggal berapa kode tersebut dibuat.


2. Materi Html

HTML atau Hypertext Markup Language adalah bahasa markup yang digunakan untuk membuat sebuah halaman web. Isinya terdiri dari berbagai kode yang dapat menyusun struktur suatu website.

HTML terdiri dari kombinasi teks dan simbol yang disimpan dalam sebuah file. Dalam membuat file HTML, terdapat standar atau format khusus yang harus diikuti. Format tersebut telah tertuang dalam standar kode internasional atau ASCII (American Standard Code for Information Interchange). Mengenal Tag HTML, Elemen, dan Atribut Setelah mengetahui bagaimana sejarah dari HTML, sekarang Anda perlu tahu komponen-komponen yang terdapat pada HTML.

Secara umum HTML terdiri dari Tag, Elemen, dan Atribut.


3. Materi CSS

CSS adalah singkatan dari cascading style sheets, yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website. Dengan CSS, Anda bisa mengatur jenis font, warna tulisan, dan latar belakang halaman. CSS digunakan bersama dengan bahasa markup, seperti HTML dan XML untuk membangun sebuah website yang menarik dan memiliki fungsi yang berjalan baik.CSS juga berguna untuk mengatasi keterbatasan HTML dalam mengatur format halaman website.

4. Materi Algoritma

    # materi teori algoritma yang bertemakan tentang :

Algoritma
    Algoritma adalah urutan langkah-langkah logis penyelesaian masalah yang disusun secara sistematis dan logis. Kata Logis merupakan kata kunci dalam Algoritma. Langkah-langkah dalam Algoritma harus logis dan harus dapat ditentukan bernilai salah atau benar.

Ciri-ciri penting dalam algoritma

Algoritma harus berhenti setelah mengerjakan sejumlah langkah terbatas.
Setiap langkah harus didefinisikan dengan tepat dan tidak berarti-dua (Ambiguitas).
Algoritma memiliki nol atau lebih masukkan.
Algoritma memiliki nol atau lebih keluaran.
Algoritma harus efektif (setiap langkah harus sederhana sehingga dapat dikerjakan dalam waktu yang masuk akal).

Pseudocode
    Pseudocode adalah deskripsi dari algoritma pemrograman komputer yang menggunakan struktur sederhana dari beberapa bahasa pemograman tetapi bahasa tersebut hanya ditujukan agar dapat dibaca manusia. Biasanya yang ditulis dari pseudocode adalah variabel dan fungsi. Tujuan penggunaan utama dari pseudocode adalah untuk memudahkan manusia dalam memahami prinsip-prinsip dari suatu algoritma. Penggunaan pseudocode umumnya banyak kita temukan di buku-buku dan artikel-artikel tentang pemrograman yang membahas tentang algoritma tertentu. Kadang pula pseudocode kita temukan dalam merencanakan pengembangan suatu program komputer. Dalam pseudocode, tidak ada syntax standar yang resmi. Karena itu, pseudocode ini dapat kita terapkan dalam berbagai bahasa pemograman. Tentu saja harus kita sesuaikan setiap tahap dengan bahasa pemograman yang kita gunakan. Fungsi dari pseudocode mungkin sama dengan Flowchart. Perbedaannya terletak pada cara penyampaiannya. Pseudocode menggunakan kata-kata untuk menjelaskan suatu algoritma, sedangkan Flowchart menggunakan gambar.

Tipe Data
    Dalam algoritma, kita harus bisa menentukan tipe-tipe data yang sesuai digunakan dalam Penyelesaian masalah. Sehingga komputer dapat mengolah dan mendapatkan hasil yang sesuai Menurut kebutuhan data.

Ada beberapa tipe data yang harus kita ketahui antara lain :
   a. Tipe data Char dan String Ini merupakan tipe data dasar, tipe data ini didefinisikan pada deklarsi var dibagian algoritma/program.

    b. Tipe Data Integer Merupakan tipe data bilangan bulat. Contoh: Byte 0…255 1 byte Word 0…65.555 1 byte Integer -32.768 s.d 32.767 2 byte Long Integer -2.147.483.648 4 byte

Variabel
    Tipe variabel menentukan nilai yang dapat disimpan variabel tersebut dan operator-operator apa yang dapat dikenakan padanya. Sebagai contoh, tipe integer hanya dapat menyimpan bilangan integer dan operator yang dapat dikenakan padanya antara lain operator penjumlahan, perkalian, dan sebagainya.

contoh variabel :

Bilangan/Numerik Bilangan/Numerik dibagi menjadi dua yaitu bilangan bulat/numerik dan bilangan real/pecahan.
Bilangan bulat memiliki 2 tipe yaitu Integer dan Long
Bilangan real memiliki 2 tipe yaitu Single dan Double
Karakter / String String adalah semua karakter yang ada dalam tabel ASCII, contoh : ‘a’…’z’…’0′…’9′. Operasi yang bisa dilakukan hanya operasi perbandingan saja. Tipe String ialah gabungan dari karakter, tipe string bisa digunakan untuk menyimpan data yang berupa untaian karakter.

Struktur Dasar Algoritma (Runtunan, Pengulangan, dan Seleksi)
    Runtunan(Sequence) Seleksi(Selection) 3.Pengulangan( Repetition)

    Runtunan(Sequence) -Sebuah runtutan terdiri dari satu atau lebih intruksi. -Intruksi dilaksanakan setelah intruksi sebelumnya dilaksanakan. -Urutan intruksi menentukan keadaan akhir algoritma. 1 2 3 4 A1 A2 A3 A4

    Seleksi(Selection) Adakalanya sebuah instruksi dikerjakan jika kondisi tertentu dipenuhi. Tiap–tiap instruksi akan diseleksi oleh kondisi, apabila instruksi memenuhi kondisi yang diminta, maka instruksi akan dijalankan.

    Pengulangan( Repetition) Kondisi yang dilaksanakan secara berulang-ulang.

Bagian-Bagian Algoritma (Judul, Deklarasi, dan Deskripsi)
    
    PROGRAM nama program {berisi judul algoritma, singkat dan jelas}

    DEKLARASI {sebagai tempat untuk mengenalkan nama atau variabel apa saja yang digunakan dan tipe datanya serta prosedur dan fungsi yang dipakai}

    ALGORITMA : {berisi langkah-langkah penyelesaian masalah}

Array 1 Dimensi
    Array merupakan kumpulan dari nilai-nilai data yang bertipe sama dalam urutan tertentu yang menggunakan nama yang sama. Dengan menggunakan array, sejumlah variabel dapat memakai nama yang sama. Letak atau posisi dari elemen array ditunjukkan oleh suatu index

Array 2 Dimensi
    Pada bagian ini, ditunjukkan array berdimensi lebih dari satu, yang sering disebut dengan array berdimensi dua. Sering kali digambarkan/dianalogikan sebagai sebuah matriks. dimana indeks pertama menunjukan baris dan indeks kedua menunjukan kolom ILUSTRASI ARRAY 2 DIMENSI Gambar array berdimensi (baris x kolom = 3 x 4):

Sub Program (Prosedur dan Fungsi)
    Sub Algoritma adalah sebuah algoritma pendek yang ditulis terpisah dari Algoritma utama, dimana setiap saat dibutuhkan dapat dipanggil tanpa menulis ulang. Dalam pembuatan program Sub Algoritma disebut juga dengan Sub Program. Keuntungan lain dari Sub Program adalah bila dalam sebuah program terdapat proses tertentu yang sering digunakan dalam program, maka dengan adanya sub algoritma kita tidak perlu menuliskan proses tersebut berulang ulang, cukup memanggil sub program yang sudah disiapkan. Bentuk Sub Program dapat berupa sebuah Prosedur ataupun Fungsi, dan dalam setiap Prosedur atau Fungsi tersebut dapat dilewatkan sebuah Parameter agar Prosedur/ Fungsi tersebut mampu menerima inputan dari program utama.

Jenis Sub Program dalam Algoritma :

    PROCEDURE
Procedure adalah sebuah sub program yang dapat dipanggil sewaktu – waktu jika diperlukan oleh program utama. Sebuah procedure dapat dipanggil langsung oleh program utama ataupun dipanggil berdasarkan kondisi-kondisi tertentu. Sebuah procedure biasa tidak dapat menerima masukan dari program utama, jadi hanya dapat dipanggil saja. Jadi semua blok program yang diperlukan (dari input, proses, sampai output) harus diletakkan pada procedure, dan program utama hanya bertugas memanggil saja jika diperlukan.

    PARAMETER
Perlu diingat bahwa sebuah prosedur biasa tidak bisa menerima inputan nilai dari program utama (hanya bisa dipanggil saat diperlukan). Tetapi sebuah prosedur akan bisa menerima inputan dari program utama jika dilengkapi dengan sebuah PARAMETER. Parameter adalah variabel dalam sebuah prosedur atau fungsi yang gunanya untuk menampung nilai yang dikirimkan oleh program yang memanggil prosedur atau fungsi tersebut. PARAMETER dideklarasikan setelah nama prosedur, diikuti dengan jenis variabelnya.

    FUNCTION (FUNGSI)
Function hampir sama dengan prosedur, bedanya function hanya menghasilkan satu nilai output, dan sebuah function bisa mengembalikan nilai output yang dihasilkannya tersebut ke program utama(pemanggilnya).

