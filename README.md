<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        section {
            padding: 50px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .btn {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .project-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .project {
            text-align: center;
            max-width: 250px;
        }
        .project img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        Portofolio Saya
    </header>
    <section>
        <div class="container">
            <h1>Halo, Saya Muhammad Syahid Islamy</h1>
            <p>Saya adalah siswa SMK Telkom Jakarta jurusan RPL angkatan 32.</p>
            <br>
            <p>Saat ini saya sedang mendalami bahasa pemrograman Java, Blockchain, Html, PHP, SQL dan CSS</p>
            <a href="#projects" class="btn">Lihat Proyek</a>
            <a href="#contact" class="btn">Hubungi Saya</a>
        </div>
    </section>
    <section id="projects">
    <div class="container">
        <h2>Proyek Saya</h2>
        <div class="project-grid">
            <div class="project">
                <img src="gambar1.jpg" alt="Proyek 1">
                <p>Proyek 1 - Deskripsi singkat</p>
            </div>
            <div class="project">
                <img src="gambar2.jpg" alt="Proyek 2">
                <p>Proyek 2 - Deskripsi singkat</p>
            </div>
            <div class="project">
                <img src="gambar3.jpg" alt="Proyek 3">
                <p>Proyek 3 - Deskripsi singkat</p>
            </div>
        </div>
    </div>
</section>
    <section id="contact">
        <div class="container">
            <h2>Kontak Saya</h2>
            <p>Email: sayberlord16.com</p>
            <p>Telp : 081400603688</a></p>
        </div>
    </section>
    <footer>
        &copy; Portofolio Muhammad Syahid
    </footer>
</body>
</html>
