# Catatan Minggu 02 : Struktur OOP: Class, Object, Encapsulation

## Yang saya kerjakan
Pada minggu 2, saya mengerjakan class Aset dengan menerapkan konsep encapsulation. Saya menambahkan field kode, nama, status, dan kondisi dengan access modifier private. Saya juga membuat konstruktor, getter, dan setter untuk mengakses serta mengubah data aset. Selain itu, saya menambahkan validasi agar kode dan nama tidak boleh kosong serta status dan kondisi tidak boleh bernilai null.

## Keputusan desain
Saya menggunakan access modifier private agar data aset tidak dapat diubah secara langsung dari luar class. Saya menggunakan getter dan setter sebagai cara untuk mengakses dan mengubah data. Status awal aset ditetapkan menjadi tersedia, sedangkan kondisi awalnya baik. Saya menggunakan IllegalArgumentException untuk menangani data yang tidak valid.

## Kendala
Kendala yang saya temui adalah memahami cara menerapkan encapsulation dan validasi pada Java. Saya mengatasinya dengan mempelajari fungsi getter, setter, konstruktor, dan penggunaan IllegalArgumentException. Saya juga memperhatikan agar data aset tidak dapat diisi dengan nilai kosong atau null.

## Penggunaan AI
- Alat yang dipakai: ChatGpt
- Bagian yang dibantu AI: saya bingung ketika disuruh menerapkan encapsulation dan validasi pada java
- Prompt utama: saya hanya bertanya pada ai apa yang harus saya lakukan dan validasi seperti apa yang dimaksud ( saya salin teks nya dan saya bertanya ini gimana maksudnya)
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya menyesuaikan kode dengan struktur class yang sudah tersedia di repository dan hanya mengganti bagian TODO yang diminta agar tidak mengubah bagian lainnya.
- Satu hal yang saya pahami lebih baik sekarang: Saya lebih memahami konsep encapsulation, penggunaan field private, getter dan setter, serta validasi data menggunakan IllegalArgumentException.
