# Teste_Global_TI
Projeto solicitado pela Global TI, como parte de processo seletivo para vaga de Desenvolvedor .Net na empresa Via Varejo.

Objetivo do projeto:
--------------------
  Um programa que receba a localização de cada um dos meus amigos e, para cada um deles, indique quais são os outros três amigos mais próximos a ele.

Arquitetura usada:
-------------------
  Foi utilizado dois projetos distintos, além da criação do banco de dado, são eles:

  ApiUsuarios =>
   - Serviço que realiza o cadastro das informações, bem como os cálculos responsáveis pela ja mencionada lista de amigos mais próximos,   foi criado uma api em Asp.Net Core.
  
  AmigosApp => 
  WindowsForms (C#)

  Repositório => 
   - Banco de dados SQL Server 2017 (Acesso via seriço feito com Entity Framework)
  Script de criação do banco("GlobalTIBD") e tabela("Usuarios") se encontra no arquivo  ScriptCriacaoBDeTabela_TesteGlobalTI.sql

Observações:
------------
  A string de conexão com o banco de dados deve ser alterada e se encontra no arquivo appsettings.json, localizado em ..\ApiUsuarios\ApiUsuarios

  Para funcionamento correto da aplicação, o endereço/mapeamento do serviço, visivel no browser que é iniciado ao executar o serviço, deve ser inserido ta tela inicial da interface, que apenas deverá ser executada após o serviço estar em execução.
  
  




