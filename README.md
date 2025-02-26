<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outlook</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffffff;
        }
        .login-container {
            width: 400px;
            text-align: left;
        }
        .login-container img {
            width: 180px;
            display: block;
            margin-bottom: 30px;
        }
        h2 {
            font-size: 24px;
            margin-bottom: 10px;
            font-weight: 400;
        }
        input {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #8c8c8c;
            border-radius: 2px;
            font-size: 16px;
            display: block;
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #0078d4;
            color: white;
            border: none;
            border-radius: 2px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }
        button:hover {
            background-color: #005a9e;
        }
        .link {
            color: #0078d4;
            text-decoration: none;
            display: inline-block;
            margin-top: 15px;
            font-size: 14px;
        }
        .link:hover {
            text-decoration: underline;
        }
        .warning {
            color: red;
            margin-top: 15px;
            font-weight: bold;
            display: none;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <!-- Vervang de URL hieronder met de definitieve link naar het Hoornbeeck-logo als dat nodig is -->
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Hoornbeeck-logo.png" alt="Hoornbeeck Logo">
        <h2>Aanmelden</h2>
        <input type="text" placeholder="E-mailadres, telefoonnummer of Skype" id="email">
        <a href="#" class="link">Geen account? Maak er een!</a>
        <a href="#" class="link">Problemen met aanmelden?</a>
        <button onclick="showWarning()">Volgende</button>
        <p class="warning" id="warning">LET OP! Dit is een demo phishingpagina.</p>
    </div>
    
    <script>
        function showWarning() {
            document.getElementById('warning').style.display = 'block';
        }
    </script>
</body>
</html>
