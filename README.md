# Lab5Web
# Pengenalan Javascript
* Dalam HTML, kode Javascript disisipkan di antara tag <script> dan </script>.
* Script dapat diletakkan pada tag <head> atau <body> , atau dapat juga diletakkan pada keduanya.
* Javascript juga dapat diletakkan pada file external.

Perhatikan contoh berikut ini.

Persiapan membuat dokumen HTML seperti di bawah ini.

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/html_js.JPG)

Pada contoh di atas terdapat fungsi-fungsi yang menampilkan output seperti:

* Fungsi document.write() menampilkan output ke dokumen HTML;
* Fungsi console.log() menampilkan output ke console javascript.

Dan hasilnya seperti di bawah ini.

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/java_script.JPG)

# Pemakaian Alert Pada Javascript
Ada 4 cara untuk menampilkan output pada Javascript, salah satunya adalah dengan menggunakan fungsi alert().
* Fungsi alert() merupakan sebuah fungsi yang akan menampikan jendela dialog.
* Jendela dialog merupakan jendela yang digunakan untuk berinteraksi dengan pengguna.
* Dialog alert() biasanya digunakan untuk menampilkan sebauh pesan peringatan atau informasi.
* Fungsi alert() berada dalam objek window.

Contohnya seperti berikut.

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/html_alertbox.JPG)

Hasilnya :

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/page_alertbox.JPG)

Dialog alert() memiliki satu perameter yang harus diberikan, yaitu: teks yang akan ditampilkan pada dialog.

Pada contoh di atas, kita memberikan teks "ini merupakan pesan untuk anda".

# Pemakaian Method dalam Objek

* Objek adalah sebuah variabel yang menyimpan nilai (properti) dan fungsi (method).
* Method adalah perilaku dari objek (fungsi).
* Cara membuat method di dalam objek adalah dengan cara mengisi nilai (value) dengan sebuah fungsi.
* Cara mengakses method dari objek yaitu menggunakan tanda titik atau dot (.), lalu diikuti dengan nama method.

Perhatikan contoh di bawah ini.

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/html_pemakaianmethod.JPG)

Untuk method harus menggunakan tanda kurung. Ini menyatakan kalau kita ingin mengeksekusi fungsi.

Hasilnya:

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/pemakaian_method.JPG)

Pemakaian Prompt
Pemakaian prompt juga merupakan salah satu macam jendela dialog pada Javascript.
Dialog prompt() berfungsi untuk mengambil sebuah inputan dari pengguna.
Dialog prompt() akan mengembalikan sebuah nilai string dari apa yang diinputkan oleh pengguna.
Contoh:

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/html_pemakaianprompt.JPG)

Hasilnya:

Kita disuruh menginput nama pada kolom field, seperti ini.

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/page_prompt.JPG)

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/page_prompt2.JPG)

Lalu, akan muncul teks seperti ini:

![imag](https://github.com/fdlhrauf/Lab5Web/blob/main/Images/hasil_prompt.JPG)

Dialog prompt() memiliki beberapa parameter yang harus diberikan:

Teks yang akan ditampilkan pada form;
Nilai default untuk field input.
Pada contoh di atas, kita memberikan nilai default-nya berupa string dengan tanda petik dan teks "masukkan nama anda".

Perbedaan dialaog alert() dan dialaog prompt() adalah waktu yang tepat dalam penggunaan alert() dan prompt():

Saat kita hanya ingin menampilkan informasi saja, maka gunakan alert().
Dan apabila kita ingin mengambil data teks dari pengguna, maka gunakan prompt().
Pemakaian Fungsi dan Cara Memanggilnya
Fungsi di dalam Javascript adalah sebuah objek. Karena memiliki properti dan juga method.
Ada 4 cara yang bisa kita lakukan untuk membuat fungsi di Javascript:
Menggunakan cara biasa;
Menggunakan ekspresi;
Menggunakan tanda panah (=>);
dan menggunakan Constructor.
Contohnya:

enter image description here

Contoh di atas merupakan cara membuat fungsi dengan menggunakan cara biasa.

Cara Memanggil Fungsi
Memanggil fungsi dengan menuliskan nama fungsinya. Contohnya seperti kode di atas, berarti memanggil fungsi dengan nama fungsi pesan().
Memanggil fungsi melalui atribut event pada HTML. Seperti contoh kode di atas, memanggil fungsi dengan event onload yang merupakan event ketika element atau halaman di buka.
Jadi, pada contoh di atas memanggil fungsi dengan cara nomer 2 (dua).

Operasi Dasar Aritmatika pada Javascript
Operator adalah simbol yang digunakan untuk melakukan operasi pada suatu nilai dan variabel.
Operator Aritmatika merupakan operator yang biasa digunakan pada operasi perhitungan matematis.
Operator aritmatika terdiri dari:
Penjumlahan, simbolnya ( + )
Pengurangan, simbolnya ( - )
Perkalian, simbolnya ( * )
Pemangkatan, simbolnya ( ** )
Pembagian, simbolnya ( / )
Modulus, simbolnya ( % )
Contoh:

enter image description here

Pada contoh kode di atas, menggunakan fungsi, dan untuk melakukan perhitungan aritmatika, kita menggunakan variabel. Variabel pada kode di atas adalah val1 dan val2. Untuk val1 = 9 dan val2 = 4.

Kemudian pada bagian tag <body> terdapat event pada Javascript, yaitu onclick yang merupakan event jika sebuah element html di klik.

Dan hasilnya:

enter image description here

Nah, pada gambar di atas dinamakan event onclick dengan value "aritmethic, apabila kita meng-klik value tersebut, maka akan muncul hasil seperti di bawah ini:

enter image description here

Coba perhatikan pada operator modulus ( % )

Operator modulus adalah operator untuk menghitung sisa bagi. Pada contoh di atas 9 dibagi 4 adalah 2, maka sisanya adalah 1.

Seleksi Kondisi (if - else)
if - else merupakan salah satu bentuk percabangan pada Javascript.
Percabangan if - else merupakan percabangan yang memiliki dua blok pilihan. Pilihan pertama untuk kondisi benar, dan pilihan kedua untuk kondisi salah (else).
Perhatikan contoh di bawah ini.

enter image description here

Pada kode di atas menjunjukkan bahwa, pada kondisi if, yang menginput nilai lebih dari sama dengan 60, maka akan lulus, sedangkan pada kondisi else, di bawah nilai 60 maka hasilnya tidak lulus.

Dan ini contoh apabila kita menginput nilai 80

enter image description here

enter image description here

Hasilnya akan lulus.

enter image description here

Sedangkan apabila kita menginput nilai di bawah 60, maka:

enter image description here

hasilnya menunjukkan tidak lulus.

enter image description here

Penggunaan Operator switch
Salah satu bentuk peracabangan selain if - else yaitu percabangan swtich/case.
Percabangan switch/case adalah bentuk lain dari percabangan if/else/if.
Pada percabangan switch kita dapat membuat blok kode (case) sebanyak yang diinginkan di dalam blok switch.
Setiap case harus diakhiri dengan break. Khusus untuk default, tidak perlu diakhiri dengan break karena dia terletak di bagian akhir.
Pemberian break bertujuan agar program berhenti mengecek case berikutnya saat sebuah case terpenuhi.
Contohnya:

enter image description here

enter image description here

Pada kode program di atas, kita akan menginput nilai 1-5.

Dan ini kita menggunakan event onclick.

enter image description here

Kemudian apabila di klik, maka akan muncul tampilan seperti ini, misalnya kita akan menginput nilai 4.

enter image description here

Maka, hasilnya akan seperti ini.

enter image description here

Pembuatan Form Input
Pada pembuatan form input Javascript, hampir sama dengan pembuatan form pada HTML.

Contohnya seperti berikut.

enter image description here

Hasilnya, kita disuruh menginput pada form yang tersedia, seperti di bawah ini.

enter image description here

Pembuatan Form Button Pada objek document
Objek document adalah model dari dokumen HTML. Objek ini berisi kumpulan fungsi dan atribut berupa objek dari elemen HTML.
Di dalam objek document, terdapat fungsi-fungsi dan atribut yang bisa kita gunakan untuk memanipulasi dokumen HTML.
Perhatikan contoh kode program berikut ini.

enter image description here

Pada kode di atas, terdapat fungsi document.bgColor yang digunakan untuk memberikan warna pada background page, sedangkan fungsi document.fgColor digunakan untuk memberikan warna untuk tulisan pada page.

Selain itu, kode di atas merupakan kode untuk membuat sebuah form, dengan input type = "button", dimana form tersebut menggunakan event Javascript, yaitu onclick yang apabila kita meng-klik <value> nya, maka akan berubah sesuai dengan atribut yang diberikan pada fungsinya.

Dan ini hasilnya defaultnya:

enter image description here

Dan seperti ini tampilan apabila kita meng-klik tombol button "Latar Belakang Hijau.

enter image description here

Tampilan Latar Belakang Putih

enter image description here

Tampilan "Teks Kuning"

enter image description here

Tampilan "Teks Biru

enter image description here

HTML DOM
DOM merupakan singkatan dari Document Object Model. Artinya, dokumen (HTML) yang dimodelkan dalam sebuah objek.
Objek dari dokumen ini menyediakan sekumpulan fungsi dan atribut/data yang bisa kita manfaatkan dalam membuat program Javascript. Inilah yang disebut API (Application Programming Interface).
Perhatikan contoh berikut ini.

enter image description here

Pada contoh di atas merupakan sebuah program untuk membuat daftar menu makanan dengan menggunakan checkbox, yang apabila kita men-ceklist pada daftar menu tersebut, maka akan muncul total harga yang harus di bayar.

Dan pada kode di atas, terdapat beberapa fungsi:

fungsi document.getElementById() yang merupakan fungsi untuk memilih elemen berdasarkan atribut id
fungsi parseInt merupakan fungsi untuk mengubah String menjadi Integer atau mengubah kebilangan bulat. Artinya jika bilangan didalamnya mengandung desimal maka akan dikonversikan ke bilangan bulat.
Dan hasilnya seperti ini.

enter image description here

Misalnya kita men-ceklist menu makanan "Ayam Goreng dan "Tempe Goreng dengan masing-masing harga yang sudah ditentukan, maka akan muncul total harga yang harus dibayar, yaitu Rp. 5.500

enter image description here

Tugas Praktikum 5
Buat script untuk melakukan validasi pada isian form.

Jawaban:
Persiapan membuat dokumen HTML terlebih dahulu dan dilanjut menambahkan kode seperti di bawah ini.
enter image description here

Penjelasan kode
Di sini kita memerintahkan untuk menjalankan function validasi() saat form di submit. onSubmit=”validasi()”

enter image description here

dimana function validasi() sudah kita buat untuk mengecek inputan.

enter image description here

kita menangkap nilai value dari form input. dan memasukkannya ke dalam variabel.

enter image description here

dan kemudian mengecek masing-masing variabel.

enter image description here

Jika nama, email dan alamat di isi. atau tidak kosong. maka akan di kembalikan nilai TRUE pada form agar dapat di teruskan. jika tidak maka tampilkan pesan alert yang menampilkan “Anda harus mengisi data dengan lengkap !”.

Kemudian tambahkan CSS.
enter image description here

Dan hasilnya seperti berikut ini.
enter image description here














