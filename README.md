## Json

### Quando usar
JSON é uma API REST online gratuita que você pode usar sempre que precisar de dados falsos 
ou simplesmente para testar coisas localmente.

## Links para os arquivos JSON

Este repositório contém arquivos JSON com dados de bancos e serviços:

* [bancos.json](https://isaccanedo.github.io/json/bancos.json)
* [servicos.json](https://isaccanedo.github.io/json/servicos.json)

## Como usar os dados

Você pode acessar os dados JSON diretamente através dos links acima.

**Exemplo de uso com JavaScript:**

```javascript
fetch('[https://isaccanedo.github.io/json/bancos.json](https://isaccanedo.github.io/json/bancos.json)')
  .then(response => response.json())
  .then(data => {
    // Faça algo com os dados dos bancos
    console.log(data);
  });

fetch('[https://isaccanedo.github.io/json/servicos.json](https://isaccanedo.github.io/json/servicos.json)')
  .then(response => response.json())
  .then(data => {
    // Faça algo com os dados de serviços
    console.log(data);
  });

