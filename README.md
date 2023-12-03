
# Sistem Informasi Sekolah

Sistem informasi sekolah berbasis laravel 8 dengan template dashboard
[Stisla](https://getstisla.com/)
## Authors

- [Pascal Adnan](https://www.github.com/lacsapadnan)


## Fitur

- CRUD Jurusan
- CRUD Mata Pelajaran
- CRUD Guru
- CRUD Kelas
- CRUD User
- CRUD Materi
- CRUD Tugas & Jawaban
- CRUD Jadwal Sekolah


## Instalasi

clone project atau download

```bash
  git clone https://github.com/lacsapadnan/Sistem-Informasi-Sekolah.git
  cd Sistem-Informasi-Sekolah
  npm install
  composer install
  cp .env.example .env
```

Buka `.env` dan atur database anda
```bash
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=
```

Install website
```bash
  php artisan key:generate
  php artisan migrate --seed
```

Jalankan website
```bash
  php artisan serve
```
## Default akun untuk testing

Admin
```bash
  email : admin@mail.com
  password : admin123
```

Guru
```bash
  email : budi@mail.com
  password : budi123

  email : gunawan@mail.com
  password : gunawan123
```

Siswa
```bash
  email : kevin@mail.com
  password : kevin123

  email : siska@mail.com
  password : siska123
```
## Update Selanjutnya

- Fitur Pengumuman Sekolah

- Fitur Absensi (Premium)

- Fitur Kuis atau Ujian (Premium)

- Fitur Tabungan Siswa via Midtrans (Premium)

- Fitur Pembayaran Sekolah via Midtrans (Premium)

### Aplikasi Sistem Informasi Akademik Sekolah
Aplikasi Sistem Informasi Sekolah (SIS) memiliki berbagai fungsi yang mendukung pengelolaan dan operasional sekolah secara efisien. Berikut beberapa fungsi utama dari aplikasi Sistem Informasi Sekolah
1. Manajemen Data Siswa:
Basis Data Siswa: Menyimpan dan mengelola informasi pribadi, akademis, dan lainnya mengenai setiap siswa.

2. Manajemen Data Guru dan Karyawan:
- Pemantauan Kinerja Guru: Melacak kinerja dan kehadiran guru.
- Informasi Karyawan: Menyimpan data dan informasi mengenai guru dan karyawan sekolah (Nama guru, NIP, dan mata pelajaran yang dikuasai)
- 
3. Manajemen Kurikulum:
- Pengelolaan Program Pembelajaran: Membantu menyusun dan melacak program pembelajaran.
- Penjadwalan Pelajaran: Membantu dalam penyusunan jadwal pelajaran.

4. Manajemen Nilai dan Absensi:
- Input Nilai: Memudahkan proses penginputan dan perhitungan nilai siswa.
- Absensi Siswa: Merekam dan melacak kehadiran siswa.

### Screenshot Tampilan Aplikasi Sistem Informasi Sekolah
### Halaman Login 👇
- Halaman login membantu melindungi data sensitif dan pribadi siswa, guru, dan staf sekolah. Hanya pengguna yang memiliki izin yang dapat mengakses informasi yang tersimpan dalam sistem.
- Proses login memastikan bahwa pengguna yang mencoba mengakses aplikasi adalah orang yang seharusnya. Ini dilakukan melalui penggunaan kombinasi nama pengguna (username) dan kata sandi (password), atau metode autentikasi lainnya seperti verifikasi dua faktor.

### Halaman dashboard 👇
Memberikan informasi tentang jumlah siswa, jumlah mata pelajaran, jumlah guru dan jumlah kelas.

### Halaman List Jurusan 👇
Halaman "List Jurusan" dalam aplikasi akademik sekolah memiliki beberapa fungsi penting untuk membantu pengelolaan dan pemantauan data terkait jurusan-jurusan yang tersedia di sekolah. Berikut adalah beberapa fungsi umum dari halaman "List Jurusan" dalam aplikasi akademik sekolah:

- Pendaftaran dan Informasi Jurusan:
Memuat daftar lengkap jurusan yang tersedia di sekolah.
Menyediakan informasi terkait setiap jurusan, seperti deskripsi singkat, tujuan, dan mata pelajaran yang diajarkan.

-Pemilihan Jurusan:
Memudahkan siswa dalam memilih jurusan yang sesuai dengan minat, bakat, dan tujuan karir mereka.

### Halaman List Mata Pelajaran 👇
Halaman ini menyediakan informasi terkait setiap daftar-daftar mata pelajaran yang ada di sebuah sekolah sesuai dengan jurusan yang siswa ambil.

### Halaman List Guru 👇
Halaman ini menyediakan informasi terkait daftar-daftar guru yang ada di sekolah. 
Halaman ini juga memberikan informasi tentang mata pelajaran yang diajarkan oleh guru tersebut.

### Halaman List Kelas 👇
Halaman ini menyediakan informasi terkait kelas-kelas yang ada mulai dari kelas X IPA IPS sampai kelas XII IPA IPS.
Halaman ini juga memberikan informasi tentang siapa wali kelas yang ada di kelas-kelas tersebut.

### Halaman List Siswa 👇
Halaman ini menyediakan informasi terkait siswa-siswa yang terdaftar di sekolah tersebut.
Halaman ini juga memberikan informasi mengenai nama, NIS, dan kelas dari setiap siswa-siswa tersebut.

### Halaman List Jadwal 👇
Halaman ini menyediakan informasi terkait jadwal-jadwal mata pelajaran yang ada di sekolah tersebut.
Halaman ini juga memberikan informasi mengenai mata pelajaran, kelas, hari, jam mulai dan jam kelas


