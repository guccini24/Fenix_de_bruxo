# Fenix_de_bruxo
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Pessoal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        main {
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        section {
            margin-bottom: 2rem;
        }
        h1, h2 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 0.5rem;
        }
        .project {
            background-color: white;
            padding: 1rem;
            margin-bottom: 1rem;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        form {
            background-color: white;
            padding: 1rem;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 0.5rem;
        }
        input, textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fénix De Bruxo 13</h1>
    </header>
    <main>
        <section id="biografia">
            <h2>Biografia</h2>
            <p>Olá! Somos a [Fénix De Bruxo]. Somos um grupo de [Música e Realização de eventos] com [10] anos de experiência em [Realização de Eventos]. Somos apaixonados por [Festa e Música] e temos trabalhado em diversos projetos que nos permitiram desenvolver nossas habilidades em [Festas e Música].</p>
            <p>Sou formado em [Sua Formação] pela [Sua Instituição]. Ao longo da minha carreira, tive a oportunidade de colaborar com equipes incríveis e contribuir para projetos significativos. Estou sempre em busca de novos desafios e oportunidades para crescer profissionalmente.</p>
        </section>
        <section id="projetos">
            <h2>Projetos</h2>
            <div class="project">
                <h3>Projeto 1</h3>
                <p>Descrição do Projeto 1. Este projeto envolveu [Detalhes do Projeto] e resultou em [Resultados/Impacto do Projeto].</p>
            </div>
            <div class="project">
                <h3>Projeto 2</h3>
                <p>Descrição do Projeto 2. Este projeto envolveu [Detalhes do Projeto] e resultou em [Resultados/Impacto do Projeto].</p>
            </div>
            <div class="project">
                <h3>Projeto 3</h3>
                <p>Descrição do Projeto 3. Este projeto envolveu [Detalhes do Projeto] e resultou em [Resultados/Impacto do Projeto].</p>
            </div>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form>
                <label for="nome">Nome</label>
                <input type="text" id="nome" name="nome" required>
                
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
                
                <label for="mensagem">Mensagem</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
</body>
</html>
