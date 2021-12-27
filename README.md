# Final Project PBO Kelompok1

* Muhammad Hanif 2017051004
* Fitriah Hardianti 2057051001

## Pembagian Tugas

* Muhammad Hanif
   - Membuat dan menghubungkan program dengan database SQLite
   - Menginisialisasi dan mengembangkan class yang digunakan dalam project

* Fitriah Hardianti
   - Mendesain dan membuat GUI menggunakan JavaFX dan Scene Builder
   - Menginisialisasi dan mengembangkan class yang digunakan dalam project

## StudiCase Program
Pada sistem koperasi, terdapat entitas nasabah, dimana nasabah  memiliki properti nama, noRekening, alamat dan saldo tabungan. Setelah departemen IT  memisahkan kelas Nasabah dengan Rekening, yang berasosiasi secara agregasi 1:n.
Setelah berjalannya waktu, kopereasi tumbuh menjadi besar, sehingga nasabah koperasi tidak hanya individu akan tetapi juga perusahaan, untuk itu perlu penyesuaian sistem yang sudah ada, Direksi mengambil kebijakan pemisahan entitas nasabah individu dan perusahaan, dimana masing-masing entitas memiliki properti pembeda yaitu, untuk individu memiliki nik dan npwp sedangan untuk perusahaan memiliki nomor izin berusaha (nib)

![ClassDiagram](https://user-images.githubusercontent.com/83523392/147461347-33a10728-6f44-4386-bef7-4ab9ea15ec2e.png)
## Penjelasan Class Diagram
nasabah harus salah satu antara Individu atau Perusahaan sehingga class Nasabah harus dibuat abstrak agar tidak bisa diinstansiasi. Semua subclass dari kelas Nasabah harus menimplementasikan method print() yang berbeda dengan subclass lainnya, sehingga method print() ini harus dibuat abstract di class Nasabah.
