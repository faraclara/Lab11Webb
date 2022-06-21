Instruksi Praktikum

1. Persiapkan text editor misalnya VSCode.
2. Buka kembali folder dengan nama lab11_php_ci pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

Langkah-langkah Praktikum

1. Membuat Pagination
Pagination merupakan proses yang digunakan untuk membatasi tampilan yang panjang
dari data yang banyak pada sebuah website. Fungsi pagination adalah memecah
tampilan menjadi beberapa halaman tergantung banyaknya data yang akan ditampilkan
pada setiap halaman.
Pada Codeigniter 4, fungsi pagination sudah tersedia pada Library sehingga cukup
mudah menggunakannya.
Untuk membuat pagination, buka Kembali Controller Artikel, kemudian modifikasi
kode pada method admin_index seperti berikut.

gambar 1

Kemudian buka file views/artikel/admin_index.php dan tambahkan kode berikut
dibawah deklarasi tabel data.

gambar 2

Selanjutnya buka kembali menu daftar artikel, tambahkan data lagi untuk melihat
hasilnya.

Membuat Pencarian

Pencarian data digunakan untuk memfilter data.
Untuk membuat pencarian data, buka kembali Controller Artikel, pada method
admin_index ubah kodenya seperti berikut

gambar 3

Kemudian buka kembali file views/artikel/admin_index.php dan tambahkan form
pencarian sebelum deklarasi tabel seperti berikut:

gambar 4

Dan pada link pager ubah seperti berikut.\

gambar 5

Selanjutnya ujicoba dengan membuka kembali halaman admin artikel, masukkan kata
kunci tertentu pada form pencarian.

gambar 6

Upload Gambar
Menambahkan fungsi unggah gambar pada tambah artikel. Buka kembali Controller
Artikel, sesuaikan kode pada method add seperti berikut:


gambar 7

Kemudian pada file views/artikel/form_add.php tambahkan field input file seperti
berikut

gambar 8

Dan sesuaikan tag form dengan menambahkan ecrypt type seperti berikut.

Ujicoba file upload dengan mengakses menu tambah artikel.

gambar akhir
