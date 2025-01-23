# Block and Inline element in HTML

Dalam HTML, elemen-elemen dibedakan menjadi dua kategori utama: Block-level elements dan Inline elements. Pemahan mengenai perbedaan ini sangat penting karena berpengaruh pada layout dan tampilan halman web.

## Block-level elements
Elemen block-level adalah elemen yang secara otomatis memulai baris baru dan mengambil lebar penuh dari kontainer induknya (parent container). Elemen ini digunakan untuk membungkus konten besar dan membuat struktur halaman lebih terorganisir.

### Ciri-ciri Block-level Elements:
- Memulai pada baris baru.
- Mengambil lebar penuh dari kontainer induknya.
- Bisa berisi elemen lain, termasuk block-level elements lainnya dan inline elements

### Contoh Elemen block-level
Contoh nya ada di file blockInline.html ya

### Beberapa Elemen Block-level yang umum:
- `<div>`
- `<p>`
- `<h1>`, `<h2>`, `<h3>`,...`<h6>`
- `<ul>`, `<ol>`, `<li>`
- `<header>`, `<footer>`, `<section>`, `<article>`
- `<form>`


## Inline Elements
Elemen inline adalah elemen yang hanya mengambil ruang sebesar konten yang dibawanya. Elemen ini tidak menyebabkan baris baru dan dapat berdampingan dengan elemen lainnya di dalam satu baris.

### Ciri-ciri Inline Elements:
- Tidak memulai baris baru.
- Hanya memakan ruang sebesar konten yang ada di dalamnya.
- Tidak dapat berisi elemen block-level lain, hanya elemen inline atau teks.

### Contoh elemen inline
Contohnya ada di file blockInline.html ya

### Beberapa Elemen Inline yang Umum:
- `<span>`
- `<a>`
- `<strong>`, `<em>`
- `<img>`
- `<b>`, `<i>`
- `<code>`


## Perbedaan Antara Block dan Inline
| Properti                  | Block-level Elements                  | Inline Elements                  |
|---------------------------|---------------------------------------|----------------------------------|
|Perilaku                   |Memulai baris baru                     |Tidak memulai baris baru          |
|Lebar                      |Mengambil lebar penuh kontainer        |Hanya selebar konten yang ada     |
|Elemen yang bisa dibungkus |Bisa membungkus elemen block dan inline|Hanya bisa dibungkus elemen inline|
|Contoh elemen              |`<div>`, `<h1>`, `<ul>`, `<p>`                 |`<span>`, `<a>`, `<strong>`             |


## Mencampus Block dan Inline
Terkadang, kita perlu mencampur elemen block-level dan inline dalam struktur HTML untuk tujuan tertentu. Sebagai contoh, kita bisa menggunakan elemen block-level untuk membuat struktur dan elemen inline untuk teks yang lebih kecil atau tautan.

### Contoh menggabung elemen block dan inline
Contohnya ada di file blockInline.html ya


## Terdapat tag `<div>` dan tag `<span>` serta ada atribut style, Apa sih itu ?

### Elemen `<div>`
Elemen `<div>` adalah elemen block-level yang digunakan untuk mengelompokkan elemen-elemen lain di dalamnya. Biasanya, `<div>` digunakan untuk membagi konten dalam halaman web dan memberikan struktur pada layout. Secara default, elemen ini akan mengambil lebar penuh dari kontainer induknya dan memulai baris baru.

#### Penggunaan `<div>`:
- Membuat sekumpulan konten atau bagian dalam halaman web.
- Memberikan gaya dengan CSS (kita akan belajar nanti)
- Memnambahkan interaktivitas dengan javascript (kita akan belajar nanti)

#### Contoh penggunaan `<div>`:
Ada di file divAndSpan.html ya

### Elemen `<span>`
Elemen `<span>` adalah elemen inline yang digunakan untuk membungkus bagian kecil dari konten seperti teks atau elemen-elemen inline lainnya. Biasanya, `<span>` digunakan untuk memberi gaya pada bagian tertentu dari teks tanpa mempengaruhi aliran dokumen secara keseluruhan.

#### Penggunaan Umum `<span>`:
- Menyorot atau memberi gaya khusus pada bagian kecil teks.
- Tidak mengubah struktur atau layout halaman secara signifikan
- Tidak menyebabkan baris baru

#### Contoh penggunaan `<span>`:
Ada di file divAndSpan.html ya

### Atribut **style**
#### Penjelasan sederhana untuk Atribut style
- Atribut **style** adalah cara untuk memberikan gaya atau tampilan langsung pada elemen HTML.
- Dengan menggunakan **style**, kamu bisa mengubah hal-hal seperti warna latar belakang, warna teks, ukuran teks, dan banyak lagi, tanpa menulis kode CSS di file terpisah.
- Ini lebih cocok untuk perubahan kecil atau percakapan langsung pada eleme*n, tetapi untuk proyek yang lebih besar dan terstruktur, CSS biasanya lebih baik.

#### Penjelasan dalam konteks HTML:
Katakanlah kamu punya elemen `<div>`, `<p>`, atau `<span>`, dan kamu ingin mengubah tampilan elemen-elemen tersebut—misalnya, mengubah warna latar belakang atau teks. Alih-alih menulis kode CSS terpisah, kamu bisa menambahkan atribut **style** langsung di elemen tersebut untuk membuat perubahan yang langsung terlihat.

#### Contoh 
Contoh mengubah **warna latar belakang** dan **warna teks** ada di file blockInline.html dan divAndSpan.html
- **background-color: red;** mengubah latar belakang menjadi merah
- **color: white;** mengubah warna teks menjadi putih



## Kesimpulan
Memahami perbedaan antara elemen block dan inline dalam HTML sangat penting untuk menyusun layout dan struktur halaman yang efisien. Elemen block cocok digunakan untuk membagi konten besar menjadi bagian yang lebih terorganisir, sementara elemen inline lebih cocok untuk bagian kecil, seperti teks atau tautan, yang tidak memerlukan pemisahan baris baru.

---

## Referensi tambahan
- [Dokumentasi MDN tentang block-level element](https://developer.mozilla.org/en-US/docs/Glossary/Block-level_content)
- [Dokumentasi MDN tentang inline-level element](https://developer.mozilla.org/en-US/docs/Glossary/Inline-level_content)
- [Tutorial W3Schools tentang block-level element dan inline-level element](https://www.w3schools.com/html/html_blocks.asp)

---

Happy coding! 😊