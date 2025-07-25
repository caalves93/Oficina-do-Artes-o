<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oficina do Artesão - Links</title>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            background-color: #F5F5DC; /* Bege claro para o fundo */
            color: #333333;
            padding: 20px;
            box-sizing: border-box;
        }
        .container {
            background-color: #FFFFFF;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 90%;
            max-width: 450px;
            border: 2px solid #8B4513; /* Marrom Madeira */
        }
        .logo {
            width: 200px; /* Ajustado para um tamanho maior */
            height: auto;
            margin-bottom: 25px;
            /* Remover border-radius e border para o logo específico */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
        }
        h1 {
            font-family: 'Merriweather', serif;
            color: #333333; /* Preto/Grafite */
            margin-bottom: 30px;
            font-size: 2.2em;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
            display: none; /* Ocultar o h1, pois o logo já tem o nome */
        }
        .link-button {
            display: block;
            width: calc(100% - 20px); /* Ajuste para padding */
            padding: 15px 20px;
            margin: 15px auto;
            background-color: #A0522D; /* Sienna - Marrom mais escuro */
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1.1em;
            font-weight: 600;
            transition: background-color 0.3s ease, transform 0.2s ease;
            border: none;
            cursor: pointer;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .link-button:hover {
            background-color: #8B4513; /* Marrom Sela - Mais escuro no hover */
            transform: translateY(-2px);
        }
        .whatsapp-button {
            background-color: #228B22; /* Verde Floresta */
        }
        .whatsapp-button:hover {
            background-color: #1DA851; /* Verde mais escuro no hover */
        }
        .drive-button {
            background-color: #4285F4; /* Azul Google Drive */
        }
        .drive-button:hover {
            background-color: #3367D6; /* Azul mais escuro no hover */
        }
        /* Ícones (opcional, se for usar) */
        .link-button::before {
            content: '';
            display: inline-block;
            width: 20px;
            height: 20px;
            vertical-align: middle;
            margin-right: 10px;
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center;
        }
        .whatsapp-button::before {
            background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgZmlsbD0iY3VycmVudENvbG9yIiBjbGFzcz0iYmkgYmktc2VuZC1maWxsIiB2aWV3Qm94PSIwIDAgMTYgMTYiPjxwYXRoIGQ9Ik0xNS45NjQgMy4zNzJhLjI1LjI1IDAgMCAwLS4xMS0uMDY2TDEuOTYyLjAxOGEuMjUuMjUgMCAwIDAtLjE3Mi4wMThhLjI1LjI1IDAgMCAwLS4wNzIuMDY0Yy0uMDQ0LjA3My0uMDY3LjE2Mi0uMDY0LjI1bC43MjUgNS40MzhhLjI1LjI1IDAgMCAwIC4wNzIuMTc2bDUuMzM3IDQuNzQ0Yy4wNzIuMDY0LjE3Mi4wOTYuMjY0LjA5NmEuMjUuMjUgMCAwIDAgLjE3Mi0uMDQ4bDUuOTQ1LTMuMjQ0YS4yNS4yNSAwIDAgMCwuMTEtLjA2NkwxNS45NjQgMy4zNzJ6TTIuNDY0IDEuNTI4bDEyLjA3NiAyLjM4NC01LjY2IDMuMDk0LTYuNDg0LDUuNDc4eiIvPjwvc3ZnPg=='); /* Exemplo de ícone WhatsApp */
        }
        .drive-button::before {
            background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgZmlsbD0iY3VycmVudENvbG9yIiBjbGFzcz0iYmkgYmktZmlsZS1lYXNlIiB2aWV3Qm94PSIwIDAgMTYgMTYiPjxwYXRoIGQ9Ik04IDYuNWEuNS41IDAgMCAxIC41LjVoMi41YS41LjUgMCAwIDEgLjUuNXYyLjVhLjUuNSAwIDAgMS0uNS41aC0yLjVhLjUuNSAwIDAgMS0uNS0uNXYtMi41eiIvPjxwYXRoIGQ9Ik00IDBhMiAyIDAgMCAwLTIgMnYxMmEyIDIgMCAwIDAgMiAyaDhhMiAyIDAgMCAwIDItMlYyYTIgMiAwIDAgMC0yLTJINXptMCAxLjVoN2ExLjUgMS41IDAgMCAxIDEuNSAxLjV2MTJhMS41IDEuNSAwIDAgMS0xLjUgMS41SDVhMS41IDEuNSAwIDAgMS0xLjUtMS41VjJhMS41IDEuNSAwIDAgMSAxLjUtMS41eiIvPjwvc3ZnPg=='); /* Exemplo de ícone Drive */
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="upload/1000201374.png" alt="Logo Oficina do Artesão" class="logo">
        <h1>Oficina do Artesão</h1>
        <a href="https://drive.google.com/drive/folders/10JvnqMMP_ClHDz2YdYab2o7Di5kdjg8A" target="_blank" class="link-button drive-button">
            Acessar Acervo (Google Drive)
        </a>
        <a href="https://wa.me/5514991658041" target="_blank" class="link-button whatsapp-button">
            Falar no WhatsApp
        </a>
    </div>
</body>
</html>
