## Day 4 - Belajar HTML

```
Nama: Habib Fatih Zanjabilah (312410135)
Kelas: TeknikInformatika 24A1
```
## Deskripsi Proyek

```
Pada hari ke-4 pembelajaran HTML ini, saya membuat Formulir Pendaftaran sederhana menggunakan elemen-elemen dasar HTML.
Tujuannya adalah memahami struktur dasar dari tag <form>, <input>, <label>, dan <textarea> dalam pembuatan form di halaman web.
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day4Belajarhtml</title>
</head>
<body>
    <center>
        <h1>Day4Belajarhtml</h1>
    </center>
    
<h3>Formulir Pendaftaran</h3>

<form>
  <label>Nama:</label><br>
  <input type="text" name="nama"><br><br>

  <label>Email:</label><br>
  <input type="email" name="email"><br><br>

  <label>Jenis Kelamin:</label><br>
  <input type="radio" name="gender" value="Laki-laki"> Laki-laki
  <input type="radio" name="gender" value="Perempuan"> Perempuan<br><br>

  <label>Hobi:</label><br>
  <input type="checkbox" name="hobi" value="Membaca"> Membaca
  <input type="checkbox" name="hobi" value="Menulis"> Menulis
  <input type="checkbox" name="hobi" value="Coding"> Coding<br><br>

  <label>Komentar:</label><br>
  <textarea name="komentar" rows="4" cols="40"></textarea><br><br>

  <input type="submit" value="Kirim">
</form>
</body>
</html>
