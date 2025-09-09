# Saya akan menjelaskan file Portofolio.html dan style.css

## 1. Portofolio.html

```html
<html>  
<head>  
  <title>Portofolio</title> // Judul halaman, muncul di tab browser  
  <link rel="stylesheet" href="style.css"> // Menghubungkan file CSS eksternal bernama style.css  
</head>  

<body>  
  <header>  
    <p>Biografi</p>  
    <h1>Darmawansyah murfa</h1>  
  </header>  

  <section> // Membagi konten dan membuat halaman jadi lebih rapi karena kontennya terpisah sesuai tema  
    <h2 style="text-align: center;">Tentang Saya</h2>  
    <img src="gambar.jpg" alt="Foto Darmawansyah Murfa" class="foto-saya" height="200px"> // Untuk menampilkan gambar profil  
    <p style="text-align: center;">saya adalah Mahasiswa s1 yang berkuliah di Universitas Negeri Makassar, dan saya sempat bersekolah di SMK negeri 2 makassar yang berletak di jalan pancasila</p> // Paragraf tentang biodata, teks ditengah  
  </section>  

  <section>  
    <h2 style="text-align: center;">Keterampilan</h2> // Judul sub-bagian keterampilan  
    <ul> // Berfungsi sebagai wadah/list utama  
      <li style="text-align: center;">HTML</li> // <li> digunakan untuk menampilkan satu per satu list 
      <li style="text-align: center;">CSS</li>  
      <li style="text-align: center;">C++</li>  
    </ul>  
  </section>  

  <section>  
    <h2 style="text-align: center;">Hobby</h2>  
    <ul>  
      <li style="text-align: center;">Main catur</li>  
      <li style="text-align: center;">Baca Komik</li>  
      <li style="text-align: center;">Bersepeda</li>  
    </ul>  
  </section>  

  <section> // Bagian keempat: Kontak/Sosial Media  
    <h2 style="text-align: center;">Kontak/sosial media</h2> // Judul sub-bagian kontak  
    <p style="text-align: center;"><a href="mailto:darmawansyahmurfa.com">Email: darmawansyahmurfa.com</a></p> // Link email  
    <p style="text-align: center;"><a href="https://www.instagram.com/wan_rinka/">IG: Wan_rinka</a></p> // Link ke Instagram  
    <p style="text-align: center;"><a href="https://www.tiktok.com/@.osamurinka">Tiktok: .OsamuRinka</a></p> // Link ke Tiktok  
  </section>  

  <footer> // Bagian footer (kaki halaman)  
    <p>DIbuat oleh darmawan</p>  
  </footer>  
</body>  
</html>  

```

## 2. style.css

```css
body {
  font-family: Arial, sans-serif; // Mengatur font utama menjadi Arial
  margin: 0; // Menghilangkan jarak default di tepi halaman
  padding: 0; // Menghilangkan ruang kosong di dalam body
}

header {
  background: #4a90e2; // Memberi background warna biru pada header
  color: white; // Mengatur warna teks jadi putih
  text-align: center; // Membuat teks di header rata tengah
  padding: 15px; // Memberi jarak dalam (atas, bawah, kiri, kanan) sebesar 15px
}

section {
  padding: 20px; // Memberi jarak dalam di setiap section agar kontennya tidak mepet
}

ul {
  padding: 0; // Menghapus padding default list (<ul>)
}

li {
  margin: 5px 0; // Jarak antar item list atas-bawah 5px
  padding: 8px; // Ruang dalam tiap item list 8px
  background: white; // Latar belakang item list warna putih
  border-radius: 4px; // Sudut tiap kotak list agak membulat (4px)
  box-shadow: 0 2px 3px rgba(0, 0, 0, 9); // Efek bayangan di bawah tiap list
  list-style: none; // Menghilangkan tanda bullet (•) bawaan list
}

.foto-saya {
  display: block; // Membuat gambar dianggap elemen blok (bisa atur posisi)
  margin: 20px auto;   // Memberi jarak atas-bawah 20px, dan "auto" kiri-kanan supaya gambar rata tengah
  border-radius: 10px;  // Membuat sudut foto sedikit membulat
}

footer {
  background: #4a90e2; // Latar belakang footer biru
  color: white; // Warna teks footer putih
  text-align: center; // Isi footer rata tengah
  padding: 15px // Jarak dalam footer 15px
}

```
