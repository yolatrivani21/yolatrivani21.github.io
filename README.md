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
            <p>Jika Anda memiliki pengaduan atau saran, silakan isi formulir di bawah ini:</p>
            <form action="#" method="POST">
                <label for="name">Nama Lengkap:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="complaint">Pengaduan:</label>
                <textarea id="complaint" name="complaint"></textarea>

                <label for="suggestion">Saran:</label>
                <textarea id="suggestion" name="suggestion"></textarea>

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
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;  /* Latar belakang cerah untuk keseluruhan halaman */
    color: #333;
}

header {
    background-color: #2d3e50;  /* Warna gelap untuk header */
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2em;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 50px 20px;
    background-color: #ffffff;  /* Latar belakang putih untuk setiap section */
    margin: 20px 0;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section h2 {
    font-size: 2em;
    color: #333;
    margin-bottom: 15px;
}

section h3 {
    font-size: 1.5em;
    color: #444;
    margin-bottom: 15px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
}

table th, table td {
    padding: 10px;
    text-align: left;
    border-bottom: 1px solid #ddd;
}

form label {
    display: block;
    margin: 10px 0 5px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    background-color: #2d3e50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

footer {
    background-color: #2d3e50;
    color: white;
    text-align: center;
    padding: 15px 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

@media screen and (max-width: 768px) {
    nav ul {
        flex-direction: column;
        margin-top: 20px;
    }

    nav ul li {
        margin: 10px 0;
    }
}
