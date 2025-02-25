<!DOCTYPE html>
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
        }
        .header {
            background-color: #f5e6cc;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        .navbar {
            background-color: #8b5a2b;
            padding: 15px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .container {
            margin: 50px auto;
            width: 80%;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="header">Perpustakaan Yola Tri Vani</div>
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#contact">Contact Us</a>
    </div>
    <div class="container" id="home">
        <h2>Home</h2>
        <p>Website ini bekerja sama dengan Digilib USU untuk menyediakan sumber daya akademik terbaik.</p>
    </div>
    <div class="container" id="about">
        <h2>About Me</h2>
        <p><strong>Nama:</strong> Yola Tri Vani</p>
        <p><strong>NIM:</strong> 12345678</p>
        <p><strong>Program Studi:</strong> Ilmu Perpustakaan</p>
        <p><strong>Fakultas:</strong> Ilmu Budaya</p>
        <p><strong>Universitas:</strong> Universitas Sumatera Utara</p>
        <p><strong>Domisili:</strong> Medan</p>
        <p><strong>Email:</strong> yola@example.com</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="message">Pesan:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
            <button type="submit">Kirim</button>
        </form>
    </div>
</body>
</html>
