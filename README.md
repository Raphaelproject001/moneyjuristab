<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apostas de Placar - Futebol</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap" async defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#jogos">Jogos</a></li>
                <li><a href="#tabela">Tabela</a></li>
                <li><a href="#apostar">Apostar</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Bem-vindo ao site de apostas de placar!</h1>
        <p>Participe das apostas e acompanhe todos os placares dos jogos semanais.</p>
        <!-- Tradutor do Google -->
        <div id="google_translate_element"></div>
    </section>

    <section id="jogos">
        <h2>Jogos Semanais</h2>
        <!-- Lista de jogos e resultados (precisará de backend) -->
        <div id="lista-jogos"></div>
    </section>

    <section id="tabela">
        <h2>Tabela de Times</h2>
        <!-- Tabela e brasões (precisará de backend) -->
        <div id="tabela-times"></div>
    </section>

    <section id="apostar">
        <h2>Faça sua Aposta</h2>
        <form id="form-aposta">
            <label for="time-casa">Escolha o time da casa:</label>
            <select id="time-casa">
                <!-- Opções de times (precisará de backend) -->
            </select>
            <br>
            <label for="time-visitante">Escolha o time visitante:</label>
            <select id="time-visitante">
                <!-- Opções de times (precisará de backend) -->
            </select>
            <br>
            <label for="placar-casa">Placar time da casa:</label>
            <input type="number" id="placar-casa" min="0">
            <br>
            <label for="placar-visitante">Placar time visitante:</label>
            <input type="number" id="placar-visitante" min="0">
            <br>
            <label for="valor-aposta">Valor da Aposta:</label>
            <input type="number" id="valor-aposta" min="10" max="100" step="10">
            <br>
            <button type="submit">Apostar</button>
        </form>
    </section>

    <footer>
        <div id="google-map"></div>
    </footer>

    <script src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
    <script src="script.js"></script>
</body>
</html>
