
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #3498db;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header img {
            border-radius: 50%;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        h2 {
            color: #3498db;
            text-align: center;
        }

        section {
            margin: 20px 0;
        }

        .project {
            display: flex;
            justify-content: space-between;
            background-color: white;
            border-radius: 8px;
            margin: 10px 0;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .project img {
            width: 150px;
            height: 150px;
            object-fit: contain;
            border-radius: 8px;
        }

        .project-info {
            flex: 1;
            margin-left: 20px;
        }

        .project-info h3 {
            margin-top: 0;
        }

        .contact-info {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .contact-info ul {
            list-style: none;
            padding: 0;
        }

        .contact-info ul li {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #3498db;
            color: white;
        }
    </style>
</head>

<body>

    <header>
        <div class="container">
            <img src="https://avatars.githubusercontent.com/u/109207987?v=4" alt="Meu Avatar" width="150" />
            <h1>Bem-vindo ao meu Portfólio!</h1>
            <p>Explore meus projetos e conheça mais sobre minha jornada profissional</p>
        </div>
    </header>

    <div class="container">
        <section>
            <h2>🚀 Projetos</h2>

            <div class="project">
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Calculator_icon.png" alt="Calculadora" />
                <div class="project-info">
                    <h3>Calculadora em Python</h3>
                    <p><strong>Descrição:</strong> Uma aplicação simples de calculadora em Python para realizar operações básicas.</p>
                    <p><strong>Tecnologias:</strong> Python</p>
                    <p><a href="https://github.com/EdsonName/Meu_Portifolio/tree/main/calculadora">Acesse o projeto aqui</a></p>
                </div>
            </div>

            <div class="project">
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/Stock_Stock_Market_Icon.png" alt="Estoque" />
                <div class="project-info">
                    <h3>Sistema de Gerenciamento de Estoque</h3>
                    <p><strong>Descrição:</strong> Sistema para gerenciamento de estoque de produtos, com funcionalidades de adição, edição e exclusão.</p>
                    <p><strong>Tecnologias:</strong> Python, SQLite</p>
                    <p><a href="https://github.com/EdsonName/Meu_Portifolio/tree/main/sistema_de_estoque">Acesse o projeto aqui</a></p>
                </div>
            </div>

            <div class="project">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/HTML5_logo_icon.svg" alt="Desenvolvimento Web" />
                <div class="project-info">
                    <h3>Desenvolvimento de Sites</h3>
                    <p><strong>Descrição:</strong> Sites simples e responsivos criados com HTML, CSS e JavaScript.</p>
                    <p><strong>Tecnologias:</strong> HTML, CSS, JavaScript</p>
                    <p><a href="https://github.com/EdsonName/Meu_Portifolio/tree/main/desenvolvimento_de_sites">Acesse o projeto aqui</a></p>
                </div>
            </div>

        </section>

        <section class="contact-info">
            <h2>🧑‍💻 Sobre Mim</h2>
            <p>Sou estudante de **Análise e Desenvolvimento de Sistemas** e **Ciências Contábeis**. Tenho paixão por programação e busco constantemente aprender novas tecnologias.</p>
            <h3>Habilidades:</h3>
            <ul>
                <li>Python, JavaScript, HTML, CSS</li>
                <li>SQLite, MySQL</li>
                <li>Flask, Django (em aprendizado)</li>
                <li>Git, GitHub, Visual Studio Code</li>
            </ul>
        </section>

        <section class="contact-info">
            <h2>📬 Contato</h2>
            <p>Se você deseja discutir algum projeto ou tem interesse em colaborar, entre em contato comigo:</p>
            <ul>
                <li><strong>Email:</strong> <a href="mailto:seuemail@example.com">seuemail@example.com</a></li>
                <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/seu-linkedin" target="_blank">Meu LinkedIn</a></li>
                <li><strong>GitHub:</strong> <a href="https://github.com/EdsonName" target="_blank">Meu GitHub</a></li>
                <li><strong>Twitter:</strong> <a href="https://twitter.com/EdsonName" target="_blank">@EdsonName</a></li>
            </ul>
        </section>

        <section>
            <h2>📄 Visualize Meu Currículo</h2>
            <p>Confira meu currículo em PDF para mais informações sobre minha formação e experiências profissionais:</p>
            <p><a href="https://www.example.com/curriculo.pdf" target="_blank">Baixar Currículo</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Edson Name. Todos os direitos reservados.</p>
    </footer>

</body>

</html>
