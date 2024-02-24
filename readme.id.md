![Laravel](https://laravel.com/assets/img/components/logo-laravel.svg)

<h1 align="center">Aplikasi Silsilah Keluarga</h1>

## Tentang
Aplikasi silsilah keluarga untuk mempermudah pendataan keluarga kita.

## Pemanfaatan
1. Melihat Silsilah keluarga
2. Melihat data ahli waris

## Fitur
Aplikasi ini menggunakan Bahasa Indonesia dan Bahasa Inggris, diatur pada `config.locale`.

### Konsep
1. Satu orang memiliki satu ayah (belum sebagai tentu orang tua)
2. Satu orang memiliki satu ibu (belum sebagai tentu orang tua)
3. satu orang memiliki satu orang tua
4. Satu orang memiliki 0 s/d beberapa anak
5. Satu orang bisa memiliki pasangan (Istri/Suami)
6. Satu pasangan bisa memiliki 0 s/d beberapa anak
7. Satu orang laki-laki bisa memiliki maksimal 4 pasangan yang tidak cerai (TODO)
8. Satu orang perempuan bisa memiliki maksimal 1 pasangan yang tidak cerai (TODO)
9. Satu orang perempuan yang suaminya meninggal otomatis set tanggal cerai (pada data pasangan) (TODO)

### Input ke sistem
1. Input Nama dan Jenis Kelamin
2. Tambah Ayah
3. Tambah Ibu
4. Tambah Pasangan
5. Tambah Anak

### Data Orang
1. Nama Panggilan
2. Jenis Kelamin
3. Nama Lengkap
4. Tanggal Lahir
5. Tanggal Meninggal (atau cukup tahun)
6. Alamat
7. Telp
8. Email

### Data Pasangan (TODO)
1. Suami
2. Istri
3. Tanggal menikah
4. Tanggal Cerai
5. Alamat
