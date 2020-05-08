<h3 align="center">
  Desafio: Primeiro projeto Node.js
</h3>

## Sobre o desafio
Nesse desafio, foi criado uma aplicação Node.js que permite incluir e listar os dados dos repositórios criados, além disso é gerado um balanço com o valor de soma de entradas, retiradas e total de crédito.

**Observação**: Este desafio está utilizando o gerenciador de pacotes **yarn**, sendo assim para instalar todas as dependências é necessário dar o comando `yarn` no terminal.

### Funcionalidades da Aplicação

Abaixo as funcionalidades que foram criadas para atender o desafio.

- **`POST /transactions`**: A rota recebe `title`, `value` e `type` dentro do corpo da requisição, sendo o type o tipo da transação, que deve ser `income` para entradas (depósitos) e `outcome` para saidas (retiradas).

- **`GET /transactions`**: Essa rota retorna uma listagem com todas as transações que você cadastrou até agora, junto com o valor de soma de entradas, retiradas e total de crédito.
