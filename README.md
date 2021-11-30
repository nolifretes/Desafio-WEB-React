## Projeto React.js

A proposta deste projeto é criar um website utilizando a biblioteca React JS, realizando integrações com a API do GitHub.

**Dependências do projeto:**

* **REACT JS**: em caso de dúvidas sobre a biblioteca, utilize a documentacao oficial https://reactjs.org/
* **react-router-dom**: precisa ser instalado o módulo abaixo, comando: `npm install react-router-dom --save`
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para utilizar qualquer biblioteca para criação de interfaces.

## Layout

- [Figma](https://www.figma.com/file/CAs54hHHm8BTUrBoRySPIj/Frontend-job-test?node-id=0%3A1)

- A aplicação deverá conter o seguinte layout, poderá contér mais funcionalidades das quais já esperada, isso ficará a seu critério.

## Funcionalidades básicas

### Página inicial

- possuir um campo de busca, para que seja possível digitar um texto aberto. Este valor precisa ser repassado para o endpoint API.
- exibir resultados da consulta da api, mostrando os dados do Usuário/Repositório.
- lista de repositórios deve redirecionar para a página de detalhes com o clique em um item da lista.

### Página de Detalhes

- página deve mostrar os detalhes do repositório clicado.
- contendo no mínimo os seguintes dados: nome, descrição, email, username, forks, start, issues, linguagem.

## API GitHub

- endpoint consumidos:
`http://api.github.com/users/{USUARIO}`
`http://api.github.com/users/{USUARIO}/{REPO}`


## Entrega

 Ao terminar o teste, envie um email para `desenvolvimento@nolifretes.com.br` com o titulo - DEV-REACT-TESTE contendo o link do github. 
