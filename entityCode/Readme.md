# Entity Code in HTML

## Pengertian Entity Code
Entity code dalam HTML adalah cara untuk mewakili karakter khusus, simbol, atau tanda tertentu yang mungkin memiliki makna khusus dalam HTML, sehingga tidak dapat ditulis langsung dalam kode. Dengan menggunakan entity code, kamu dapat memastikan bahwa karakter tersebut ditampilkan dengan benar di browser.

Entity code biasanya dimulai dengan tanda `&` dan diakhiri dengan tanda `;`.

### Contoh Format Entitiy Code:
- **Nama Entitas (Named Entity)**: `&nbsp;` (untuk spasi)
- **Kode Numerik (Numeric Entity)**: `&#160;` (untuk spasi)


## Daftar Entity Code Umum
Berikut adalah beberapa entity code yang sering digunakan:
|Simbol|Nama Entitas|Kode Numerik|Deskripsi            |
|------|------------|------------|---------------------|
|`&`   |`&amp;`     |`&#38;`     |Ampersand (dan)      |
|`<`   |`&lt;`      |`&#60;`     |Tanda lebih kecil    |
|`>`   |`&gt;`      |`&#62;`     |Tanda lebih besar    |
|`"`   |`&quot;`    |`&#34`      |Tanda kutip ganda    |
|`'`   |`&apos;`    |`&#39`      |Tanda kutip tunggal  |
|      |`&nbsp;`    |`&#160`     |Spasi non-breaking   |
|&copy;|`&copy;`    |`&#169`     |Tanda hak cipta      |
|&reg; |`&reg;`     |`&#174`     |Tanda merek terdaftar|
|&euro;|`&euro;`    |`&#8364`    |Simbol Euro          |
|&yen; |`&yen;`     |`&#165`     |Simbol Yen           |

## Studi Kasus: Menggunakan Entity Code
Ada pada file entityCode.html yaa

## Catatan Penting:
1. **Penggunaan Entity Code**: Gunakan entity code untuk menghindari konflik karakter yang memiliki makna khusus dalam HTML (misalnya `<` dan `>` untuk tag HTML).
2. **Konsistensi**: Jika memungkinkan, gunakan format yang lebih mudah dibaca (nama entitas) dibandingkan kode numerik.
3. **Spasi Non-breaking: Entity `&nbsp;` sangat berguna untuk menjaga agar teks tidak terpisah oleh pergantian baris otomatis di browser.

---

## Referensi tambahan
- [Entity code W3C HTML Entities](https://www.w3.org/TR/html4/sgml/entities.html)
- [Entity code toptal](https://www.toptal.com/designers/htmlarrows/symbols/)

---

Happy coding! 😊