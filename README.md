<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Caprichado</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0c0c6b;
        }

        header {
            background-color: #0c0c6b;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }

        section {
            padding: 50px;
            text-align: center;
        }

        /* Aumentando o tamanho da fonte do conteúdo das seções */
        section p, section td {
            font-size: 24px;
            line-height: 1.6;
        }

        section:nth-child(odd) {
            background-color: #ffffff;
        }

        section:nth-child(even) {
            background-color: #eeeeee;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #0c0c6b;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #0c0c6b;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Bem-vindo ao Meu Site sobre os Lípideos</h1>
    <p></p>
</header>

<section>
    <h2>Abacate</h2>
    <p>
        <table>
            <tr>
                <td><img width="300" height="150" src="download.webp" /></td>
                <td>O abacate é uma fruta cremosa e versátil, rica em gorduras saudáveis, principalmente o ácido oleico, que auxilia na redução do colesterol ruim (LDL) e aumenta o colesterol bom (HDL). É também uma excelente fonte de fibras, vitaminas como a K, E e C, e minerais como potássio. O abacate pode ser consumido puro, em vitaminas, saladas, torradas ou guacamole, tornando-se uma opção nutritiva para incluir na dieta diária.</td>
            </tr>
        </table>
    </p>
    <a href="#secao2" class="btn">Ir para a Seção 2</a>
</section>

<section id="secao2">
    <h2>Sementes de Abóbora</h2>
    <p>
        <table>
            <tr>
                <td><img width="300" height="150" src="download (4).jpeg" /></td>
                <td>As sementes de abóbora são pequenos tesouros nutricionais repletos de benefícios para a saúde. Ricas em proteínas, fibras e gorduras saudáveis, elas também contêm uma grande quantidade de minerais essenciais, como magnésio, zinco, ferro e fósforo. Essas sementes são conhecidas por suas propriedades anti-inflamatórias e antioxidantes, além de auxiliarem na saúde do coração, do sistema imunológico e na manutenção de ossos fortes.</td>
            </tr>
        </table>
    </p>
    <a href="#secao3" class="btn">Ir para a Seção 3</a>
</section>

<section id="secao3">
    <h2>Nozes</h2>
    <p>
        <table>
            <tr>
                <td><img width="300" height="150" src="download (3).jpeg" /></td>
                <td>As nozes são superalimentos ricos em nutrientes como ácidos graxos ômega-3, fibras, proteínas e antioxidantes. Seu consumo regular contribui para a saúde do coração, melhora a função cerebral e fortalece o sistema imunológico. Versáteis na cozinha, podem ser consumidas como lanche ou ingrediente de receitas doces e salgadas. Além disso, as nozes são excelentes para manter a saciedade e fornecer energia ao longo do dia.</td>
            </tr>
        </table>
    </p>
    <a href="#secao4" class="btn">Ir para a Seção 4</a>
</section>

<section id="secao4">
    <h2>Salmão</h2>
    <p>
        <table>
            <tr>
                <td><img width="300" height="150" src="images (5).jpeg" /></td>
                <td>O salmão é um peixe gorduroso altamente nutritivo, conhecido por ser uma das melhores fontes de ácidos graxos ômega-3. Esse nutriente é essencial para a saúde do coração e do cérebro. Além disso, o salmão é rico em proteínas de alta qualidade, vitaminas como B12 e D, e minerais como selênio. Seja grelhado, assado ou cru, como no sushi, o salmão é uma escolha deliciosa e saudável para qualquer refeição.</td>
            </tr>
        </table>
    </p>
    <a href="#top" class="btn">Voltar ao topo</a>
</section>

<footer>
    <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
</footer>

</body>
</html>

