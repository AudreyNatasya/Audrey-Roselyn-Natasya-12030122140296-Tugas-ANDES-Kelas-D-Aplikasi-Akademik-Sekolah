
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


## Screenshots

![Login](https://i.ibb.co/QrvFVsq/download.png)

![Dashboard](https://i.ibb.co/4Vvff5F/Screenshot-3.jpg)


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

