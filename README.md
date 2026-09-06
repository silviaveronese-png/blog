<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog da Silvia</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f8d7e8, #d8c4f1);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .slide {
            width: 90%;
            max-width: 1000px;
            min-height: 550px;
            background: white;
            border-radius: 25px;
            padding: 60px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .texto {
            flex: 1;
        }

        .texto h1 {
            color: #9b4d80;
            font-size: 55px;
            margin-bottom: 10px;
        }

        .texto h2 {
            color: #555;
            font-size: 25px;
            margin-bottom: 25px;
        }

        .texto p {
            color: #666;
            font-size: 20px;
            line-height: 1.7;
        }

        .destaque {
            color: #9b4d80;
            font-weight: bold;
        }

        .foto {
            width: 280px;
            height: 280px;
            border-radius: 50%;
            background: linear-gradient(135deg, #c77dbb, #8e6bbd);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 80px;
            font-weight: bold;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }

        .rodape {
            margin-top: 30px;
            color: #9b4d80;
            font-weight: bold;
        }

        @media (max-width: 700px) {
            .slide {
                flex-direction: column-reverse;
                text-align: center;
                padding: 35px;
            }

            .foto {
                width: 200px;
                height: 200px;
                font-size: 60px;
            }

            .texto h1 {
                font-size: 42px;
            }
        }
    </style>
</head>

<body>

    <section class="slide">

        <div class="texto">
            <h1>Olá, eu sou a Silvia! 💜</h1>

            <h2>Bem-vindos ao meu blog</h2>

            <p>
                Meu nome é <span class="destaque">Silvia</span> e este é
                um espaço onde posso compartilhar um pouco sobre mim,
                meus interesses, meus sonhos e as coisas que fazem parte
                da minha vida.
            </p>

            <p>
                Gosto de aprender coisas novas, conhecer pessoas e
                registrar momentos especiais. ✨
            </p>

            <div class="rodape">
                🌸 Um pouco de mim, do meu jeito!
            </div>
        </div>

        <div class="foto">
            S
        </div>

    </section>

</body>
</html>
