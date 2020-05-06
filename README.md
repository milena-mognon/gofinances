<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 07: GoFinances Web
</h3>

## :rocket: Sobre o desafio

Nesse desafio, foi desenvolvido a parte web da aplicação GoFinances, utilizando React. Esta irá se conectar ao backend, desenvolvido no [Desafio 06](https://github.com/milena-mognon/desafio-typeorm-upload), para exibir as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.

Essa aplicação serve para armazenar transações financeiras de entrada e saída e permitir o cadastro e a listagem dessas transações, além de permitir a criação de novos registros no banco de dados a partir do envio de um arquivo csv.

### Específicação dos testes

- **`should be able to list the total balance inside the cards`**: A aplicação deve permitir que seja exibido na sua Dashboard, cards contendo o total de `income`, `outcome` e o total da subtração de `income - outcome` que são retornados pelo balance do seu backend.

* **`should be able to list the transactions`**: A aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do seu backend.

- **`should be able to navigate to the import page`**: A aplicação deve permitir a troca de página através do Header, pelo botão que contém o nome `Importar`.

- **`should be able to upload a file`**: A aplicação deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de `import`, e que seja possível exibir o nome do arquivo enviado para o input.

## 🚀 Instalação e execução

### back-end

Acesse o [Desafio 06](https://github.com/milena-mognon/desafio-typeorm-upload) e siga as instruções disponíveis no README.

### front-end

1. Faça um clone desse repositório;
2. Entre na pasta do projeto pelo terminal;
3. Rode `yarn` para instalar as dependências;
4. Rode `yarn start` para iniciar o servidor de desenvolvimento;
5. Acesse `localhost:3000` para ver no navegador;
6. Rode `yarn test` para executar os testes;
