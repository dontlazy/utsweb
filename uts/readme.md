# Profil Pribadi - Website

Berikut adalah kode untuk halaman web "Profil Pribadi".

## HTML (soal1.html):
```html
<!--Bayin-->

<html>
<head> 
    <title> UTS BAYIN </title> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="soal1.css"></head>
<body>
    <header>PROFIL PRIBADI</header>

    <div class="biodata">
        <img src="https://akcdn.detik.net.id/visual/2022/06/30/anime-spy-x-family-anya-forger_169.jpeg?w=650&q=80" alt="Foto Profil" class="biodata-img">
        <p>
            Halo, saya Bayin Ramadhan, biasa dipanggil Bayin. Saya asalnya dari Baubau, Sulawesi Tenggara.
            Saya sekarang kuliah di Universitas Negeri Makassar. Saya mengambil jurusan Teknik Komputer. 
            Banyak hal yang saya pelajari saat berkuliah di UNM, salah satunya adalah membuat web dan sekarang saya sedang mengerjakannya sebagai tugas UTS.
            Hobi saya yaitu masak dan juga menonton film.
        </p>
    </div>

    <div class="skills-section">
        <h2>Keterampilan</h2>
        <table>
            <tr>
                <th>Keterampilan</th>
                <th>Tingkat</th>
            </tr>
            <tr>
                <td>Java</td>
                <td>Menengah</td>
            </tr>
            <tr>
                <td>Pembuatan Website</td>
                <td>Menengah</td>
            </tr>
            <tr>
                <td>Matematika Diskrit</td>
                <td>Lanjutan</td>
            </tr>
        </table>
    </div>

    <nav>
        <a href="#kontak">Kontak</a>
    </nav>

    <!-- Bagian Kontak -->
    <div id="kontak">
        <h2>Kontak</h2>
        <p>Email: bayinrmdn@gmail.com</p>
    </div>

</body>
</html>