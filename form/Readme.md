# Form in HTML

## Pengertian Form (formulir) di HTML
Formulir dalam HTML digunakan untuk mengumpulkan data dari pengguna. Formulir biasanya digunakan pada halaman web untuk menerima input seperti teks, pilihan, dan file yang nantinya dapat diproses oleh server.

## Elemen Utama Formulis
Berikut adalah elemen-elemen utama yang digunakan untuk membuat formulir di HTML:

|Elemen      |Fungsi                                                          |
|------------|----------------------------------------------------------------|
|`<form>`    |Elemen utama untuk membuat formulir.                            |
|`<input>`   |Digunukan untuk menerima berbagai jenis input dari pengguna.    |
|`<textarea>`|Digunakan untuk menerima input teks yang panjang.               |
|`<select>`  |Membuat dropdown pilihan.                                       |
|`<option>`  |Menentukan pilihan dalam elemen `<select>`.                     |
|`<label>`   |Menyediakan label untuk elemen input, meningkatkan aksesbilitas.|
|`<button>`  |Digunakan untuk membuat tombol dalam formulir.                  |
|`<fieldset>`|Mengelompokkan elemen formulir secara logis.                    |
|`<legend>`  |Memberikan judul pada kelompok elemen dalam `<fieldset>`.       |

## Atribut Penting pada Elemen `<form>`
Berikut adalah beberapa atribut yang sering digunakan pada elemen `<form>`:

|Atribut     |Fungsi                                                                   |
|------------|-------------------------------------------------------------------------|
|`action`    |URL tujuan untuk mengirimkan data formulir.                              |
|`method`    |Metode pengiriman data: `GET` atau `POST`.                               |
|`enctype`   |Menentukan tipe enkripsi data, seperti `multipart/form-data`.            |
|`novalidate`|Menonaktifkan validasi formulir bawaan browser.                          |
|`target`    |Menentukan di mana hasil akan ditampilkan, seperti `_blank` atau `_self`.|

## Jenis Input pada Formulir
Elemen `<input>` memiliki banyak jenis input berdasarkan atribut `type`:

|Tipe Input|Fungsi                                           |
|----------|-------------------------------------------------|
|`text`    |Inut teks satu baris.                            |
|`password`|Input teks yang disembunyikan (untuk kata sandi).|
|`email`   |Input untuk alaman email.                        |
|`number`  |Input untuk angka.                               |
|`date`    |Input untuk tanggal.                             |
|`file`    |Input untuk mengunggah file.                     |
|`radio`   |Pilihan tunggal dalam grup.                      |
|`checkbox`|Pilihan jamak.                                   |
|`submit`  |Tombol untuk mengirimkan formulir.               |
|`reset`   |Tombol untuk mengatur ulang formulir.            |

## Contoh Formulir Sederhana
Ada pada file form.html yaa

## Studi Kasus: Formulir Registrasi Pengguna
Ada pada file form.html yaa

## Catatan Penting
1. Pastikan untuk selalu menggunakan atribut name pada elemen input agar data dapat dikirimkan.
2. Gunakan elemen `<label>` untuk meningkatkan aksesibilitas.
3. Validasi data formulir baik di sisi klien (browser) maupun di sisi server untuk keamanan.

---

## Referensi tambahan
- [Dokumentasi MDN tentang Form](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
- [Dokumentasi MDN tentang Input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
- [Tutorial W3Schools tentang Form](https://www.w3schools.com/html/html_forms.asp)

---

Happy coding! 😊