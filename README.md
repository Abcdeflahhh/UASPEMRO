NAMA : AFLAH ATHALLAH TAMAM KAPUKONG

KELAS :24.A4

NIM : 312410280

MATA KULIAH : BAHASA PEMROGRAMAN

DOSEN PENGAMPU : Agung Nugroho, S.Kom., M.Kom.

![gambar](https://github.com/Abcdeflahhh/UASPEMRO/blob/71de6bd92acac08a813c4d8179a0606b5037b7cd/Image/tugas.jpg)

- Class " Data " 
 
![gambar](https://github.com/Abcdeflahhh/UASPEMRO/blob/b4c7185e51c5fabb70c80fe6a282a6c0386b8a15/Image/class%20data.jpg)

Deskripsi: Kelas Data digunakan untuk menyimpan informasi tentang seorang mahasiswa, termasuk:

nama: Nama mahasiswa.

nim: Nomor Induk Mahasiswa.

nilai_uas: Nilai Ujian Akhir Semester.

Metode __init__: Ini adalah konstruktor yang dipanggil saat objek dari kelas ini dibuat. Ia menerima tiga parameter (nama, nim, dan nilai_uas) dan menyimpannya sebagai atribut objek.

- Class " View " 

![gambar](https://github.com/Abcdeflahhh/UASPEMRO/blob/804b9c41bc554e0ff189d6b493c5b034950ff675/Image/class%20view.jpg)

Deskripsi: Kelas View bertanggung jawab untuk interaksi dengan pengguna, termasuk pengambilan input dan menampilkan output.

Metode input_data:

Mengambil input dari pengguna untuk nama, NIM, dan nilai UAS.

Menggunakan strip() untuk menghapus spasi di awal dan akhir input.

Mengembalikan objek Data yang baru dibuat dengan informasi tersebut.

Metode tampilkan_data:

Menerima daftar objek Data dan menyiapkan data untuk ditampilkan dalam format tabel.

Menambahkan header tabel dan setiap data mahasiswa ke dalam tabel_data.

Memanggil fungsi tampilkan_tabel untuk menampilkan data.

- Fungsi " Tampilkan Table "

![gambar](https://github.com/Abcdeflahhh/UASPEMRO/blob/cbac0eaedd66045259d5d8170e5f1de5c1f09817/Image/tampilkan%20table.jpg)

Deskripsi: Fungsi ini bertugas untuk menampilkan data dalam format tabel.

Proses:

Menghitung lebar kolom berdasarkan panjang data terpanjang di setiap kolom menggunakan zip(*data).

Mencetak header tabel dan garis pemisah.

Mencetak setiap baris data dengan format yang sesuai, menggunakan lebar kolom yang telah ditentukan.

- Class " Process "

![gambar]()

