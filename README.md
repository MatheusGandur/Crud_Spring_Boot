Bota Crud-Primavera
API, cadastro de pessoas e endereço.

#O QUE É A APLICAÇÃO?

Essa aplicação é uma API que consiste em criar cadastro de pessoas, incluindo dados como e-mail, endereço, etc. A intenção do desenvolvimento é mostrar na prática as funcionalidades de uma API inserindo os dados através do Postam e armazenando no banco de dados MongoDB .

#FUNCIONALIDADES:

Encontra uma pessoa registrada no sistema por ID. Encontra uma lista de pessoas registradas no sistema. Registrar uma pessoa no sistema. Atualiza dados de uma pessoa do sistema. Exclua uma pessoa do sistema.

#FERRAMENTAS:

Processo interno:

Java
Spring Data JPA
Maven
MongoDB
#VERSÃO:

Versão do Java: 17

Versão do Spring Boot: 3.2.3

1 - Expor um serviço de busca de CEP Na classe EnderecoController temos o método GET busca o cadastro, onde falamos um JSON ex: {"email":" maihts@gmail.com "}.

2- Salvar usuário, seguindo as regras do CRUD Todos os métodos CRUD estão na classe UsuarioControllerr(consultar, atualizar, excluir e incluir).

3- Abaixo vou deixar alguns exemplos para realizar os testes na API. { "nome" : "", "email" : "", "documento" : "", "endereco" :{ "rua" : "", "numero" : 30, "bairro" : "", "cep" : "", "" : "M", "" : "" }}

#Dependências:

Data JPA -> Utilizando o JPA para fazer a ponte entre o banco de dados e a aplicação -> ORM

MongoDB -> Utilizado esse BANCO no ambiente de desenvolvimento e produção.

Postman - Utilizado para fazer as requisições (CONSUMIR) a aplicação.

IntelliJ - IDE escolhido para desenvolver o projeto.

Git e GitHub - Utilizados para commitar o projeto e subir o código para a nuvem(remoto).