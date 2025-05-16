<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Inscrição - Campeonato de Lutas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #e50914;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    section {
      padding: 30px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #e50914;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-top: 10px;
    }
    input, select, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: none;
    }
    button {
      background-color: #e50914;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #c30710;
    }
  </style>
</head>
<body>

  <header>
    <h1>Campeonato de Lutas 2025</h1>
    <p>Mostre sua força. Mostre sua técnica. Mostre quem você é.</p>
  </header>

  <section>
    <h2>Informações do Evento</h2>
    <p><strong>Data:</strong> 20 de julho de 2025</p>
    <p><strong>Local:</strong> Ginásio Municipal de Esportes – Av. das Lutas, 123, Centro</p>

    <h2>Modalidades</h2>
    <ul>
      <li>Jiu-jitsu</li>
      <li>Judô</li>
      <li>Taekwondo</li>
    </ul>

    <h2>Categorias</h2>
    <ul>
      <li>Infantil, Juvenil, Adulto e Master</li>
      <li>Masculino e Feminino</li>
      <li>Por nível e peso</li>
    </ul>

    <h2>Formulário de Inscrição</h2>
    <form>
      <label for="nome">Nome Completo:</label>
      <input type="text" id="nome" name="nome" required />

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required />

      <label for="modalidade">Modalidade:</label>
      <select id="modalidade" name="modalidade" required>
        <option value="">Selecione</option>
        <option value="jiujitsu">Jiu-jitsu</option>
        <option value="muaythai">Muay Thai</option>
        <option value="boxe">Boxe</option>
        <option value="mma">MMA</option>
      </select>

      <label for="categoria">Categoria:</label>
      <select id="categoria" name="categoria" required>
        <option value="">Selecione</option>
        <option value="infantil">Infantil</option>
        <option value="juvenil">Juvenil</option>
        <option value="adulto">Adulto</option>
        <option value="master">Master</option>
      </select>

      <label for="peso">Categoria de Peso:</label>
      <input type="text" id="peso" name="peso" placeholder="Ex: até 70kg" required />

      <label for="mensagem">Mensagem adicional (opcional):</label>
      <textarea id="mensagem" name="mensagem" rows="4"></textarea>

      <button type="submit">Fazer Inscrição</button>
    </form>
  </section>

</body>
</html>
