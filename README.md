<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recuperação de E-mail - Money Jurista</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 100%;
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            border: 2px solid green;
            border-radius: 10px;
            background-color: #1a1a1a;
        }
        input[type="email"] {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid green;
            border-radius: 5px;
        }
        button {
            background-color: blue;
            color: white;
            padding: 10px 20px;
            border: 2px solid green;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Recuperação de E-mail</h2>
        <p>Digite seu e-mail para recuperar sua conta</p>
        <form action="#" method="POST">
            <input type="email" name="email" placeholder="Digite seu e-mail" required>
            <br>
            <button type="submit">Recuperar Conta</button>
        </form>
    </div>
</body>
</html>
