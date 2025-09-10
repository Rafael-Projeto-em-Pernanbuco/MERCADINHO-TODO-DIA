
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Mercadinho Todo Dia</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #001f3f; /* azul escuro */
      color: white;
    }

    header {
      background-color: #001530;
      text-align: center;
      padding: 30px;
    }

    header h1 {
      color: red;
      font-size: 2.5em;
    }

    header p {
      color: yellow;
      font-size: 1.2em;
    }

    section {
      padding: 20px;
      text-align: center;
    }

    h2 {
      color: yellow;
    }

    .cadastro input[type="email"] {
      padding: 10px;
      width: 250px;
      border-radius: 5px;
      border: none;
    }

    .cadastro button {
      padding: 10px 20px;
      background-color: red;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .cadastro button:hover {
      background-color: darkred;
    }

    .redes a {
      display: inline-block;
      margin: 10px;
      padding: 10px 15px;
      background-color: yellow;
      color: #001f3f;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    iframe {
      border-radius: 10px;
      margin-top: 10px;
    }

    footer {
      background-color: #000c1a;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }

    #google_translate_element {
      position: fixed;
      top: 10px;
      right: 10px;
      z-index: 9999;
    }
  </style>
</head>
<body>

  <!-- Tradutor -->
  <div id="google_translate_element"></div>

  <!-- Cabeçalho -->
  <header>
    <h1>Mercadinho Todo Dia</h1>
    <p>Rua Deum Peixoto Nº108 - Exu, PE</p>
  </header>

  <!-- Mapa -->
  <section>
    <h2>Localização</h2>
    <iframe
      src="https://www.google.com/maps?q=Rua+Deum+Peixoto+108,+Exu,+PE&output=embed"
      width="90%" height="300" allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <!-- Cadastro -->
  <section class="cadastro">
    <h2>Cadastre seu e-mail para receber novidades!</h2>
    <form onsubmit="cadastrarEmail(event)">
      <input type="email" id="email" placeholder="Digite seu e-mail" required>
      <button type="submit">Cadastrar</button>
    </form>
    <p id="mensagem-cadastro"></p>
  </section>

  <!-- Redes Sociais -->
  <section class="redes">
    <h2>Redes Sociais</h2>
    <a href="https://facebook.com" target="_blank">Facebook</a>
    <a href="https://instagram.com" target="_blank">Instagram</a>
    <a href="https://wa.me/5587999980935" target="_blank">WhatsApp</a>
    <a href="https://twitter.com" target="_blank">Twitter</a>
    <a href="https://www.kwai.com" target="_blank">Kwai</a>
    <a href="https://tiktok.com" target="_blank">TikTok</a>
    <a href="https://telegram.org" target="_blank">Telegram</a>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2025 Mercadinho Todo Dia. Todos os direitos reservados.</p>
  </footer>

  <!-- Script de cadastro -->
  <script>
    function cadastrarEmail(event) {
      event.preventDefault();
      const email = document.getElementById('email').value;
      const mensagem = document.getElementById('mensagem-cadastro');
      mensagem.textContent = `Obrigado por se cadastrar, ${email}!`;
      event.target.reset();
    }
  </script>

  <!-- Google Tradutor -->
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({
        pageLanguage: 'pt',
        includedLanguages: 'en,es,fr,de,it,pt',
        layout: google.translate.TranslateElement.InlineLayout.SIMPLE
      }, 'google_translate_element');
    }
  </script>
  <script src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <!-- Chat Tawk.to (atendimento online) -->
  <script type="text/javascript">
    var Tawk_API = Tawk_API || {}, Tawk_LoadStart = new Date();
    (function () {
      var s1 = document.createElement("script"), s0 = document.getElementsByTagName("script")[0];
      s1.async = true;
      s1.src = 'https://embed.tawk.to/SEU_ID_AQUI/default';
      s1.charset = 'UTF-8';
      s1.setAttribute('crossorigin', '*');
      s0.parentNode.insertBefore(s1, s0);
    })();
  </script>

</body>
</html>
