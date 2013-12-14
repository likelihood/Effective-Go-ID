#Penamaan 

Nama sebagai hal penting pada Go seperti dalam bahasa pemrograman lain. Bahkan memiliki dampak semantik: visibilitas nama diluar paket ditentukan oleh apakah karakter pertama adalah huruf besar. Karena itu layak untuk menghabiskan sedikit waktu untuk berbicara tentang aturan penamaan dalam Go.

### Nama Paket 

Ketika sebuah paket di impor, nama paket menjadi accessor untuk isi. Setelah
`import "bytes"`

impor paket bisa berbicara tentang `bytes.Buffer`. Ini sangat menolong jika setiap orang yang memakai paket bisa menggunakan nama yang sama mengacu pada isinya, yang menyiratkan bahwa nama paket harus baik: pendek, ringkas dan menggugah (mudah diingat). Dengan aturan, paket ditulis dengan huruf kecil, ditulis dalam 1 kata saja, tidak perlu garis bawah atau penulisan campuran hurufBesar. Mengurangi salah tulis, karena semua orang yang menggunakan paket anda akan mengetik nama itu. 
