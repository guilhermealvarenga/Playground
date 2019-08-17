# Playground de ASP.NET MVC 5 + DDD + EF + AutoMapper + IoC #

[Tutorial - Eduardo Pires](https://www.eduardopires.net.br/2014/10/tutorial-asp-net-mvc-5-ddd-ef-automapper-ioc-dicas-e-truques/)

### Conte�do abordado no tutorial

* Criar uma solu��o padr�o DDD
* Separar a aplica��o em camadas
* Entidades de Dom�nio
* Classes de Servi�o
* Criar Contratos (Interfaces)
* Reposit�rio Gen�rico
* Reposit�rio Especializado
* Criar um Contexto do Entity Framework
* Trabalhar com Migrations
* Criar novas conven��es do Entity Framework
* Remover algumas conven��es do Entity Framework
* Sobrescrever o m�todo SaveChanges para persist�ncia de dados
* Programar com CodeFirst
* Utilizar FluentAPI para modelar tabelas
* Criar Relacionamentos entre Entidades e refletindo nas tabelas do banco de dados.
* Criar e utilizar a camada de Application
* Trabalhar com classes gen�ricas de Entidades
* Abstrair camadas com Inje��o de Depend�ncia (IoC)
* Implementar o Ninject como container de IoC (DI)
* Utilizar ViewModels
* Utilizar DataAnnotations para valida��o de formul�rios
* Mapear ViewModels x Entidade de Dom�nio com AutoMapper
* Muitas dicas para acelerar sua produ��o


### Modelo de Arquitetura MVC
* ASP.NET MVC � apenas camada de apresenta��o.
* O padr�o MVC visa apenas a separa��o de responsabilidades e nada mais.

### DDD - Domain Driven Design
* Uma abordagem de design.
* Complexa (no in�cio).
* Desenvolvimento guiado pelo Dom�nio.
* Isolamento de Responsabilidades.
* Abstra��o de Camadas.

### Domain Layer
* Entidades.
* Objetos de Valor.
* Contratos (Interfaces).
* Services.
* Factories.

Montando uma aplica��o utilizando ASP.NET MVC e aplicando DDD para guiar o desenvolvimento, com ORM's, Reposit�rios, IoC, mapeando as Entidades de Dom�nio com as ViewModels e entre outros patterns.  
A aplica��o ser�:
* Respons�vel (por isolar todas as depend�ncias, cada coisa reponder por si pr�pria, n�o misturar os assuntos). 
* Escal�vel. 
* Test�vel. 
* Reutiliz�vel  

E a somat�ria destes pontos torna a manuten��o da aplica��o muito mais f�cil e tranquila.