<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORMULÁRIO</title>

    <link rel="stylesheet" href="style.css">
    <style>
        *, ::after, ::before {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(-120deg, #631aa7, #000000);
        }

        body,
        textarea {
            font-family: sans-serif;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 100vh;
        }

        .form_box {
            display: flex;
            flex-direction: column;
            background-color: aqua;
            border-radius: 8px;
            width: 700px;
            padding: 20px;
        }

        .form_box .title {
            padding: 24px 32px;
            font-size: 24px;
            border-bottom: thin solid;
        }

        .form_box form {
            display: flex;
            flex-direction: column;
            padding: 20px 0;
        }

        .form_box input,
        .form_box textarea {
            width: calc(100% - 20px);
            height: 48px;
            border-radius: 8px;
            border: thin solid #999;
            padding: 0 10px;
            margin: 10px 0;
            font-size: 16px;
        }

        .form_box textarea {
            height: 180px;
        }

        .form_box button {
            width: 200px;
            height: 48px;
            border-radius: 8px;
            background-color: #f54915;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        .form_box button:hover {
            background-color: #dc1717;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="form_box">
            <h2 class="title">Insira sua mensagem</h2>
            <form action="https://formsubmit.co/prof.carlos.costa@acad.ifma.edu.br" method="POST">
                <input type="text" name="name" placeholder="Seu nome" autocomplete="off" required>
                <input type="email" name="email" placeholder="Seu E-mail" autocomplete="off" required>
                <input type="text" name="subject" placeholder="Assunto">
                <textarea name="message" placeholder="Digite sua mensagem"></textarea>
                <button type="submit">Enviar sua mensagem</button>
            </form>
        </div>
    </div>
</body>
</html>
