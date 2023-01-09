# repository-UAS-2

```
Nama  : Sahrul Ridwansyah
Nim   : 312210063
Kelas : TI.22.A2
```

# model/daftar_nilai.py

MODEL/daftar_nilai.py merupakan modul yang berisi empat buah fungsi utama, yaitu tambah_data, ubah_data, hapus_data, dan cari_data. Setiap fungsi memiliki parameter dan tipe data yang berbeda-beda, sehingga dapat digunakan untuk mengelola data penilaian mahasiswa dengan cara yang sesuai.
Fungsi tambah_data berfungsi untuk menambahkan data penilaian mahasiswa ke daftar nilai. Fungsi ini memiliki parameter daftar (list) dan data (tuple), kemudian menambahkan data ke daftar nilai dengan menggunakan perintah daftar.append(data).
Fungsi ubah_data berfungsi untuk mengubah data penilaian mahasiswa yang ada di daftar nilai. Fungsi ini memiliki parameter daftar (list), data_baru (tuple), dan data_lama (tuple), kemudian mengubah data yang ada di daftar nilai dengan menggunakan perintah for dan if.
Fungsi hapus_data berfungsi untuk menghapus data penilaian mahasiswa dari daftar nilai. Fungsi ini memiliki parameter daftar (list) dan data (tuple), kemudian menghapus data dari daftar nilai dengan menggunakan perintah daftar.remove(data).
Fungsi cari_data berfungsi untuk mencari data penilaian mahasiswa di daftar nilai. Fungsi ini memiliki parameter daftar (list) dan data (tuple), kemudian mencari data di daftar nilai dengan menggunakan perintah for dan if. Jika data ditemukan, maka data tersebut dikembalikan kepada pengguna. Jika tidak, maka akan dikembalikan pesan "Data tidak ditemukan.".

