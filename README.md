## Projeto React.js

A proposta deste projeto é criar um website utilizando a biblioteca React JS, realizando integrações com a API do GitHub.

**Dependências do projeto:**

* **REACT JS**: em caso de dúvidas sobre a biblioteca, utilize a documentacao oficial https://reactjs.org/
* **react-router-dom**: precisa ser instalado o módulo abaixo, comando: `npm install react-router-dom --save`
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para utilizar qualquer biblioteca para criação de interfaces.

## Layout

- A aplicação deverá seguir o layout conforme link abaixo, caso queira implementar outras funcionalidades das quais já esperada, isso ficará a seu critério.
- [Figma](https://www.figma.com/file/CAs54hHHm8BTUrBoRySPIj/Frontend-job-test?node-id=0%3A1)

## Funcionalidades básicas

### Página inicial

- Possuir um campo de busca, para que seja possível digitar o nome de um usuário e um nome de repositório (ex: Facebook/React). Este valor precisa ser repassado para o endpoint API.
- Exibir os resultados da consulta da api, mostrando o repositório em uma lista.
- Ao clicar em um repositório na lista, a aplicação deverá redirecionar para a página de detalhes.


### Página de Detalhes

- Página deverá mostrar os detalhes do repositório clicado.
- Exibir no mínimo os seguintes dados: nome, descrição, email, owner name, avatar url, forks, start, issues, linguagem.
- Na página de detalhes, ao clicar sobre uma issue, deverá abrir uma nova aba do navegador para a página oficial da issue no GitHub. 

## API GitHub

- endpoint consumidos:
`https://docs.github.com/pt/rest/reference/repos'


## Entrega

 Ao terminar o teste, envie um email para `desenvolvimento@nolifretes.com.br` com o titulo - DEV-REACT-TESTE contendo o link do github. 
