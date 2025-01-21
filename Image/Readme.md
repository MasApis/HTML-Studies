# Picture in html

Elemen `<img>` adalah salah satu elemen HTML yang paling umum digunakan untuk menyisipkan gambar dalam halaman web. Gambar dapat memberikan konteks visual dan memperkaya pengalaman pengguna. Panduan ini menjelaskan cara menggunakan elemen `<img>` dalam HTML dengan berbagai cara, termasuk atribut-atribut penting, teknik responsif, dan praktik terbaik.

## 1. Sintaks Dasar

Untuk menyisipkan gambar menggunakan elemen `<img>`, Anda perlu mendefinisikan atribut `src` untuk menentukan sumber gambar, serta `alt` untuk memberikan deskripsi gambar jika gambar tidak dapat ditampilkan. Berikut adalah sintaks dasar:

```html
<img src="path/to/image.jpg" alt="Deskripsi Gambar">
```

### Atribut utama
- **src(Source):** Atribut ini wajib ada dan menentukan sumber gambar. Nilai dari src dapat berupa URL gambar atau path relatif.

- **alt(Alternative text):** Menyediakan deskripsi gambar untuk pembaca layar, atau ketika gambar gagal dimuat.


## 2. Atribut tambahan

### width dan height
**Atribut width dan height** digunakan untuk menentukan ukuran gambar dalam piksel. Ini membantu pengaturan tata letak dan meminimalisir pergesaran konten saat gambar dimuat. Contoh penggunaan terdapat di file image.html

### title
**Atribut title** memberikan informasi tambahan saat pengguna mengarahkan kursor ke gambar. Ini sering digunakan untuk memberikan tooltip. Contoh terdapat di file image.html

### loading
**Atribut loading** mengontrol bagaimana gambar dimuat di halaman web. Ada dua nilai yang umum digunakan: lazy untuk membuat gambar hanya ketika gambar hampir terlihat di layar, dan eager untuk memuat gambar secara langsung. Contoh penggunaan terdapat di file image.html


## Kombinasi tag `<a>` dengan `img`
sebuah gambar bisa disisipi oleh sebuah link website, yang berguna untuk menambah informasi dari gambar tersebut. Contoh penggunaan terdapat di file image.html

## Catatan penting
1. **Selalu sertakan atribut `alt`**
- **Peringatan**: Jangan pernah meninggalkan atribut `alt` kosong. Atribut ini penting untuk **aksebilitas** dan membantu pengguna dengan gangguan penglihatan yang menggunakan pembaca layar.

2. **Hati-hati dengan ukuran gambar**
- **Perinatan**: Menentukan gambar dengan atribut **width** dan **height** dapat membantu menghindari pergeseran konten saat gambar dimuat. Pastikan ukuran yang diberikan sesuai dengan gambar asli untuk mencegah gambar pecah.

3. **Jangan gunakan gambar berat yang terkompresi**
- **Peringatan:** Gambar besar yang terkompresi dapat memperlambat waktu muat halaman, yang akan mempengaruhi pengalaman pengguna.

## Referensi tambahan
- [Dokumentasi MDN tentang Image](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
- [Tutorial W3Schools tentang HTML image](https://www.w3schools.com/html/html_images.asp)

---

Happy coding! 😊
