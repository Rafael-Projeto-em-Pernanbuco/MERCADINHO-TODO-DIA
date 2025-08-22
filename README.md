
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Araujo - Exu-PE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: #000000;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3e2c23;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }

        .container {
            padding: 20px;
        }

        .services {
            background-color: #f3f3f3;
            padding: 20px;
            border-left: 5px solid #3e2c23;
            margin-bottom: 20px;
        }

        .map {
            margin: 20px 0;
            text-align: center;
        }

        footer {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 15px;
        }

        /* WhatsApp Chat Button */
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25d366;
            color: white;
            border-radius: 50px;
            padding: 12px 20px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
            z-index: 1000;
        }

        .translate {
            position: fixed;
            top: 10px;
            right: 10px;
            z-index: 1000;
        }
    </style>
</head>
<body>

    <!-- Google Translate -->
    <div class="translate" id="google_translate_element"></div>
    <script type="text/javascript">
      function googleTranslateElementInit() {
        new google.translate.TranslateElement({pageLanguage: 'pt', includedLanguages: 'en,es,fr,de,it'}, 'google_translate_element');
      }
    </script>
    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

    <header>
        <h1>Loja Araujo</h1>
        <p>Rua Padre Medeiros, N°00 - Centro, Exu-PE</p>
    </header>

    <nav>
        <a href="#servicos">Serviços</a>
        <a href="#localizacao">Localização</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <section id="servicos" class="services">
            <h2>Serviços</h2>
            <ul>
                <li>Temos Roupas de Varios Estilos</li>
                <li>Camisetas Polo</li>
                <li>Calças,Bermudas Bonés etc</li>
            </ul>
        </section>

        <section id="localizacao" class="map">
            <h2>Nosso Endereço</h2>
            <p>Rua Padre Medeiros, N°00 - Centro, Exu-PE</p>
            <iframe 
                src="https://www.google.com/maps?q=Rua+Padre+Medeiros,+00,+Exu-PE&output=embed"
                width="100%" 
                height="350" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </section>
    </div>

    <footer id="contato">
        <p>© 2025 LOJA ARAUJO - Todos os direitos reservados</p>
    </footer>

    <!-- WhatsApp Chat -->
    <a class="whatsapp-button" href="https://wa.me/5587900000000" target="_blank">
        💬 Fale conosco
    </a>

</body>
</html>
