# Catatan Minggu 04 : Polymorphism

## Yang saya kerjakan
saya mengerjakan penerapan konsep polymorphism pada program Aset Pinjam, mengubah method getJenis() dan hitungDenda() pada class Aset menjadi method abstract agar setiap subclass dapat memberikan implementasinya masing-masing. Selain itu, saya mengerjakan dua method cari() pada class KatalogAset untuk mencari aset berdasarkan nama dan jenis aset. Pencarian nama dibuat agar tidak membedakan huruf besar dan kecil.

## Keputusan desain
Saya menggunakan abstract method pada class Aset karena setiap jenis aset memiliki jenis dan aturan denda yang dapat berbeda. Dengan demikian, setiap subclass bertanggung jawab memberikan implementasi method tersebut.

Pada class KatalogAset, saya menggunakan method overloading pada method cari(). Method pertama digunakan untuk mencari aset berdasarkan kata pada nama, sedangkan method kedua digunakan untuk mencari aset berdasarkan nama sekaligus jenis aset. Saya juga menggunakan toLowerCase() agar pencarian tidak dipengaruhi oleh penggunaan huruf besar atau kecil.

## Kendala
masih bingung dengan cara memahami penerapan polymorphism pada class induk dan subclass.Saya mengatasinya dengan mempelajari kembali struktur class dan menggunakan bantuan AI untuk memahami penempatan kode serta cara kerja setiap method.

## Penggunaan AI
- Alat yang dipakai: ChatGPt
- Bagian yang dibantu AI: saat awal saya bingung  dengan penerapannya
- Prompt utama: untuk prompt nya saya bilang gini, 'bisa tolong jelasin ini maksudnya gimana'
- Yang saya ubah atau tolak dari saran AI, dan alasannya: saya menolak kode dari ai nya
- Satu hal yang saya pahami lebih baik sekarang: lumayan paham bahwa polymorphism memungkinkan method dengan nama yang sama memiliki perilaku berbeda melalui overriding pada subclass. dan juga sedikit memahami bahwa overloading memungkinkan beberapa method memiliki nama yang sama tetapi parameter berbeda.
