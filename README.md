<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan Yola Tri Vani</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Selamat datang di Perpustakaan Yola Tri Vani</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>Home</h2>
            <p>Selamat datang di Perpustakaan Yola Tri Vani! Website ini bekerja sama dengan Digilab Kampus Universitas Sumatera Utara (USU) untuk menyediakan akses ke berbagai koleksi buku digital dan fisik. Kami bertujuan untuk meningkatkan literasi masyarakat melalui koleksi-koleksi buku yang dapat diakses dengan mudah.</p>
            <p>Anda dapat menjadi anggota dan memanfaatkan fasilitas perpustakaan kami untuk mengakses buku dan berbagai sumber daya pendidikan lainnya.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <h3>Biodata</h3>
            <table>
                <tr>
                    <th>Nama</th>
                    <td>Yola Tri Vani</td>
                </tr>
                <tr>
                    <th>Alamat</th>
                    <td>Jalan Pendidikan No. 10, Kota Yola</td>
                </tr>
                <tr>
                    <th>Email</th>
                    <td>yola@perpustakaanyola.com</td>
                </tr>
                <tr>
                    <th>Telepon</th>
                    <td>(021) 1234-5678</td>
                </tr>
                <tr>
                    <th>Profesi</th>
                    <td>Pengelola Perpustakaan</td>
                </tr>
            </table>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Jika Anda memiliki pertanyaan atau ingin menghubungi kami, silakan isi formulir di bawah ini:</p>
            <form action="#" method="POST">
                <label for="name">Nama Lengkap:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="phone">Nomor Telepon:</label>
                <input type="text" id="phone" name="phone" required>

                <label for="message">Pesan:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Kirim</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Perpustakaan Yola Tri Vani. Semua hak dilindungi.</p>
        </div>
    </footer>
</body>
</html>
