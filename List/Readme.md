# List in HTML

Daftar (lists) dalam HTML digunakan untuk mengelompokkan item yang saling berhubungan dalam sebuah struktur. Ada tiga jenis utama daftar dalam HTML:

## 1. List Berurutan (`<ol>`)
Daftar berurutan digunakan ketika item dalam daftar harus memiliki urutan tertentu. Setiap item dalam daftar diberi nomor secara otomatis oleh browser.

### Contoh penggunaan
Contoh penggunaan tag `<ol>` terdapat di file list.html ya teman-teman.

### Atribut:
- `type`: Menentukan jenis penomoran (misalnya, `1`, `A`, `a`, `I`, `i`).
  ```html
  <ol type="A">
    <li>Item A</li>
    <li>Item B</li>
  </ol>
  ```
- `start`: Menentukan angka awal dari daftar.
  ```html
  <ol start="5">
    <li>Item 5</li>
    <li>Item 6</li>
  </ol>
  ```

## 2. List Tidak Berurutan (`<ul>`)
Daftar tidak berurutan digunakan ketika urutan item tidak penting. Setiap item ditampilkan dengan simbol peluru.

### Contoh penggunaan
Contoh penggunaan tag `<ul>` terdapat di file list.html ya teman-teman.

### Atribut:
- `type`: Menentukan gaya peluru (misalnya, `disc`, `circle`, `square`).
  ```html
  <ul type="circle">
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
  ```

## 3. Daftar Definisi (`<dl>`)
Daftar definisi digunakan untuk mendefinisikan istilah dan deskripsinya.

### Contoh penggunaan
Contoh penggunaan tag `<dl>` terdapat di file list.html ya teman-teman.

### Elemen dalam Daftar Definisi:
- `<dt>`: Mendefinisikan istilah.
- `<dd>`: Menjelaskan istilah.

## List Bersarang
Daftar dapat disusun secara bersarang untuk membuat struktur yang lebih kompleks.

### Contoh penggunaan
Contoh penggunaan tag list bersarang terdapat di file list.html ya teman-teman.

## Catatan penting
- Gunakan tag semantik yang tepat (`<ol>`, `<ul>`, `<dl>`) agar pembaca layar (screen readers) dapat memahami konten dengan baik.
- Tambahkan teks deskriptif jika diperlukan.
- Hindari daftar bersarang yang terlalu rumit, karena dapat membingungkan pengguna.
- Terdapat tag `<strong>` di contoh penggunaan tag `<dl>`, itu berguna untuk memberikan penekanan pada sebuah text.

## Latihan
Cobalah membuat halaman HTML sederhana yang menggunakan semua tag list dari `<ul>`, `<ol>`, dan `<dl>`. Kombinasikan dengan tag heading untuk memahami cara kerjanya.

## Referensi tambahan
- [Dokumentasi MDN tentang List](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [Tutorial W3Schools tentang HTML List](https://www.w3schools.com/html/html_lists.asp)

---

Happy coding! 😊
