# Começando do Zero

Lista de referência para os desenvolvedores iniciantes e para os que se atualizam constatemente. 
Os itens desta lista expressa a visão do desenvolvedor web que utiliza tecnologia .NET.

  - **Considerações:**
     - Os itens com este icone ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png) são as tecnologias essenciais, de escala 1 (as que você precisa dominar primeiro);
     - Esta é uma lista para uma pessoa com perfil em desenvolvimento web utilizando .NET;
     - A lista trata-se apenas de tecnologia e ferramentas. Boas práticas, conceitos, padrões e técnicas não estão contidos aqui;
     - Esta é uma tentativa de clarear o que cada coisa faz e que tecnologia atenderá isso;
     - Não há tecnologias muito específica (como frameworks de testes, mocks, etc) e outra tecnologia mais avançada e não tão popular ainda (como dapper).

*Esta lista é dinâmica e será atualizada com freqüência, inclusive sua contribuição é bem-vinda!* Para saber mais o que motivou a criação desta lista acesse  o artigo [Começando do zero!](http://www.rodrigokono.net/2014/10/03/comeando-do-zero-quais-tecnologias-preciso-aprender-hoje-e-porque/)

## Tabela de Conteúdo

  1. [Tooling](#tooling)
  2. [Client Side](#client-side)
  3. [Backend](#backend)
  4. [Storage](#storage)


## Tooling

| Finalidade                                                                                                                                                                 | Tecnologia           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|
| Mais que uma IDE para o desenvolver aplicações .NET. Conhecer customizações, teclas de atalho, integrações com add-ins , análises e debugging agiliza bastante o trabalho. | **Visual Studio**  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png) |
| Sistema de controle de versão distribuído para pequenos e grandes projetos. Se destaca por ter local branching, staging areas e múltiplos workflows                        | **Git**  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)                |
| Gerenciar pacotes de dependências para soluções .NET. Copia os arquivos da biblioteca solicitada para a sua solução e atualiza automaticamente seu projeto.                | **NuGet** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)               |
| Automatizar praticamente qualquer coisa com um mínimo de esforço possível. Por exemplo minification, build, testes unitários, linting, etc                                 | Grunt / Gulp         |
| Produtividade / Scaffolds                                                                                                                                                  | Yeoman               |
| Gerenciamento de dependência / pacotes (você não precisa mais baixar manualmente e gerenciar seus scripts)                                                                 | Bower                |
| Ferramenta de produtividade que torna o Visual Studio muito melhor. Inspeções de código, refatorações automatizadas, navegação rápida, assistência na codificação.         | ReSharper            |
| Extensão para o Visual Studio com várias funcionalidades para desenvolvedores web.                                                                                         | Web Essentials       |
| Gerenciamento de código, integração com o time, controle de bugs, features, projeto, integração contínua, etc. O Visual Studio Online é baseado no TFS.                    | Visual Studio Online |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Client Side

| Finalidade                                                                                                                                               | Tecnologia        |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Realizar ações no browser como a comunicação assíncrona e a alteração do conteúdo do documento                                                           | **JavaScript** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)       |
| Criar conteúdo web com bons recursos de semântica, acessibilidade e multimídia.                                                                          | **HTML5** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)            |
| Estilos para páginas web com efeitos de transição, imagem, e outros, que dão um estilo novo às páginas Web 2.0 em todos os aspectos de design do layout. | **CSS3** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)             |
| Manipular documentos, manipular eventos, realizar animaçóes e realizar posts ajax de maneira mais simples afim de extender o poder do javaScript         | jQuery            |
| Utilizar controles de interface do usuário, tais como widgets, modal, combo, etc                                                                         | jQuery UI         |
| Desenvolver interfaces de usuário de maneira ágil com responsividade e suporte à dispositivos móveis                                                     | Bootstrap         |
| Ajudar a desenvolver páginas ou web apps de maneira mais rápida, robusta e adaptáveis.                                                                   | HTML5 BoilerPlate |
| Poder no na criação de aplicações SPA (single-page applications) e outras aplicações da web.                                                             | AngularJS         |
| Controlar o CSS, por exemplo com funções, variáveis, etc.                                                                                                | LESS              |
| Obter velocidade e qualidade do código com o controle de dependências/bibliotecas.                                                                       | RequireJs         |
| Separação de dados e domínio na camada de interface do usuário. Simplificar a visão complexa de componentes.                                             | KnockoutJs        |
| Ampliar a manipulação de objetos JavaScript                                                                                                              | UnderscoreJs      |
| Criar  programas de rede escaláveis de maneira fácil                                                                                                     | NodeJs            |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Backend

| Finalidade                                                                                     | Tecnologia       |
|------------------------------------------------------------------------------------------------|------------------|
| Desenvolver aplicações web, serviços, componentes, games, apps em .NET                         | **C#** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)              |
| Desenvolver aplicações web utilizando o modelo MVC                                             | **ASP.NET MVC 5**  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)  |
| Realizar consultas em repositórios de dados via objeto.                                        | **LINQ** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)            |
| Mapear o banco de dados para a aplicação de maneira que ele seja disponível para o ambiente OO | **NHibernate** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)      |
| Mapear o banco de dados para a aplicação de maneira que ele seja disponível para o ambiente OO | **Entity Framework** ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)|
| Criar serviços de comunicação entre aplicações.                                                | WCF              |
| Criar e consumir APIs                                                                          | ASP.NET WEB API  |
| Criar páginas web Single Page Applications                                                     | ASP.NET SPA      |
| Criar aplicações de tempo real                                                                 | ASP.NET SignalIR |
| Trabalhar com ambiente em nuvem                                                                | Windows Azure    |
| Trabalhar com Injeção de dependencias                                                          | Unity            |

**[Voltar ao topo](#tabela-de-conteúdo)**

## Storage

| Finalidade                                                   | Tecnologia         |
|--------------------------------------------------------------|--------------------|
| Realizar consultas em qualquer banco de dados                | **SQL ANSI**  ![Aprender Primeiro](https://raw.githubusercontent.com/cleytonferrari/comecandodozero/master/assets/first.png)         |
| Um dos principais bancos NoSQL                               | MongoDB            |
| Processamento e armazenamento de dados relacionais na nuvem  | SQL Azure          |
| Um dos principais SGBD do mercado                            | SQL Server         |
| Um dos principais SGBD do mercado                            | Oracle             |
| Armazenamento de grande quantidade de dados não estruturados | Azure Blob Storage |

**[Voltar ao topo](#tabela-de-conteúdo)**
