## Projeto React.js

A proposta deste projeto é criar um website utilizando a biblioteca React JS, realizando integrações com a API do GitHub.

**Dependências do projeto:**

* **REACT JS**: em caso de dúvidas sobre a biblioteca, utilize a documentacao oficial https://reactjs.org/
* **react-router-dom**: precisa ser instalado o módulo abaixo, comando: `npm install react-router-dom --save`
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para utilizar qualquer biblioteca para criação de interfaces.

## Funcionalidades básicas

### Página inicial

- possuir um campo de busca, para que seja possível digitar um texto aberto. Este valor precisa ser repassado para o endpoint API.
- exibir resultados da consulta da api, mostrando os dados do usuário digitado e listando seus repositórios.
- lista de repositórios deve redirecionar para a página de detalhes com o clique em um item da lista.

### Página de Detalhes

- página deve mostrar os detalhes do repositório clicado.
- contendo no mínimo os seguintes dados: nome, descrição, nome do dono e  linguagem.

## API GitHub

- endpoint consumidos:
`http://api.github.com/users/{USUARIO}`
`http://api.github.com/users/{USUARIO}/repos`


## Entrega

 Ao terminar o teste, envie um email para `desenvolvimento@nolifretes.com.br` contendo o link do github. 
