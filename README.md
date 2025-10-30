# Lab6Web 

Nama: Fauzan Alfariz

NIM: 312410620

Kelas: TI 24 A4

# Tugas 1

````html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Refactor Layout Praktikum 4</title>

  <!-- Link Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
        rel="stylesheet" 
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
        crossorigin="anonymous">
</head>

<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Praktikum 6</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Artikel</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Container Utama -->
  <div class="container">

    <!-- Baris Heading -->
    <div class="row mb-4">
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 1</h5>
            <p class="card-text">Deskripsi singkat heading 1.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 2</h5>
            <p class="card-text">Deskripsi singkat heading 2.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 3</h5>
            <p class="card-text">Deskripsi singkat heading 3.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Baris Konten Utama dan Sidebar -->
    <div class="row">
      <!-- Konten Utama -->
      <div class="col-md-8">
        <div class="card mb-4">
          <div class="card-body">
            <h4 class="card-title">Konten Utama</h4>
            <p class="card-text">
              Ini adalah area untuk artikel atau isi utama website.
              Anda dapat menambahkan teks, gambar, atau elemen lain di sini.
            </p>
          </div>
        </div>
      </div>

      <!-- Sidebar -->
      <div class="col-md-4">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Sidebar</h5>
            <p class="card-text">
              Ini adalah bagian sidebar untuk link tambahan atau informasi lainnya.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Script Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
          crossorigin="anonymous"></script>
</body>
</html>
````

Kode HTML diatas meliputi:

1. **Responsivitas:**

   * Dengan menggunakan kelas Bootstrap seperti `col-md-4` dan `col-md-8`, layout ini responsif, artinya tampilan akan menyesuaikan dengan ukuran layar perangkat yang digunakan (desktop, tablet, atau smartphone).

2. **Penggunaan Kartu (Card):**

   * Setiap bagian heading dan konten utama ditampilkan dalam elemen `card` dari Bootstrap. Kartu ini memiliki struktur standar dengan judul, teks, dan body untuk menjaga desain tetap konsisten.

3. **Navbar Toggler:**

   * Pada navbar, terdapat tombol toggler (icon hamburger) yang hanya muncul pada layar kecil. Fungsinya untuk menampilkan menu navigasi ketika layar lebih sempit (seperti di smartphone).

4. **Penggunaan CSS dan JS dari CDN:**

   * Baik CSS maupun JS Bootstrap diimpor melalui CDN untuk memudahkan penggunaan tanpa perlu mendownload file secara lokal. Ini membantu mempercepat proses pengembangan dan memastikan versi terbaru digunakan.

Dengan struktur ini, website akan tetap teratur, mudah dibaca, dan adaptif pada berbagai ukuran layar.

Output:

<img width="1917" height="726" alt="image" src="https://github.com/user-attachments/assets/9c74e462-0aaa-48aa-85b5-6a3125b6f048" />

# Tugas 2

````html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Bootstrap</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="container mt-5">
  <h3 class="text-center mb-4">Form Kontak</h3>

  <form>
    <div class="mb-3">
      <label for="nama" class="form-label">Nama Lengkap</label>
      <input type="text" class="form-control" id="nama" placeholder="Masukkan nama Anda">
    </div>

    <div class="mb-3">
      <label for="email" class="form-label">Alamat Email</label>
      <input type="email" class="form-control" id="email" placeholder="nama@contoh.com">
    </div>

    <div class="mb-3">
      <label for="pesan" class="form-label">Pesan</label>
      <textarea class="form-control" id="pesan" rows="3" placeholder="Tulis pesan Anda di sini"></textarea>
    </div>

    <button type="submit" class="btn btn-primary">Kirim</button>
  </form>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
````


Pada kode di atas, terdapat sebuah **formulir kontak** yang dibangun menggunakan **Bootstrap**. Di bagian `<head>`, ada pengaturan karakter dan viewport untuk memastikan tampilan responsif di berbagai perangkat, serta penautan ke **CSS Bootstrap** untuk memberikan tampilan yang rapi dan konsisten.

Di dalam bagian **body**, terdapat sebuah **container** dengan margin atas (`mt-5`), yang memberikan jarak pada formulir agar tidak terlalu dekat dengan bagian atas halaman. Di dalam container ini, ada sebuah judul "Form Kontak" yang diletakkan di tengah menggunakan kelas `text-center`, dan diberi margin bawah (`mb-4`) agar terlihat lebih teratur.

Formulir itu sendiri terdiri dari tiga bagian utama. Pertama, ada input untuk **Nama Lengkap**, yang menggunakan elemen `<input>` dengan tipe teks. Kedua, ada input untuk **Alamat Email**, yang menggunakan tipe `email` agar dapat memvalidasi input yang dimasukkan. Terakhir, ada **textarea** untuk menulis **Pesan**. Setiap elemen formulir diberi kelas `form-control`, yang merupakan kelas Bootstrap untuk memberi gaya pada input dan textarea sehingga tampilannya lebih bersih dan rapi.

Formulir ini juga dilengkapi dengan tombol **Kirim** yang diberi kelas `btn btn-primary`, memberikan gaya tombol dengan warna biru khas dari Bootstrap.

Di bagian bawah, ada **script Bootstrap** yang diimpor dari CDN untuk memastikan bahwa elemen-elemen Bootstrap, meskipun tidak banyak digunakan dalam form ini, tetap dapat berfungsi jika diperlukan, seperti pada komponen interaktif lainnya.

Output:

<img width="1915" height="833" alt="image" src="https://github.com/user-attachments/assets/fc49bc5b-a1ac-41b5-b1a8-569f05f9c253" />

# Tugas 3

````html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Fauzan Alfariz</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <a class="navbar-brand" href="#">Fauzan Alfariz</a>
  </div>
</nav>

<!-- Tentang Saya -->
<div class="container my-5">
  <div class="row align-items-center">
    <div class="col-md-4">
      <img src="https://picsum.photos/300" alt="Foto Saya" class="img-fluid rounded">
    </div>
    <div class="col-md-8">
      <h2>Fauzan Alfariz</h2>
      <p>Mahasiswi Informatika yang tertarik dalam pengembangan web dan desain UI/UX. 
         Mempunyai semangat tinggi untuk belajar teknologi terbaru dan membangun website interaktif.</p>
    </div>
  </div>
</div>

<!-- Portfolio -->
<div class="container my-5">
  <h3 class="text-center mb-4">Portfolio Saya</h3>
  <div class="row">
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/400/200" class="card-img-top" alt="Project 1">
        <div class="card-body">
          <h5 class="card-title">Proyek 1</h5>
          <p class="card-text">Website profil menggunakan HTML dan Bootstrap.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/401/200" class="card-img-top" alt="Project 2">
        <div class="card-body">
          <h5 class="card-title">Proyek 2</h5>
          <p class="card-text">Form login interaktif dengan validasi JavaScript.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/402/200" class="card-img-top" alt="Project 3">
        <div class="card-body">
          <h5 class="card-title">Proyek 3</h5>
          <p class="card-text">Dashboard admin responsif menggunakan Bootstrap Grid.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
````


Pada kode ini, kita membuat halaman **portfolio pribadi** menggunakan **Bootstrap**. Di dalam bagian **head**, terdapat pengaturan untuk karakter encoding dan tampilan responsif, serta tautan ke file **CSS Bootstrap** yang digunakan untuk styling.

Bagian pertama adalah **Navbar** yang menggunakan kelas `navbar` dari Bootstrap. Navbar ini memiliki latar belakang biru (`bg-primary`) dengan nama "Fauzan Alfariz" yang ditampilkan di sebelah kiri sebagai nama pemilik portfolio. Biasanya, navbar ini akan diisi dengan menu navigasi, tapi di sini hanya ada nama saja.

Berikutnya, ada bagian **Tentang Saya** yang memuat informasi pribadi. Di bagian ini, terdapat gambar diri yang ditampilkan di sebelah kiri menggunakan elemen `<img>`, dan deskripsi tentang pemilik portfolio di sebelah kanan. Kelas `img-fluid` membuat gambar responsif, sedangkan kelas `rounded` memberikan efek sudut melengkung pada gambar.

Selanjutnya, ada bagian **Portfolio Saya**. Di sini terdapat tiga proyek yang ditampilkan menggunakan **kartu** (`card`) dari Bootstrap. Setiap kartu terdiri dari gambar proyek di bagian atas, judul proyek, dan deskripsi singkat tentang proyek tersebut. Ketiga kartu ini diatur dalam **grid** tiga kolom, dengan menggunakan kelas `col-md-4` dari Bootstrap, sehingga tampilan akan responsif di perangkat yang lebih kecil.

Di bagian bawah, terdapat **script Bootstrap** yang diperlukan untuk elemen interaktif (seperti dropdown, modal, dll) yang disertakan dalam Bootstrap, meskipun tidak digunakan banyak dalam halaman ini.

Output:

<img width="1909" height="1079" alt="image" src="https://github.com/user-attachments/assets/64c4f8e8-6f3f-4626-9834-c1f43330d5a7" />





