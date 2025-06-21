# Praktikum 1-9 Pemrograman Web 2

```bash
Dzikry Eza Yusuf (312310731) TI.23.A2

```

---

# Daftar Praktikum

*   **[Praktikum 1](#praktikum-1)**
*   **[Praktikum 2](#praktikum-2)**
*   **[Praktikum 3](#praktikum-3)**
*   **[Praktikum 4](#praktikum-4)**
*   **[Praktikum 5](#praktikum-5)**
*   **[Praktikum 6](#praktikum-6)**
*   **[Praktikum 7](#praktikum-7)**
*   **[Praktikum 8](#praktikum-8)**
*   **[Praktikum 9](#praktikum-9)**

---

# Praktikum 1

### Aktifkan Extensi

Buka `xampp -> apache -> config -> php.ini`

Hilangkan tanda `;` pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.

<img src="web2_p1/konfigurasi_php.png" width="max-content">

### Buka Browser

Ketik (http://localhost/lab11_ci/ci4/public) di browser. Akan muncul seperti gambar dibawah.

<img src="web2_p1/installcodeigniter.png" width="max-content">

### Menjalankan CLI

<img src="web2_p1/spark.png" width="max-content">

### Mengaktifkan Mode Debugging

`Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable 
CI_ENVIRINMENT menjadi development.`

<img src="web2_p1/parseerror.png" width="max-content">

### Memahami Konsep MVC (Model-View-Controller)

`Membuat Route Baru.
Tambahkan kode berikut di dalam Routes.php
$routes->get('/about', 'Page::about');
$routes->get('/contact', 'Page::contact');
$routes->get('/faqs', 'Page::faqs')`

**Lalu Ketik php spark routes**

<img src="web2_p1/sparkroutes.png" width="max-content">

### Membuat Controller

<img src="web2_p1/controller.png" width="max-content">

### Auto Routing

<img src="web2_p1/autorouting.png" width="max-content">

### Membuat View

<img src="web2_p1/halamanabout.png" width="max-content">

### Membuat Layout Web dengan CSS

<img src="web2_p1/hal_about.png" width="max-content">


# Praktikum 2

### Membuat Artikel dengan mengakses url (http://localhost:8080/artikel)

<img src="web2_p2/2.1.png" width="max-content">

### Menambahkan beberapa data pada database agar dapat di tampilkan datanya

<img src="web2_p2/2.2.png" width="max-content">

### Membuat menu admin dengan mengakses menu admin dengan url (http://localhost:8080/admin/artikel)

<img src="web2_p2/2.3.png" width="max-content">

### Membuat data artikel dengan menambahkan fungsi pada Controller Artikel dengan nama add(), lalu membuat view untuk form dengan nama form_add.php

<img src="web2_p2/2.4.png" width="max-content">

### Mengubah data dengan menambahkan fungsi baru pada Controller Artikel dengan nama edit().

<img src="web2_p2/2.5.png" width="max-content">

### Menghapus Data dengan menambahkan fungsi baru pada Controller Artikel dengan nama delete().

<img src="web2_p2/2.6 delete.png" width="max-content">

---

# Praktikum 3

### Membuat Layout Utama
`Buat folder layout di dalam app/views/`
`Buat file main.php di dalam folder layout dengan kode berikut: `
<img src="web2_p3/3.1.png" width="max-content">
<img src="web2_p3/3.2.png" width="max-content">

### Modifikasi File View
`Ubah app/Views/home.php agar sesuai dengan layout baru: `
<img src="web2_p3/3.3.png" width="max-content">

### Membuat Class View Cell 
`Buat folder Cells di dalam app/`
`Buat file ArtikelTerkini.php di dalam app/Cells/ dengan kode berikut: `
<img src="web2_p3/3.4.png" width="max-content">

### Membuat View untuk View Cell
`Buat folder components di dalam app/Views/ `
`Buat file artikel_terkini.php di dalam app/Views/components/ dengan kode berikut: `
<img src="web2_p3/3.5.png" width="max-content">
