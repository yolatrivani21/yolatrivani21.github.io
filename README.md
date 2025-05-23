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
            text-align: center;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #8b5a2b;
            color: white;
            padding: 20px;
        }

        .navbar {
            background-color: #d2691e;
            padding: 15px;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            cursor: pointer;
        }

        .slide {
            display: none;
            margin: 50px auto;
            width: 80%;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .active {
            display: block;
        }

        h1,
        h2,
        h3 {
            color: #8b4513;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th,
        td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f4a460;
            color: white;
        }

        input,
        textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            background-color: #8b5a2b;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #a0522d;
        }

        footer {
            background-color: #8b5a2b;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <h1>Perpustakaan Yola Tri Vani</h1>
            <nav class="navbar">
                <a onclick="showSlide('home')">Home</a>
                <a onclick="showSlide('about')">About Me</a>
                <a onclick="showSlide('contact')">Contact Us</a>
            </nav>
        </div>
    </header>

    <div class="slide active" id="home">
        <h2>Selamat Datang di Perpustakaan Yola Tri Vani!</h2>
        <p>Website ini bekerja sama dengan Digilib Kampus Universitas Sumatera Utara (USU) untuk menyediakan akses ke berbagai koleksi buku digital dan fisik. Website ini bertujuan untuk meningkatkan literasi masyarakat melalui koleksi-koleksi buku yang dapat diakses dengan mudah.</p>
        <p>Anda dapat menjadi anggota dan memanfaatkan fasilitas perpustakaan ini untuk mengakses buku dan berbagai sumber daya pendidikan lainnya.</p>
        <p><a href="https://library.usu.ac.id/" target="_blank">Kunjungi Perpustakaan USU</a></p>
    </div>

    <div class="slide" id="about">
        <h2>About Me</h2>
        <p>Halaman ini berisi tentang saya</p>
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

    <div class="slide" id="contact">
        <h2>Formulir Pengaduan dan Saran</h2>
        <p>Silakan isi formulir di bawah ini untuk memberikan pengaduan atau saran:</p>
        <form id="contactForm">
            <table>
                <tr>
                    <th><label for="name">Nama Lengkap:</label></th>
                    <td><input type="text" id="name" name="name" required></td>
                </tr>
                <tr>
                    <th><label for="email">Email:</label></th>
                    <td><input type="email" id="email" name="email" required></td>
                </tr>
                <tr>
                    <th><label for="complaint">Pengaduan:</label></th>
                    <td><textarea id="complaint" name="complaint"></textarea></td>
                </tr>
                <tr>
                    <th><label for="suggestion">Saran:</label></th>
                    <td><textarea id="suggestion" name="suggestion"></textarea></td>
                </tr>
                <tr>
                    <td colspan="2" style="text-align: center;"><button type="submit">Kirim</button></td>
                </tr>
            </table>
        </form>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2025 Perpustakaan Yola Tri Vani</p>
        </div>
    </footer>

    <script>
        function showSlide(id) {
            let slides = document.querySelectorAll('.slide');
            slides.forEach(slide => {
                slide.classList.remove('active');
            });
            document.getElementById(id).classList.add('active');
        }

        document.getElementById("contactForm").addEventListener("submit", function (event) {
            event.preventDefault();
            let name = document.getElementById("name").value;
            let email = document.getElementById("email").value;
            let complaint = document.getElementById("complaint").value;
            let suggestion = document.getElementById("suggestion").value;
            if (name === "" || email === "") {
                alert("Nama dan Email wajib diisi!");
                return;
            }
            alert("Terima kasih " + name + "! Pengaduan atau saran Anda telah dikirim.");
            document.getElementById("contactForm").reset();
        });
    </script>
</body>

</html>
