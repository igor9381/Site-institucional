# Site insticucional
Projeto de página institucional em HTML

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>TecIgor</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <div class="container">
        <h1>TecIgor Soluções Digitais</h1>
        <p>Inovação e tecnologia para o seu negócio</p>
    </div>
</header>

<section class="sobre">
    <div class="container">
        <h2>Sobre Nós</h2>
        <p>
            Somos uma empresa focada no desenvolvimento de soluções digitais,
            ajudando negócios a crescer através da tecnologia e automação.
        </p>
    </div>
</section>

<section class="servicos">
    <div class="container">
        <h2>Serviços</h2>

        <div class="cards">
            <div class="card">
                <h3>Desenvolvimento Web</h3>
                <p>Criação de sites modernos e responsivos.</p>
            </div>

            <div class="card">
                <h3>Integração de Sistemas</h3>
                <p>Automatização e integração de plataformas.</p>
            </div>

            <div class="card">
                <h3>Consultoria em TI</h3>
                <p>Planejamento estratégico para evolução tecnológica.</p>
            </div>
        </div>
    </div>
</section>

<section class="contato">
    <div class="container">
        <h2>Contato</h2>
        <p>Email: igor.gp023@gmail.com</p>
        <p>Telefone: (32) 98510-4300</p>
    </div>
</section>



</body>
</html>




* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}


.container {
    width: 90%;
    max-width: 1000px;
    margin: auto;
    padding: 40px 0;
}


header {
    background-color: #1f2937;
    color: white;
    text-align: center;
    padding: 40px 0;
}


section {
    padding: 40px 0;
}

.sobre {
    background-color: white;
}

.servicos {
    background-color: #e5e7eb;
}

.contato {
    background-color: white;
}


.cards {
    display: flex;
    gap: 20px;
    margin-top: 20px;
}

.card {
    background: white;
    padding: 20px;
    flex: 1;
    border-radius: 8px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}


footer {
    background-color: #1f2937;
    color: white;
    text-align: center;
    padding: 20px;
}



