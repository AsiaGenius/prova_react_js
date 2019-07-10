# Prova Pratix

Esse teste rápido consiste em uma aplicação REACT-JS que fará uma consulta em uma URL, com dados do tipo jSON. Esses dados devem retornar, e ser listados na tela da aplicação.

##### Tarefas

- O projeto deverá fazer a consulta na URL: https://api.pratix.top/api/geo/get/simple/radio/40/-3.7553375/-38.6296543
- Tratar os dados, e exibir **cards** em uma LISTA
- Deverá ter um **campo search** para pesquisarmos os cards por **Serviços**
- Deverá ter um Scroll to Update (a medida que vai rolando a tela pra baixo, vai aparecendo novos cards)



### Cards

Segue a ideia de modelo do card, é obrigatório aparecer;
- Area de Atuação (categoria)
- Serviços (subcategoria)
- Cidade/Estado
- Email
- Quantidade de Estrelas

Pra ajudar você a se inspirar, segue uma ideia de desing de como poderia ser (claro, você vai colocar os dados que foram solicitados acima); https://prnt.sc/od4fx5


### Campo Search

Deverá ser fluido e sem bugs, digita o nome, e vai filtrar tudo exibindo apenas as ocorrências.

O campo serviço, consta lá no retorno do jSON.


### Redux
Você deverá usar redux e redux-persist. A ideia aqui, é que com o redux-persist, a próxima vez que o usuário entrar no Projeto, carregue tudo sem demora (visto que ficou em cache do redux-persist)
.

**Crie o seu próprio repositório e suba o projeto, crie sua branch, e envie commits. Em seguida, envie o link do repositório, para verificarmos como ficou. ***

Boa sorte!
