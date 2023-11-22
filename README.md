# AntigosBR
Tema:
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Seu Nome - Portfólio</title>
</head>
<body>
    <header>
        <nav>
            <h1>Antigos Br</h1>
        <p>Desenvolvedor Front-end</p><ul>
                <li><a href="#about">Sobre Mim</a></li>
                <li><a href="#projects">Projetos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
        
    </header>

    <section id="about">
        <h2>Biografia</h2>
        <!-- Bem-vindo ao emocionante mundo automotivo, onde paixão e expertise se encontram. Eu sou [Seu Nome], o fundador e apaixonado por carros por trás deste universo de quatro rodas que você está prestes a explorar.

Desde a minha infância, os motores rugindo e o design inovador dos veículos sempre me fascinaram. Essa paixão guiou meu caminho para a criação deste site, onde cada carro é cuidadosamente selecionado para atender aos mais altos padrões de desempenho, elegância e confiabilidade.

Com anos de experiência no mercado automotivo, desenvolvi um olhar crítico para identificar as jóias automotivas que oferecem uma experiência única de direção. Navegue pelo nosso inventário diversificado, onde cada modelo é escolhido a dedo para garantir que você encontre o carro dos seus sonhos.

Nosso compromisso vai além da venda. Buscamos proporcionar uma jornada transparente e personalizada, focada em atender às suas necessidades e superar suas expectativas. Acredito que cada carro tem uma história para contar, e estou aqui para ajudá-lo a encontrar o veículo que se alinha perfeitamente com a sua narrativa de vida.

Junte-se a nós nesta jornada automotiva, onde a excelência se encontra com a paixão. Estou ansioso para ajudá-lo a encontrar o carro perfeito que não apenas atenda às suas necessidades práticas, mas também desperte a chama da paixão automotiva em seu coração.

Vamos começar essa emocionante viagem juntos! -->
    </section>

    <section id="projects">
        <h2>Projetos</h2>
        <!-- Adicione detalhes dos seus projetos aqui -->
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <!-- Adicione um formulário de contato ou informações de contato aqui -->
    </section>

    <footer>
        <p>&copy; 2023 Seu Nome</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

<script>
    document.addEventListener("DOMContentLoaded", function () {
    // Adiciona um evento de clique para os links de navegação suave
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();

            const targetId = this.getAttribute('href').substring(1);
            const targetElement = document.getElementById(targetId);

            // Scroll suave até a seção desejada
            targetElement.scrollIntoView({
                behavior: 'smooth'
            });
        });
    });
});

</script>
