<body>
    <header>
        <div class="container">
            <h1>Selamat Datang di Perpustakaan Yola Tri Vani</h1>
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
            <p>Selamat Datang di Perpustakaan Yola Tri Vani! Website ini bekerja sama dengan Digilab Kampus Universitas Sumatera Utara (USU) untuk menyediakan akses ke berbagai koleksi buku digital dan fisik. Kami bertujuan untuk meningkatkan literasi masyarakat melalui koleksi-koleksi buku yang dapat diakses dengan mudah.</p>
            <p>Anda dapat menjadi anggota dan memanfaatkan fasilitas perpustakaan kami untuk mengakses buku dan berbagai sumber daya pendidikan lainnya.</p>
        </div>
    </section>
<p><a href="https://library.usu.ac.id/" target="_blank">Kunjungi Perpustakaan USU</a></p>
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
                    <th>NIM</th>
                    <td>220709056</td>
                </tr>
                <tr>
                    <th>Program Studi</th>
                    <td>Perpustakaan dan Sains Informasi</td>
                </tr>
                <tr>
                    <th>Fakultas</th>
                    <td>Ilmu Budaya</td>
               </tr>
                <tr>
                    <th>Universitas</th>
                    <td>Universitas Sumatera Utara</td>
                </tr>
                <tr>
                    <th>Domisili</th>
                    <td>Medan</td>
                </tr>
                <tr>
                    <th>Email</th>
                    <td>yolatrivani21@gmail.com</td>
                </tr>
                <tr>
                    <th>Telepon</th>
                    <td>081536267845</td>
                </tr>
                <tr>
                    <th>Profesi</th>
                    <td>Pengelola Perpustakaan</td>
                </tr>
            </table>
        </div>
    </section>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan Yola Tri Vani</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 50%;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        h2 {
            text-align: center;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-top: 10px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            margin-top: 15px;
            padding: 10px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
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
</body>
</html>
