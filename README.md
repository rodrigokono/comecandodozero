# Começando do Zero

Lista de referência para os desenvolvedores iniciantes e para os que se atualizam constantemente. 
Os itens desta lista expressam a visão do desenvolvedor web que utiliza tecnologia .NET.

  - **Considerações:**
     - Os itens com este icone ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png) são as tecnologias essenciais, de escala 1 (as que você precisa dominar primeiro);
     - Esta é uma lista para uma pessoa com perfil em desenvolvimento web utilizando .NET;
     - A lista trata-se apenas de tecnologia e ferramentas. Boas práticas, conceitos, padrões e técnicas não estão contidos aqui;
     - Esta é uma tentativa de clarear o que cada coisa faz e que tecnologia atenderá isso;
     - Não há tecnologias muito específicas (como frameworks de testes, mocks, etc) e outras tecnologias mais avançadas e não tão populares ainda (como dapper).

*Esta lista é dinâmica e será atualizada com freqüência, inclusive sua contribuição é bem-vinda!* Para saber mais o que motivou a criação desta lista acesse  o artigo [Começando do zero!](http://www.rodrigokono.net/2014/10/03/comeando-do-zero-quais-tecnologias-preciso-aprender-hoje-e-porque/)

## Tabela de Conteúdo

  1. [Tooling](#tooling)
  2. [Client Side](#client-side)
  3. [Backend](#backend)
  4. [Storage](#storage)


## Tooling

| Finalidade                                                                                                                                                                 | Tecnologia           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|
| Mais que uma IDE para o desenvolver aplicações .NET. Conhecer customizações, teclas de atalho, integrações com add-ins , análises e debugging agiliza bastante o trabalho. <br>[video 01 - Baixando VS e criando um projeto - (8:33)](https://www.youtube.com/watch?v=mVkngdaZPXU)<br>[video 02 - Adicionando linhas e trocando o estilo do visual studio - (1:44)](https://www.youtube.com/watch?v=5f8HcqXESIY) | [**Visual Studio**](http://www.visualstudio.com/)  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png) |
| Sistema de controle de versão distribuído para pequenos e grandes projetos. Se destaca por ter local branching, staging areas e múltiplos workflows <br>[video 01 - Instalação, clone de repositório, commit e push - (4:37)](https://www.youtube.com/watch?v=HTBUMpqkk5w)<br>[video 02 - Configurando usuário no git - (1:41)](https://www.youtube.com/watch?v=RJnDv6P3UCo)<br>[video 03 - Ignorando arquivos nos commits - (4:30)](https://www.youtube.com/watch?v=QKMNOkrC_tQ)| [**Git**](http://git-scm.com/)  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)                |
| Gerenciar pacotes de dependências para soluções .NET. Copia os arquivos da biblioteca solicitada para a sua solução e atualiza automaticamente seu projeto.  <br>[video 01 - Baixando pacotes com o nuget - (3:17)](https://www.youtube.com/watch?v=IXWB68X0b-c) | [**NuGet**](https://www.nuget.org/) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)               |
| Automatizar praticamente qualquer coisa com um mínimo de esforço possível. Por exemplo minification, build, testes unitários, linting, etc                                 | [Grunt](http://gruntjs.com/) / [Gulp](http://gulpjs.com/)         |
| Produtividade / Scaffolds                                                                                                                                                  | [Yeoman](http://yeoman.io/)               |
| Gerenciamento de dependência / pacotes (você não precisa mais baixar manualmente e gerenciar seus scripts)                                                                 | [Bower](http://bower.io/)                |
| Ferramenta de produtividade que torna o Visual Studio muito melhor. Inspeções de código, refatorações automatizadas, navegação rápida, assistência na codificação.         | [ReSharper](http://www.jetbrains.com/resharper/)            |
| Extensão gratuita para o Visual Studio com algumas melhorias de produtividade, como ajuda rápida, visualização de erros de compilação e várias outras utilidades.                                                                                          | [Productivity Power Tools](https://visualstudiogallery.msdn.microsoft.com/dbcb8670-889e-4a54-a226-a48a15e4cace)        |
| Extensão open-souce para o Visual Studio com algumas melhorias de produtividade relacionados a formatação, organização e limpeza dos códigos-fonte, além de outras utilidades.                                                                                         | [Code Maid](http://www.codemaid.net/)       |
| Extensão para o Visual Studio com várias funcionalidades para desenvolvedores web, como melhorias nos editores de CSS, Javascript, HTML além de ferramentas para LESS, CoffeeScript, TypeScript, etc.                                                                                         | [Web Essentials](http://vswebessentials.com/)       |
| Gerenciamento de código, integração com o time, controle de bugs, features, projeto, integração contínua, etc. O Visual Studio Online é baseado no TFS.                    | [Visual Studio Online](http://www.visualstudio.com/en-us/products/what-is-visual-studio-online-vs.aspx) |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Client Side

| Finalidade                                                                                                                                               | Tecnologia        |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Realizar ações no browser como a comunicação assíncrona e a alteração do conteúdo do documento <br>[video 01 - Enviando a primeira mensagem para o navegador - (3:59)](https://www.youtube.com/watch?v=4UnWV8Hu76E) <br>[video 02 - Pegando valores de campos HTML - (5:46)](https://www.youtube.com/watch?v=hB5KO_WUxcM) <br>[video 03 - Criando uma calcularoa - (3:36)](https://www.youtube.com/watch?v=0_jMyI058IQ)| [**JavaScript**](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)       |
| Estruturar e apresentar conteúdos na web com bons recursos de semântica, acessibilidade e multimídia. <br>[video 01 - Html básico primeiros passos - (3:37)](https://www.youtube.com/watch?v=qVmTI4Weq-Q) <br>[video 02 - Html básico adicionando campos - (3:04)](https://www.youtube.com/watch?v=Z07LB81l-AA) <br>[video 03 - Html básico criando um formulário - (5:41)](https://www.youtube.com/watch?v=XJgo7kaBrFQ) | [**HTML5**](http://www.w3.org/TR/html5/) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)            |
| Estilos para páginas web com efeitos de transição, imagem, e outros, que dão um estilo novo às páginas Web 2.0 em todos os aspectos de design do layout. <br>[video 01 - Css básico primeiros passos - (6:21)](https://www.youtube.com/watch?v=caug-htWJ1Y) | [**CSS3**](http://www.w3.org/TR/CSS/) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)             |
| Manipular documentos, manipular eventos, realizar animações e realizar posts ajax de maneira mais simples afim de extender o poder do javaScript   <br>[video 01 - Jquery adicionando a biblioteca - (3:43)](https://www.youtube.com/watch?v=Uhkx7z12ub8)        | [jQuery](http://jquery.com/)            |
| Utilizar controles de interface do usuário, tais como widgets, modal, combo, etc    <br>[video 01 - Jqueryui adicionando a biblioteca e Draggable - (4:19)](https://www.youtube.com/watch?v=vDuAKrswC2c)   | [jQuery UI](http://jqueryui.com/)         |
| Desenvolver interfaces de usuário de maneira ágil com responsividade e suporte à dispositivos móveis <br>[video 01 - Configurando o bootstrap - (2:56)](https://www.youtube.com/watch?v=2t9mKvCu2AQ)| [Bootstrap](http://getbootstrap.com/) / [Foundation](http://foundation.zurb.com/)         |
| Ajudar a desenvolver páginas ou web apps de maneira mais rápida, robusta e adaptáveis.                                                                   | [HTML5 BoilerPlate](http://html5boilerplate.com/) |
| Ajudar na criação de aplicações SPA (single-page applications) e outras aplicações da web.                                                             | [AngularJS](https://angularjs.org/)         |
| Pré-compilador de CSS, permite trabalhar com funções, variáveis, e etc.                                                                                                | [LESS](http://lesscss.org)              |
| Obter velocidade e qualidade do código com o controle de dependências/bibliotecas.                                                                       | [RequireJs](http://requirejs.org/)         |
| Separação de dados e domínio na camada de interface do usuário. Simplificar a visão complexa de componentes.                                             | [KnockoutJs](http://knockoutjs.com/)        |
| Ampliar a manipulação de objetos JavaScript                                                                                                              | [UnderscoreJs](http://underscorejs.org/)      |
| Criar programas de rede escaláveis de maneira fácil     <br>[video 01 - Instalação do Nodejs - (2:46)](https://www.youtube.com/watch?v=GLwxJrBK7cs)  | [NodeJs](http://nodejs.org/)            |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Backend

| Finalidade                                                                                     | Tecnologia       |
|------------------------------------------------------------------------------------------------|------------------|
| Desenvolver aplicações web, serviços, componentes, games, apps em .NET                         | [**C#**](http://msdn.microsoft.com/pt-br/library/kx37x362.aspx) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)              |
| Desenvolver aplicações web utilizando o modelo MVC <br>[video 01 - Criando um projeto .Net MVC - (5:45)](https://www.youtube.com/watch?v=d5Gmp8YIhwE)   | [**ASP.NET MVC 5**](http://www.asp.net/mvc)  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)  |
| Realizar consultas de maneira unificada em diversos tipos de coleções de dados.                                        | [**LINQ**](http://msdn.microsoft.com/pt-br/library/bb397926.aspx) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)            |
| Mapear o banco de dados para a aplicação de maneira que ele seja disponível para o ambiente OO | [**NHibernate**](http://nhforge.org/) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)      |
| Mapear o banco de dados para a aplicação de maneira que ele seja disponível para o ambiente OO <br>[video 01 - Configurando o EF e fazendo uma query - (7:01)](https://www.youtube.com/watch?v=7mzLyXoseh4) | [**Entity Framework**](http://msdn.microsoft.com/en-us/data/ef.aspx) ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)|
| Criar Web Services REST e WS-*/SOAP em diferentes tipos de protocolos, para comunicação entre aplicações                                               | [WCF](http://msdn.microsoft.com/en-us/library/dd456779.aspx)              |
| Criar Web Services HTTP, para comunicação entre aplicações. Possui uma maneira mais madura de criar APIs RESTfull   <br>[video 01 - Criando um projeto Web Api - (3:57)](https://www.youtube.com/watch?v=eWYxuqDbqw8) | [ASP.NET WEB API](http://www.asp.net/web-api)  |
| Criar páginas web Single Page Applications                                                     | [ASP.NET SPA](http://www.asp.net/single-page-application)      |
| Criar aplicações de tempo real                                                                 | [ASP.NET SignalR](http://www.asp.net/signalr) |
| Trabalhar com ambiente em nuvem                                                                | [Windows Azure](http://azure.microsoft.com/pt-br/)    |
| Trabalhar com Injeção de dependências                                                          | [Unity](https://unity.codeplex.com/)            |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Storage

| Finalidade                                                   | Tecnologia         |
|--------------------------------------------------------------|--------------------|
| Realizar consultas em qualquer banco de dados relacional     | [**SQL ANSI**](http://www.contrib.andrew.cmu.edu/~shadow/sql/sql1992.txt)  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)         |
| Banco de dados NoSQL orientado a documentos                  | [MongoDB](http://www.mongodb.org/)            |
| Processamento e armazenamento de dados relacionais na nuvem  | [SQL Azure](http://azure.microsoft.com/pt-br/services/sql-database/)          |
| Um dos principais SGBD do mercado                            | [SQL Server](http://www.microsoft.com/pt-br/server-cloud/products/sql-server/)         |
| Um dos principais SGBD do mercado                            | [Oracle](https://www.oracle.com/database/index.html)             |
| Armazenamento de grande quantidade de dados não estruturados | [Azure Blob Storage](http://azure.microsoft.com/pt-br/documentation/articles/storage-dotnet-how-to-use-blobs/) |

**[Voltar ao topo](#tabela-de-conteúdo)**
