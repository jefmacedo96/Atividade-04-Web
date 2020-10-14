# Atividade-04-Web

Utilizando o Vue.js, Axios, Eclipse e Tomcat. Crie um WebService REST para o recurso Carros.
Cada carro é composto pelas seguintes informações:

● Carro:
○ Nome
○ Marca
○ Ano de Fabricação
○ Ano de Modelo
○ Data de Venda

● Tudo é armazenado em memória. A seguir, são apresentados os requisitos da aplicação
(em parêntese tem quanto vale cada item):

● (0.5) [CLIENTE] Ter um formulário para cadastrar um registro no sistema e um
botão para a chamada POST com o Vuejs / Axios para o servidor;

● (0.5) [CLIENTE] Ter uma lista para recuperar todos os registros e um botão para
a chamada GET com o Vuejs / Axios para o servidor;

● (0.5) [CLIENTE] Ter uma div para recuperar os dados de um registro escolhido
pelo usuário. Um campo contendo o ID e um botão para a chamada GET com o
Vuejs / Axios para o servidor;

● (0.5) [CLIENTE] Utilizar os campos anteriores do POST e o ID para realizar o
UPDATE. Um botão para a chamada PUT com o Vuejs / Axios para o servidor;

● (0.5) [CLIENTE] Utilizar o campo anterior ID para realizar o DELETE. Um
botão para a chamada DELETE com o Vuejs / Axios para o servidor;

● (1.0) [CLIENTE] Ter uma div para servir como filtro de registros. Um campo
para referenciar uma quantidade de registros que o usuário quer recuperar. Um
botão para a chamada da função de filtragem com o Vuejs / Axios para o servidor;

● (1.0) [CLIENTE] Ter uma div para servir como filtro de registros. Essa filtragem
é baseada na marca dos Carros. Um campo para referenciar a marca digitada pelo
usuário. Um botão para a chamada da função de filtragem com o Vuejs / Axios
para o servidor;

● (0.75) [SERVIDOR] Implementar o POST no WebService;

● (0.75) [SERVIDOR] Implementar o GET ALL no WebService;

● (0.75) [SERVIDOR] Implementar o GET BY ID no WebService;

● (1.0) [SERVIDOR] Implementar o método para retornar baseado na quantidade
de registros no WebService;

● (0.75) [SERVIDOR] Implementar o método para retornar baseado na marca no
WebService;

● (0.75) [SERVIDOR] Implementar o PUT no WebService;

● (0.75) [SERVIDOR] Implementar o DELETE no WebService.
