#Format

Masalah format paling diperdebatkan tetapi paling konsekuensial. Orang bisa beradaptasi dengan gaya yang berbeda dengan gaya format yang berbeda tetapi lebih baik jika mereka tidak perlu melakukannya, dan sedikit waktu yang dikhususkan untuk topik ini jika semua orang menganut gaya yang sama. Masalahnya adalah bagaimana pendekatan Utopia ini tanpa panduan pandangan gaya jangka panjang.

Dengan Go kita mengambil pendekatan yang tidak biasa dan membiarkan mesin mengurus sebagian besar masalah format. Program `gofmt` (juga tersedia dalam `go fmt` yang beroperasi pada tingkat paket daripada tingkat sumber file) membaca program Go dan mengeluarkan sumber dalam gaya standar indentasi dan rataaan vertikal, mempertahankan dan jika ada komentar diperlukan perubahan format. Jika anda ingin mengetahui bagaimana menangani beberapa situasi layout baru, jalankan `gofmt`; jika hasilnya tidak kelihatan benar, atur ulang program anda (catat bug tentang `gofmt`), tidak bekerja di sekitar itu.  


### Tautan

- Sebelumnya: [Format](02_format.md)
- Berikutnya: [Komentar](03_komentar.md)
