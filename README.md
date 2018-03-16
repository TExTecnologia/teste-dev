# Teste Dev

Leia primeiro todo o projeto, faça sua estimativa de horas para o desenvolvimento e envie um email com o título `[Teste Dev] Estimativa` para lagden@textecnologia.com.br

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o título `[Teste Dev] Finalizado` para rh@textecnologia.com.br


## Missão

Desenvolver uma **App Mobile** em [React Native](https://facebook.github.io/react-native/) ou [Vue.js and NativeScript](https://nativescript-vue.org/)


## Especificação

Abaixo temos informações que são primordiais para o desenvolvimento do **App Mobile**


### API

Para desenvolver o **App**, você irá consumir os dados de uma API [GraphQL](http://graphql.org/)

O endpoint para consumir a API é: https://api.nimble.com.br/veiculoQL/v1/gql
E o esquema está na pasta [resources](https://api.nimble.com.br/veiculoQL/v1/gql)


### Wireframe

Você fará o desenvolvimento do **App** seguindo esses wireframes


#### Lista de veículos

Na listagem, você irá exibir 20 items por página, onde o `Title` é a `marca` e o `Subtitle` é o `modelo`
A paginação é via scroll...

Exemplo:

```
-----------------
HONDA
Civic LX AT
-----------------
TOYOTA
Corolla XE 4P AT
-----------------
```

Utilize o método `buscaVeiculo` da API


#### Busca na lista de veículos

Semelhante ao item **Lista de veículos**, mas aqui irá exibir apenas os itens que foram encontrados na busca

Utilize o método `buscaVeiculo` da API


#### Detalhes do veículo

Exibe as informações do veículo (observe que nessa tela tem o botão de editar)

Utilize o método `veiculo` da API

#### Inserir, Atualizar

Atualiza ou insere os dados do veículo...

Para inserir, na tela de listagem tem o botão `+`...
E para editar, na tela de detalhes tem o botão `Editar`

Para inserir um veiculo novo, utilize o método `createVeiculo` da API
Para editar um veiculo já cadastrado, utilize o método `updateVeiculo` da API


### Dica

Utilize o [GraphQL Playground](https://www.graphqlbin.com/new) para ajudar nos testes e desenvolvimento das `queries` e `mutation`


## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Dev] Dúvida` para lagden@textecnologia.com.br