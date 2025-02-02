# json
### Quando usar
JSON é uma API REST online gratuita que você pode usar sempre que precisar de dados falsos 
ou simplesmente para testar coisas localmente.

## Links para os arquivos JSON

Este repositório contém arquivos JSON com dados de posts e usuários.

* [posts.json](https://isaccanedo.github.io/json/posts.json)
* [users.json](https://isaccanedo.github.io/json/users.json)

## Como usar os dados

Você pode acessar os dados JSON diretamente através dos links acima.

**Exemplo de uso com JavaScript:**

```javascript
fetch('[https://isaccanedo.github.io/json/posts.json](https://isaccanedo.github.io/json/posts.json)')
  .then(response => response.json())
  .then(data => {
    // Faça algo com os dados dos posts
    console.log(data);
  });

fetch('[https://isaccanedo.github.io/json/users.json](https://isaccanedo.github.io/json/users.json)')
  .then(response => response.json())
  .then(data => {
    // Faça algo com os dados dos usuários
    console.log(data);
  });

