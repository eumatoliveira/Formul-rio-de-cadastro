# Formulário de Cadastro

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- `index.html`: O arquivo HTML principal que contém o formulário de cadastro.
- `style.css`: O arquivo CSS para estilização do formulário.
- `script.js`: O arquivo JavaScript para funcionalidades adicionais.
- `README.md`: Este arquivo de documentação.

## Conteúdo dos Arquivos

### index.html

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Cadastro - Signup</title>
</head>
<body>
  <h1>Formulário de Cadastro</h1>
  <form name="signup" action="coloque o link do site">
    <label for="name">Nome:</label>
    <input type="text" id="name" name="name"><br>
    <label for="age">Idade:</label>
    <input type="number" id="age" name="age"><br>
    <label for="password">Senha:</label>
    <input type="password" id="password" name="password"><br>
    <button type="submit">Enviar</button>
  </form>
</body>
</html>
