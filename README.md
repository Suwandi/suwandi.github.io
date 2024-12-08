<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Natal</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff6347;
            font-size: 2.5em;
        }
        .biodata {
            margin: 20px 0;
        }
        .note {
            background-color: #faf2cc;
            padding: 10px;
            border-radius: 5px;
            margin: 20px 0;
        }
        .footer {
            margin-top: 20px;
        }
        .christmas-theme {
            margin: 20px 0;
        }
        .social {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="christmas-theme">
            <h1>🎄 Selamat Natal! 🎄</h1>
        </div>
        <div class="biodata">
            <p><strong>Nama:</strong> Suwandi</p>
            <p><strong>Email:</strong> suwandi@live.com</p>
            <p><strong>Nomor Telepon:</strong> +62816888906</p>
        </div>
        <div class="note">
            <h2>Catatan Harian:</h2>
            <p id="daily-note">Hari ini sangat menyenangkan! 🎅</p>
        </div>
        <div class="social">
            <h2>Bluesky Posts</h2>
            <p>Follow me on Bluesky: @suwandi.id</p>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 Suwandi's Natal Biodata</p>
    </div>
    <script>
        // Script to update the daily note
        function updateNote() {
            let note = prompt("Masukkan catatan harian baru:");
            if (note) {
                document.getElementById('daily-note').innerText = note;
            }
        }
        document.getElementById('daily-note').addEventListener('click', updateNote);
    </script>
</body>
</html>