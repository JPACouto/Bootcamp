# Este é um repositório criado com a finalidade de armazenar os trabalhos realizados nas aulas durante o curso!
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Projetos Faculdade</title>
  <style>
    :root {
      --bg-color: #f5f7fa;
      --card-bg: #ffffff;
      --primary: #6c63ff;
      --text: #333;
      --subtext: #666;
    }

    body {
      margin: 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-color);
      color: var(--text);
    }

    header {
      background-color: var(--primary);
      padding: 20px 0;
      color: white;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      padding: 0 20px;
    }

    .card {
      background-color: var(--card-bg);
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s, box-shadow 0.2s;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }

    .card h3 {
      margin: 0 0 10px 0;
      color: var(--primary);
    }

    .card p {
      margin: 0;
      color: var(--subtext);
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: var(--subtext);
      font-size: 0.85rem;
    }
  </style>
</head>
<body>
  <header>
    Projetos da Faculdade
  </header>

  <div class="container">
    <div class="card">
      <h3>Banco de Dados</h3>
    </div>
    <div class="card">
      <h3>Bootcamp I</h3>
    </div>
    <div class="card">
      <h3>Engenharia de Software</h3>
    </div>
    <div class="card">
      <h3>Fundamentos da Engenharia</h3>
    </div>
    <div class="card">
      <h3>Introdução à Computação</h3>
    </div>
    <div class="card">
      <h3>Lógica de Programação</h3>
    </div>
  </div>

  <footer>
    Página gerada para fins acadêmicos. Inspirado na identidade visual da Alura.
  </footer>
</body>
</html>
