# Saya akan menjelaskan file Portofolio.html dan style.css

## 1. Portofolio.html

```html
<html>
<head>
  <title>Portofolio</title> <!-- Judul halaman, muncul di tab browser -->
  <link rel="stylesheet" href="style.css"> <!-- Menghubungkan file CSS eksternal bernama style.css -->
</head>

<body>
  <header>
    <p>Biografi</p>
    <h1>Darmawansyah murfa</h1>
  </header>

  <section> <!-- Membagi konten dan membuat halaman jadi lebih rapi -->
    <h2 style="text-align: center;">Tentang Saya</h2>
    <img src="gambar.jpg" alt="Foto Darmawansyah Murfa" class="foto-saya" height="200px"> <!-- menampilkan foto -->
    <p style="text-align: center;">saya adalah Mahasiswa s1 ...</p> <!-- paragraf biodata -->
  </section>
</body>
</html>
```

## 2. style.css

```css
body {
  background-color: lightblue; /* warna latar belakang */
}

h1 {
  text-align: center; /* teks judul di tengah */
}
```
