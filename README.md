# aula_Git
#Aula de GitHub para o ensino médio integrado#

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Um site de exemplo bem estruturado e responsivo">
    <title>Meu Primeiro Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <nav class="nav">
            <h1 class="logo">Meu Site</h1>
            <ul class="nav-links">
                <li><a href="#inicio">Início</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero" id="inicio">
            <h1>Bem-vindo ao Meu Site!</h1>
            <p>Criado com HTML e CSS puro, seguindo boas práticas.</p>
            <button class="btn btn-primary" id="btn-interact">Clique aqui</button>
        </section>

        <section class="container" id="sobre">
            <article>
                <h2>Sobre Mim</h2>
                <p>Olá! Este é um exemplo de site básico para quem está começando a aprender desenvolvimento web.</p>
                <p>O site foi criado com foco em:</p>
                <ul>
                    <li>Semântica HTML adequada</li>
                    <li>CSS responsivo e moderno</li>
                    <li>Acessibilidade</li>
                    <li>Boas práticas de desenvolvimento</li>
                </ul>
            </article>
        </section>

        <section class="container" id="contato">
            <h2>Entre em Contato</h2>
            <form class="form" action="#" method="POST">
                <div class="form-group">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Enviar</button>
            </form>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 - Meu Projeto Web. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
