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
            cursor: pointer;
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
        <p>Selamat Datang di Perpustakaan Yola Tri Vani!</p>
    </div>
    <div class="container" id="about">
        <h2>About Me</h2>
        <p>Nama: Yola Tri Vani</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="complaint">Pengaduan:</label>
            <input type="text" id="complaint" name="complaint" required><br><br>
            <label for="suggestion">Saran:</label>
            <input type="text" id="suggestion" name="suggestion" required><br><br>
            <button type="submit">Kirim</button>
        </form>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2025 Perpustakaan Yola Tri Vani. Semua hak dilindungi.</p>
        </div>
    </footer>
    <script>
        // Smooth Scroll
        document.querySelectorAll('.navbar a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Form Validation
        document.getElementById("contactForm").addEventListener("submit", function(event) {
            event.preventDefault();
            let name = document.getElementById("name").value.trim();
            let email = document.getElementById("email").value.trim();
            let complaint = document.getElementById("complaint").value.trim();
            let suggestion = document.getElementById("suggestion").value.trim();
            
            if (name === "" || email === "" || complaint === "" || suggestion === "") {
                alert("Harap isi semua kolom!");
            } else {
                alert("Terima kasih atas masukan Anda!");
                this.reset();
            }
        });
    </script>
</body>
</html>
