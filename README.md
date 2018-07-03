# Teste Dev

Leia primeiro todo o projeto...

Faça uma estimativa de horas para o desenvolvimento e envie um email com o título `[Teste Dev] Estimativa` para rh@textecnologia.com.br

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o título `[Teste Dev] Finalizado` para rh@textecnologia.com.br

**Atenção:**

Coloque no `README.md` do seu projeto todas as informações para conseguirmos executá-lo


## Missão

Desenvolver uma **App Mobile** em [React Native](https://facebook.github.io/react-native/) ou [Vue.js and NativeScript](https://vue-native.io/)


## Especificação

Abaixo temos informações que são primordiais para o desenvolvimento do **App Mobile**


### API

Para desenvolver o **App**, você irá consumir os dados de uma API [GraphQL](http://graphql.org/)

O endpoint para consumir a API é: https://api.nimble.com.br/veiculoQL/v1/gql  
E o esquema está na pasta [resources](https://github.com/TExTecnologia/teste-dev/blob/master/resources/schema.graphql)


### Wireframe

Você fará o desenvolvimento do **App** seguindo os wireframes abaixo


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

![Lista](https://github.com/TExTecnologia/teste-dev/raw/master/resources/wireframe/lista.png)


#### Busca na lista de veículos

Semelhante ao item **Lista de veículos**, mas aqui irá exibir apenas os itens que foram encontrados na busca

Utilize o método `buscaVeiculo` da API

![Busca](https://github.com/TExTecnologia/teste-dev/raw/master/resources/wireframe/busca.png)


#### Detalhes do veículo

Exibe as informações do veículo (observe que nessa tela tem o botão de editar)

Utilize o método `veiculo` da API

![Detalhes](https://github.com/TExTecnologia/teste-dev/raw/master/resources/wireframe/detalhes.png)


#### Inserir e Atualizar

Atualiza ou insere os dados do veículo...

Para inserir, na tela de listagem tem o botão `+`...  
E para editar, na tela de detalhes tem o botão `Editar`

Para inserir um veiculo novo, utilize o método `createVeiculo` da API  
Para editar um veiculo já cadastrado, utilize o método `updateVeiculo` da API

![Editar](https://github.com/TExTecnologia/teste-dev/raw/master/resources/wireframe/edit.png)


### Dica

Utilize o [GraphQL Playground](https://www.graphqlbin.com/new) para ajudar nos testes e desenvolvimento das `queries` e `mutation`

![Graphql Playgraound](https://github.com/TExTecnologia/teste-dev/raw/master/resources/graphql-playgraound-1.png)
![Graphql Playgraound](https://github.com/TExTecnologia/teste-dev/raw/master/resources/graphql-playgraound-2.png)


## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Dev] Dúvida` para rh@textecnologia.com.br
