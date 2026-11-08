# Catatan Minggu NN: (topik)
Paradigma Pemrograman dan Setup

## Yang saya kerjakan
Saya membuat program sapaan yang sama dengan tiga gaya: prosedural (HelloProsedural), OOP (HelloOOP), dan fungsional (HelloFungsional). Ketiganya menampilkan sapaan berisi "Aset-Pinjam", nama, dan NIM yang diambil dari Varian.aktif(). Hasil keluarannya sama, hanya cara menyusun kodenya yang berbeda.

## Keputusan desain
- Prosedural: pakai method static sapa(nama, nim) yang langsung mengembalikan String, tanpa objek buatan sendiri.
- OOP: nama dan nim saya jadikan field private final yang diisi lewat konstruktor, lalu method sapa() memakai field itu. Dibuat final supaya datanya tidak berubah setelah objek dibuat.
- Fungsional: pembuatSapaan(nim) mengembalikan Function<String, String> berupa lambda yang menerima nama. Tidak ada state yang berubah

## Kendala
Di HelloOOP saya sempat salah menulis string (huruf kecil) dan ada konstruktor yang tertulis dua kali, jadi muncul error merah. Saya atasi dengan menghapus baris duplikat dan memperbaiki tipenya menjadi String. Format sapaan juga sempat tidak ada spasi, lalu saya perbaiki sesuai contoh di TODO.


## Penggunaan AI
- Alat yang dipakai: ChatGpt
- Bagian yang dibantu AI: kode error merah di ouput
- Prompt utama: waktu saya run code yang sudah saya tulis kembali hasilnya malah merah, akhirnya saya memutuskan untuk mengscreenshot bagian yang error lalu bertanya ke ChatGPt " ini kenapa kok bisa error " lalu saya kirimkan dan ChatGPt menjawab ada bagian yang salah seperti tulisan String yang huruf awal menggunakan huruf kapital ,karena punyaku memakai huruf kecil jadinya merah hasil outputnya.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: code dari AI saya tolak karena membuat saya bingung dan saya hanya mengubah bagian yang perlu saja
- Satu hal yang saya pahami lebih baik sekarang: sebelum meng run saya harus mengecek kembali apakah sudah benar huruf dan lain sebagainya, dan saya mulai memahami perbedaan setiap bahasa code pemroggraman yang sudah saya pelajari dan saya praktekan.