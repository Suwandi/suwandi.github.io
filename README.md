<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keseharian Suwandi</title>
    <style>
        /* Gaya global */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            min-height: 100vh;
        }

        header {
            width: 100%;
            background: linear-gradient(135deg, #4caf50, #2e7d32);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 24px;
        }

        .daily-activity {
            width: 90%;
            max-width: 600px;
            background: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .daily-activity h2 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #333;
        }

        .daily-activity p {
            font-size: 16px;
            color: #555;
            line-height: 1.6;
        }

        footer {
            width: 100%;
            background: #4caf50;
            color: white;
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 5px 0;
            font-size: 14px;
        }

        footer a {
            color: #ffd700;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 20px;
            }

            .daily-activity h2 {
                font-size: 18px;
            }

            footer p {
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <!-- Bagian header -->
    <header>
        <h1>Keseharian Suwandi</h1>
    </header>

    <!-- Kegiatan hari ini -->
    <section class="daily-activity">
        <h2>Hari ini</h2>
        <p>Aku di rumah aja karena hujan.</p>
    </section>

    <!-- Kontak -->
    <footer>
        <p>📞 Hubungi saya: +62 816 888 906</p>
        <p>✉ Email: <a href="mailto:suwandi@live.com">suwandi@live.com</a></p>
    </footer>
</body>
</html>