# Catatan Minggu 03: Inheritance

## Yang saya kerjakan
Saya mengerjakan penerapan konsep inheritance (pewarisan) pada program AsetPinjam. Saya melengkapi beberapa class turunan, yaitu Ruang, Laptop, dan AlatLab yang mewarisi atribut dan method dari class induk Aset. Saya juga menambahkan atribut khusus pada setiap class, membuat constructor, getter, validasi data, serta melakukan override pada method getJenis(). Dengan inheritance, setiap jenis aset memiliki karakteristik masing-masing tanpa harus membuat ulang seluruh kode dari class induk.

## Keputusan desain
Saya menggunakan inheritance dengan menjadikan Aset sebagai class induk, sedangkan Ruang, Laptop, dan AlatLab sebagai class turunannya. Setiap class turunan memiliki atribut khusus sesuai jenis asetnya. Saya menggunakan access modifier private untuk menjaga agar atribut tidak diakses secara langsung dari luar class. Saya juga menambahkan validasi agar data tidak boleh kosong atau bernilai null sesuai ketentuan program.

## Kendala
Kendala yang saya alami adalah munculnya garis merah dan error pada method getJenis() di class Ruang. Setelah diperiksa, ternyata tipe data method pada class turunan harus sama dengan method pada class induk, yaitu JenisAset, bukan String. Saya mengatasinya dengan memeriksa kode Aset.java dan menyesuaikan method override pada class turunannya. Saya juga belajar memperhatikan tipe data dan nama enum agar tidak terjadi kesalahan saat kompilasi.

## Penggunaan AI
- Alat yang dipakai: ChatGpt
- Bagian yang dibantu AI: bagian laptop
- Prompt utama: saya bertanya ke ai 'kenapa ini masih merah' ternyata setelah saya cek di aset bukan menggunakan String melainkan harus menggunakan JenisAset. setelah saya menggantinya menjadi JenisAset baru benar.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya menyesuaikan tipe data method getJenis() dari String menjadi JenisAset setelah memeriksa class induk Aset, karena tipe data yang digunakan harus sesuai dengan method induknya.
- Satu hal yang saya pahami lebih baik sekarang: menjadi lebih memahami konsep inheritance, yaitu class turunan dapat mewarisi atribut dan method dari class induk. Saya juga memahami bahwa overriding digunakan untuk memberikan implementasi method yang berbeda pada setiap class turunan sesuai kebutuhan.
