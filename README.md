# Catalogo-frota
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bem-vindo ao Agro</title>
  <style>
    /* Estilização da página */
    body, html {
      margin: 0;
      padding: 0;
      height: 110%;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      color: black;
    }
    
    /* Imagem de fundo */
    body {
      background-image: url("../../PLano%20de%20fundo.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      filter: brightness(0.65);
    }
    
    /* Conteúdo principal */
    .content {
      text-align: center;
    }
    .content h1 {
      font-size: 4em;
      margin: 0;
    }
    .content p {
      font-size: 1.2em;
    }
    
    /* Botão */
    .btn {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #4CAF50;
      border: none;
      color: black;
      font-size: 1em;
      cursor: pointer;
      border-radius: 5px;
    }
    .btn:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
<!-- Conteúdo centralizado -->
<div class="content">
  <h1>Bem-vindo ao Agro</h1>
  <p>Explore as melhores soluções para o agronegócio.</p>
  <button class="btn" onclick="window.location.href='catalogo_frotas.html'">Entrar</button>
  <button class="btn" onclick="window.location.href='https://app.powerbi.com/groups/me/apps/191249fc-0618-4d9d-8f87-07765f02a680/reports/157a94e0-0c16-45e8-a23d-1ba833d5b31f/1933ff864ae62d35316b?ctid=38e97b4e-4339-49cc-b7c4-719dfb792f8b&experience=power-bi'">Ir para Informações da frota</button>
</div>

  
  <script>
    // Função para abrir a página catálogo de frotas
    function abrirCatalogo() {
      window.location.href = 'catalogo_frotas.html'
    }
  </script>
</body>
</html>
