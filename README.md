# Tugas_PBO_2
program sederhana untuk mengelola data mahasiswa di sebuah universitas.

Pada program ini saya memakai method __init__ yang dimana setiap class memiliki atribut yang berbeda-beda. Dan masih ada beberapa method seperti method tampilkan info, tambah mahasiswa, tampilkan daftar mahasiswa, dan lain sebagainya.

Disini saya akan memberikan penjelasan dari kode-kode yang telah saya buat :
1. Kelas Mahasiswa:
   - Kelas ini memiliki tiga atribut yaitu `nama`, `nim`, dan `jurusan`.
   - Metode `__init__` digunakan untuk menginisialisasi objek Mahasiswa dengan nilai-nilai atribut.
   - Metode `tampilkan_info` digunakan untuk menampilkan informasi mahasiswa seperti nama, NIM, dan nama jurusan.

2. Kelas Jurusan:
   - Kelas ini memiliki dua atribut yaitu `NamaJurusan` dan `DaftarMahasiswa`.
   - Metode `__init__` digunakan untuk menginisialisasi objek Jurusan dengan nama jurusan dan membuat daftar mahasiswa kosong.
   - Metode `tambah_mahasiswa` digunakan untuk menambahkan objek Mahasiswa ke dalam daftar mahasiswa jurusan.
   - Metode `tampilkan_daftar_mahasiswa` digunakan untuk menampilkan daftar mahasiswa yang terdaftar di jurusan ini.

3. Kelas Universitas:
   - Kelas ini memiliki dua atribut yaitu `NamaUniversitas` dan `DaftarJurusan`.
   - Metode `__init__` digunakan untuk menginisialisasi objek Universitas dengan nama universitas dan membuat daftar jurusan kosong.
   - Metode `tambah_jurusan` digunakan untuk menambahkan objek Jurusan ke dalam daftar jurusan universitas.
   - Metode `tampilkan_daftar_jurusan` digunakan untuk menampilkan daftar jurusan yang ada di universitas ini.

4. Bagian kode di bawah kelas-kelas tersebut melakukan interaksi dengan pengguna untuk mengisi informasi universitas, jurusan, dan mahasiswa.
   - Pengguna diminta untuk memasukkan nama universitas dan objek Universitas dengan nama tersebut dibuat.
   - Pengguna juga diminta untuk memasukkan nama jurusan dan objek Jurusan dengan nama tersebut dibuat. Kemudian objek Jurusan tersebut ditambahkan ke dalam objek      Universitas.
   - Pengguna juga diminta untuk memasukkan nama dan NIM mahasiswa. Objek Mahasiswa dengan informasi tersebut dibuat, dan objek Mahasiswa tersebut ditambahkan ke      dalam objek Jurusan.
   - Terakhir, hasil dari daftar jurusan di Universitas dan daftar mahasiswa di Jurusan Teknik Informatika di Universitas tersebut ditampilkan kepada pengguna.

Kode ini memberikan kerangka dasar untuk menyimpan dan mengelola informasi tentang mahasiswa, jurusan, dan universitas. Dengan menggunakan objek-objek ini, kita dapat menyimpan informasi tentang mahasiswa yang terdaftar dalam berbagai jurusan di sebuah universitas, serta menampilkan informasi tersebut sesuai dengan kebutuhan.
