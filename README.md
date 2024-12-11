<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suwandi's Digital Business Card</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #2d2d2d;
            color: #cccccc;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .card {
            background-color: #3a3a3a;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px;
            padding: 20px;
            text-align: center;
            margin-bottom: 20px;
        }
        .card h1 {
            margin: 10px 0;
            color: #ffffff;
        }
        .card p {
            margin: 10px 0;
            font-size: 1.2em;
        }
        .card .icon {
            width: 20px;
            vertical-align: middle;
            margin-right: 10px;
        }
        .note-card {
            background-color: #3a3a3a;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            max-width: 400px;
            width: 100%;
            padding: 20px;
            text-align: center;
            margin-bottom: 20px;
        }
        .note-card h2 {
            margin: 0 0 10px 0;
            color: #ffffff;
        }
        .note-card textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            border-radius: 5px;
            border: none;
            resize: none;
        }
        footer {
            margin-top: 20px;
            font-size: 0.8em;
            color: #999999;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Suwandi</h1>
        <p><img src="https://img.icons8.com/ios-filled/50/ffffff/phone.png" alt="Phone Icon" class="icon">+62816888906</p>
        <p><img src="https://img.icons8.com/ios-filled/50/ffffff/email.png" alt="Email Icon" class="icon">suwandi@live.com</p>
    </div>
    <div class="note-card">
        <h2>Daily Note</h2>
        <textarea placeholder="Write your message here..."></textarea>
    </div>
    <footer>
        <p>&copy; 2024 suwandi.id</p>
    </footer>
</body>
</html>