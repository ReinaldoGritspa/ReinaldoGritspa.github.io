<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bem-Estar: Corpo, Mente e Espírito</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Alinha o conteúdo no topo */
            height: 100vh;
            padding: 20px;
            background-image: linear-gradient(to right, #4e5f77, #6b7d92);
        }

        .container {
            width: 100%;
            max-width: 800px;
            background-color: #fff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
            border-top: 4px solid #333;
            border-left: 4px solid #333;
            position: relative;
            transform: translateY(-20px); /* Desloca para cima */
        }

        .header {
            margin-bottom: 30px;
        }

        .header h1 {
            font-size: 36px;
            color: #333;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: bold;
            text-shadow: 1px 1px 2px #ccc;
        }

        .header p {
            font-size: 16px;
            color: #666;
            margin-top: 5px;
        }

        .image-container {
            margin-top: 20px;
            margin-bottom: 30px;
            overflow: hidden;
            border-radius: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .image-container img {
            width: 100%;
            height: auto;
            object-fit: contain; /* Ajusta a imagem para caber sem cortar */
            max-height: 400px; /* Ajuste o valor da altura máxima conforme necessário */
        }

        .section {
            margin-top: 30px;
            font-size: 18px;
            line-height: 1.6;
            color: #555;
        }

        .section h2 {
            font-size: 28px;
            color: #333;
            margin-bottom: 10px;
        }

        .btn {
            padding: 12px 25px;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            margin-top: 20px;
        }

        .btn:hover {
            background-color: #444;
        }

        .footer {
            margin-top: 40px;
            font-size: 14px;
            color: #777;
        }

        .footer a {
            color: #3498db;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Bem-Estar: Corpo, Mente e Espírito</h1>
            <p>Descubra a importância de manter o equilíbrio em sua vida através de diferentes aspectos de bem-estar.</p>
        </header>

        <div class="image-container">
            <img src="https://media.licdn.com/dms/image/v2/C4D12AQGgrAszdL6HSA/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1604168239054?e=1742428800&v=beta&t=LGzcoTADLp6ccOf_XTAJklhG_Pe8K7e9QaF7a6nryjQ" alt="Bem-Estar Físico">
        </div>

        <main>
            <section class="section">
                <h2>Importância do Bem-Estar</h2>
                <p>O bem-estar é um conceito amplo e envolve o equilíbrio entre vários aspectos da nossa vida. Entre eles, destacam-se:</p>
                <ul>
                    <li><strong>Físico:</strong> Manter a saúde física é essencial para a qualidade de vida. Isso inclui a prática regular de atividades físicas e alimentação saudável.</li>
                    <li><strong>Social:</strong> Ter boas relações sociais é fundamental para a nossa felicidade e satisfação. O apoio de amigos e família melhora nossa saúde mental.</li>
                    <li><strong>Ambiental:</strong> Estar em harmonia com o meio ambiente ajuda a reduzir o estresse e promove o bem-estar emocional. Cuidar do planeta é cuidar de si mesmo.</li>
                    <li><strong>Espiritual:</strong> Ter um sentido de propósito e conexão com algo maior pode trazer paz interior e equilíbrio emocional.</li>
                    <li><strong>Emocional:</strong> Gerenciar nossas emoções é essencial para a saúde mental. A prática da meditação e do mindfulness é uma excelente forma de trabalhar esse aspecto.</li>
                </ul>
            </section>

            <section class="section">
                <h2>Melhorando o Bem-Estar</h2>
                <p>Existem várias maneiras de melhorar esses aspectos do bem-estar, sendo duas que são abordadas em nossas páginas:</p>
                <h3>Página 2: Exercícios Físicos</h3>
                <p>A prática regular de atividades físicas é essencial para melhorar a saúde física, reduzir o estresse e promover uma melhor qualidade de vida.</p>
                
                <h3>Página 3: Yoga e Meditação</h3>
                <p>Explore o mundo da yoga e da meditação, práticas que ajudam a equilibrar o corpo e a mente, promovendo relaxamento e bem-estar emocional.</p>

                <a href="https://www.tuasaude.com/" target="_blank">
                    <button class="btn">Saiba Mais</button>
                </a>
            </section>
        </main>

        <footer class="footer">
            <p>&copy; 2025 Bem-Estar. Todos os direitos reservados.</p>
            <p>&copy; Reinaldo R. G. Junior - Informática 4B </p>
        </footer>
    </div>
</body>
</html>
