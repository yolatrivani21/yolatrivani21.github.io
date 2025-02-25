* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;  /* Latar belakang cerah */
    color: #333;
}

header {
    background-color: #2d3e50;  /* Latar belakang gelap untuk header */
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
