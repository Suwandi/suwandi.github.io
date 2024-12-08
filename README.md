<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suwandi Page</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #2c3e50;
            color: #ecf0f1;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .container {
            background-color: #34495e;
            padding: 20px;
            border-radius: 10px;
            max-width: 600px;
            width: 90%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        h1 {
            color: #e74c3c;
            margin-bottom: 20px;
        }
        .biodata p {
            margin: 10px 0;
        }
        .note {
            background-color: #95a5a6;
            padding: 10px;
            border-radius: 5px;
            margin: 20px 0;
            text-align: left;
        }
        .footer {
            margin-top: 20px;
            color: #7f8c8d;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Biodata Suwandi</h1>
        <div class="biodata">
            <p><strong>Nama:</strong> Suwandi</p>
            <p><strong>Email:</strong> suwandi@live.com</p>
            <p><strong>Phone:</strong> +62816888906</p>
        </div>
        <div class="note">
            <h2>Notes</h2>
            <p id="daily-note">Baru mengenal github 🎅</p>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 Suwandi.id</p>
    </div>
    <script>
        // Script untuk mengupdate catatan harian
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