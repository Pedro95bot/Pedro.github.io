<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jurassic Park</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Jurassic Park</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#dinos">Dinossauros</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Introdução</h2>
        <p>Explore o mundo dos dinossauros e descubra as maravilhas do Jurassic Park.</p>
    </section>
    <section id="sobre">
        <h2>Sobre</h2>
        <p>Jurassic Park é um destino emocionante onde você pode presenciar a vida jurássica bem de perto.</p>
    </section>
    <section id="dinos">
        <h2>Dinossauros</h2>
        <ul>
            <li>Tiranossauro Rex</li>
            <li>Velociraptor</li>
            <li>Triceratops</li>
        </ul>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <button type="submit">Enviar</button>
        </form>
    </section>
    <script src="script.js"></script>
</body>
</html>
