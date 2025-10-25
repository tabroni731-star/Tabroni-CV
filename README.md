<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coba Coba</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #004e92;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 5px;
        }

        main {
            max-width: 800px;
            margin: 40px auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #004e92;
            border-left: 5px solid #004e92;
            padding-left: 10px;
        }

        ul {
            list-style-type: none;
            padding-left: 0;
        }

        li {
            margin-bottom: 10px;
        }

        a {
            color: #004e92;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .info {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .info div {
            flex: 1 1 200px;
        }

        footer {
            text-align: center;
            background-color: #00264d;
            color: white;
            padding: 15px 10px;
            font-size: 0.9em;
        }

        @media (max-width: 600px) {
            header h1 { font-size: 2em; }
            main { padding: 20px; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Tabroni</h1>
        <p>PPIC Supervisor di perusahaan Flexible Packaging</p>
    </header>

    <main>
        <section>
            <h2>Kontak</h2>
            <div class="info">
                <div><strong>Email:</strong> <a href="mailto:tabroni.731@gmail.com">tabroni.731@gmail.com</a></div>
                <div><strong>Telepon:</strong> <a href="tel:+6282120057948">082120057948</a></div>
            </div>
        </section>

        <section>
            <h2>Pengalaman Kerja</h2>
            <ul>
                <li><strong>PPIC Supervisor</strong> – PT Sarana Prima Nusantara Abadi (2012 – 2021)</li>
                <li><strong>PPIC Staff</strong> – PT Trimitra Indoplast Mandiri (2022 – 2023)</li>
                <li><strong>PPIC Supervisor</strong> – PT Ultra Prima Plast (2024 – Sekarang)</li>
            </ul>
        </section>
    </main>

    <footer>
        &copy; 2025 Tabroni | Website Coba Coba
    </footer>
</body>
</html>
