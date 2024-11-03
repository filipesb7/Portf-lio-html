# Portfolio-html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Filipe Soares Barros</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Container Principal */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            border: 5px solid #007acc;
            border-radius: 10px;
            background-color: #f1f1f1;
        }

        /* Cabeçalho */
        .header {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            border-bottom: 2px solid #007acc;
            padding-bottom: 20px;
        }

        .header h1 {
            font-size: 2.5em;
            color: #333;
            margin-left: 20px;
        }

        .header .avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 4px solid #007acc;
            object-fit: cover;
        }

        /* Seção Sobre Mim */
        .about {
            padding: 20px;
            border: 2px dashed #007acc;
            border-radius: 8px;
            background-color: #f9f9f9;
            margin-bottom: 20px;
        }

        .about h2 {
            font-size: 1.8em;
            color: #007acc;
            margin-bottom: 10px;
        }

        .about p {
            color: #333;
            font-size: 1em;
            margin-bottom: 10px;
        }

        .about a {
            text-decoration: none;
            color: #007acc;
            font-weight: bold;
        }

        .about a:hover {
            text-decoration: underline;
        }

        /* Seção de Projetos */
        .projects {
            margin: 20px 0;
        }

        .projects h2 {
            font-size: 1.8em;
            color: #007acc;
            margin-bottom: 10px;
        }

        /* Projeto */
        .project {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            border: 2px solid #007acc;
            border-radius: 8px;
            overflow: hidden;
            background-color: #fff;
        }

        .project-image {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-right: 2px solid #007acc;
        }

        .project-info {
            padding: 20px;
            flex-grow: 1;
        }

        .project-info h3 {
            font-size: 1.5em;
            color: #333;
            margin-bottom: 5px;
        }

        .project-info p {
            color: #555;
            margin-bottom: 10px;
        }

        .project-info a {
            text-decoration: none;
            color: #007acc;
            font-weight: bold;
        }

        .project-info a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Container Principal -->
    <div class="container">

        <!-- Cabeçalho com Nome e Avatar -->
        <header class="header">
            <!-- Link do avatar -->
            <img src="https://img2.gratispng.com/20180625/req/aaz9k8xnr.webp" alt="Avatar de Filipe" class="avatar">
            <h1>Filipe Soares Barros</h1>
        </header>

        <!-- Informações Pessoais -->
        <section class="about">
            <h2>Sobre Mim</h2>
            <p>Sou um desenvolvedor apaixonado por tecnologia e inovação. Tenho experiência em desenvolvimento web, com foco em criar interfaces intuitivas e funcionais. Gosto de aprender novas tecnologias e me desafiar constantemente.</p>
            <p><a href="https://github.com/filipesb7" target="_blank">https://github.com/filipesb7</a></p>
        </section>

        <!-- Seção de Projetos -->
        <section class="projects">
            <h2>Projetos</h2>

            <!-- Projeto 1 - UcheinB -->
            <div class="project">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtgYUeZsVUupAoWLcsHfzbJZ3fKXdXBmQYOA&s" alt="Imagem de um vestido para o projeto UcheinB" class="project-image">
                <div class="project-info">
                    <h3>UcheinB</h3>
                    <p>Loja de Roupas</p>
                    <a href="https://github.com/filipesb7/ucheinb" target="_blank">Veja no GitHub</a>
                </div>
            </div>

            <!-- Projeto 2 - Projeto de Estrutura de Dados -->
            <div class="project">
                <img src="https://hermes.dio.me/articles/cover/92d355c1-a861-4a95-9b0f-13c55b17e7f0.png" alt="Imagem representando estrutura de dados" class="project-image">
                <div class="project-info">
                    <h3>Projeto de Estrutura de Dados</h3>
                    <p>Códigos da Atividade</p>
                    <a href="https://github.com/filipesb7/projeto-estrutura-dados" target="_blank">Veja no GitHub</a>
                </div>
            </div>
        </section>

    </div>

</body>
</html>
