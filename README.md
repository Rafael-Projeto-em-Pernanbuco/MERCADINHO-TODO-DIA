
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mercadinho Todo Dia</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <h1>Mercadinho Todo Dia</h1>
    <p>Rua Deum Peixoto Nº108 - Exu, PE</p>
  </header>

  <!-- Seção do Tradutor -->
  <div id="google_translate_element"></div>

  <!-- Mapa -->
  <section class="mapa">
    <h2>Onde estamos</h2>
    <iframe
      src="https://www.google.com/maps?q=Rua%20Deum%20Peixoto%20N%C2%BA108%20Exu%20PE&output=embed"
      width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <!-- Cadastro de Email -->
  <section class="cadastro">
    <h2>Cadastre-se para novidades!</h2>
    <form id="emailForm">
      <input type="email" id="email" placeholder="Digite seu e-mail" required />
      <button type="submit">Cadastrar</button>
    </form>
    <p id="mensagem"></p>
  </section>

  <!-- Redes Sociais -->
  <section class="redes">
    <h2>Nos siga nas redes sociais</h2>
    <div class="botoes-redes">
      <a href="https://facebook.com" target="_blank">Facebook</a>
      <a href="https://instagram.com" target="_blank">Instagram</a>
      <a href="https://wa.me/5587999999999" target="_blank">WhatsApp</a>
      <a href="https://twitter.com" target="_blank">Twitter</a>
      <a href="https://www.kwai.com" target="_blank">Kwai</a>
      <a href="https://tiktok.com" target="_blank">TikTok</a>
      <a href="https://telegram.org" target="_blank">Telegram</a>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2025 Mercadinho Todo Dia - Todos os direitos reservados</p>
  </footer>

  <!-- Chat Online Tawk.to -->
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

  <!-- Google Tradutor -->
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({pageLanguage: 'pt'}, 'google_translate_element');
    }
  </script>
  <script src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <script src="script.js"></script>
</body>
</html>
