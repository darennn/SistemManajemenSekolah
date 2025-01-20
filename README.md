# Aplikasi SistemManajemenSekolah
- Nama : Dona Fauzi Romdona
- NIM  : 2203010522

# Penjelasan Singkat Program 
## Tujuan Program
*Program ini bertujuan untuk mengelola data sekolah, termasuk:

-> Kepala Sekolah: Memiliki informasi pribadi, spesialisasi, dan program pengembangan.

-> Guru: Memiliki informasi pribadi, mata pelajaran yang diajarkan, daftar siswa, dan jadwal mengajar.

-> Siswa: Memiliki informasi pribadi, nilai akademik, dan kehadiran.

## Program ini juga menyediakan fitur untuk:

-> Menambahkan data siswa, guru, dan kepala sekolah.

-> Menyimpan dan membaca data ke/dari file.

-> Melakukan evaluasi kelas dan departemen.

## Struktur Program
*Program ini terdiri dari beberapa kelas dan interface:

- Kelas Utama
SistemManajemenSekolah: Kelas utama yang menjalankan program dan menyediakan menu interaktif.

- Kelas Model :
  
-> Orang: Kelas abstrak yang menjadi parent untuk Siswa, Guru, dan KepalaSekolah. Berisi informasi dasar seperti nama, ID, dan timestamp.

-> Siswa: Mengelola data siswa, termasuk nilai, kehadiran, dan aktivitas akademik.

-> Guru: Mengelola data guru, termasuk mata pelajaran, daftar siswa, dan jadwal mengajar.

-> KepalaSekolah: Mengelola data kepala sekolah, termasuk program pengembangan dan guru bimbingan.

- Kelas Pendukung :
  
-> KehadiranManager: Mengelola data kehadiran siswa.

-> NilaiTidakValidException: Exception khusus untuk menangani nilai yang tidak valid.

-> StatusKehadiran: Enum yang mendefinisikan status kehadiran (HADIR, IZIN, SAKIT, ALPHA).

- Interface :
  
-> DataOperation: Menyediakan metode untuk menyimpan, membaca, dan memvalidasi data.

-> KegiatanAkademik: Menyediakan metode untuk kegiatan akademik siswa, seperti mengikuti pelajaran dan mengumpulkan tugas.

## Fitur Program
*Program ini memiliki fitur-fitur berikut:

- Input Data
Pengguna dapat menambahkan data siswa, guru, dan kepala sekolah melalui input interaktif.

- Penyimpanan Data
Data disimpan dalam file teks (txt) untuk setiap entitas (siswa, guru, kepala sekolah).

- Pembacaan Data
Data dapat dibaca dari file teks untuk ditampilkan ke pengguna.

- Evaluasi :
  
-> Evaluasi Kelas: Menghitung rata-rata nilai dan kehadiran siswa dalam suatu mata pelajaran.

-> Evaluasi Departemen: Menampilkan kinerja guru dan program pengembangan di suatu departemen.

- Menu Interaktif
Program menyediakan menu interaktif untuk memudahkan pengguna dalam memilih fitur yang diinginkan.

## Cara Kerja Program
-> Program dimulai dengan inisialisasi data kepala sekolah dan guru.

-> Pengguna diberikan menu interaktif untuk memilih fitur:

- Tambah Siswa: Menambahkan data siswa baru, termasuk nilai dan kehadiran.

- Tambah Guru: Menambahkan data guru baru, termasuk mata pelajaran.

- Tampilkan Informasi: Menampilkan informasi kepala sekolah, guru, dan siswa.

- Evaluasi Kelas: Menampilkan evaluasi kelas berdasarkan mata pelajaran.

- Keluar: Mengakhiri program.

-> Data yang dimasukkan pengguna disimpan ke dalam file teks.

-> Data dapat dibaca kembali dari file teks untuk ditampilkan atau dievaluasi.





## Kesimpulan
Program Sistem Manajemen Sekolah adalah aplikasi sederhana untuk mengelola data sekolah. Dengan fitur input, penyimpanan, dan evaluasi, program ini dapat membantu pengguna dalam mengelola informasi akademik secara efisien.


*Data dapat dibaca kembali dari file teks untuk ditampilkan atau dievaluasi.*
