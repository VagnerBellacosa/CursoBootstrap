<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
![Bootcamps na Digital Innovation One](BootCamps/Images/capa.png "Bootcamps")



# CursoBootstrap

Apontamentos do curso de Javascript Html CSS com Bootstrap

[O que é Bootstrap](Workspace/OQueEhBootstrap.Md)

[Paginas exemplo](Workspace/Code)

[Tutorial](Workspace/Tutorial)

# Bootstrap: saiba neste guia para iniciantes o que é, por que e como usá-lo

Bootstrap é um framework front-end usado para desenvolver aplicações web e sites mobile-first, ou seja, com o layout adaptado à tela do dispositivo utilizado pelo usuário. Saiba tudo sobre essa tecnologia e como utilizá-la em uma aplicação front-end.

[Ivan de Souza](https://rockcontent.com/br/blog/author/ivan/)


12 dez, 19 | Leitura: 11min

![bootstrap](https://rockcontent.com/br/wp-content/uploads/sites/2/2020/04/bootstrap-1024x727.jpg)

**Bootstrap é um framework CSS utilizado em aplicações front-end**, ou seja, na camada de interface com o usuário para o desenvolvimento de aplicações adaptáveis à tela de qualquer dispositivo.

No [WordPress](https://rockcontent.com/br/blog/wordpress/), por exemplo, ele pode ser instalado como um tema ou ser utilizado para o desenvolvimento de plugins ou, ainda, dentro deles para estilizar suas funcionalidades. O objetivo do framework é oferecer uma experiência mais agradável ao usuário durante a utilização do site.

Por isso, ele conta com diversos recursos para configurar os estilos dos elementos da página de forma simples e eficiente, além de facilitar a construção de páginas que sejam, ao mesmo tempo, adaptadas para web e para dispositivos móveis. Portanto, é importante conhecer o potencial desse framework.

Pensando nisso, fizemos este guia completo para iniciantes, em que vamos mostrar:

- O que é o Bootstrap?
- Como o Bootstrap funciona?
- Quais são as funcionalidades do Bootstrap?
- Como baixar o Bootstrap?
- Como configurar e utilizar o Bootstrap?
- Quais são os motivos para usar o Bootstrap?

Quer saber mais sobre esse framework? Vamos lá!



## O que é o Bootstrap? 

O Bootstrap é um framework [CSS](https://rockcontent.com/br/blog/css/) desenvolvido pelo Twitter em 2010, com o objetivo de padronizar as ferramentas da empresa. Inicialmente era chamado de Twitter Blueprint e, um pouco mais adiante, em 2011, foi transformado em código aberto e teve o nome alterado para Bootstrap. Desde então, já passou por diversas atualizações e está atualmente na versão 4.4.

O framework combina CSS e [JavaScript](https://rockcontent.com/br/blog/javascript-e-seo/) para estilizar os elementos de uma página HTML. Ele permite muito mais que apenas mudar as cores de botões e links.

Trata-se de uma ferramenta que proporciona interatividade na página, pois oferece uma série de componentes que facilitam a comunicação com o usuário, como menus de navegação, controles de paginação, barras de progresso e muito mais.

Além de todas as funcionalidades que o framework oferece, **o seu principal objetivo é permitir a construção de sites responsivos para dispositivos móveis**. Isso significa que as páginas são desenvolvidas para funcionar em desktops, tablets e smartphones, de uma forma simples e bem organizada.

## Como o Bootstrap funciona?

**O Bootstrap é formado por uma série de arquivos CSS e JavaScript que são responsáveis por atribuir características específicas aos elementos da página.** Há um arquivo principal no framework, chamado bootstrap.css, que contém a definição para todos os estilos utilizados. Basicamente, a estrutura do framework é formada por dois diretórios:

- css: que contém os arquivos necessários para a estilização dos elementos e uma alternativa ao tema original;
- js: contém as versões do arquivo bootstrap.js (original e minificado), que é responsável por executar as aplicações de estilo que necessitam de manipulação interativa.

Para atribuir uma característica a um elemento, basta informar a classe correspondente na propriedade class do elemento a ser estilizado. Veja o exemplo:

```
<img src="nome-da-image.jpg" alt="texto alternativo" class="rounded-sm">
```

Nesse exemplo, foi atribuído o conteúdo “rounded-sm” para a propriedade da imagem. Trata-se de um estilo que adiciona cantos arredondados no elemento. Portanto, ao carregar a imagem, as características referentes a essa classe serão aplicadas no elemento.

## Quais são as funcionalidades do Bootstrap?

O Bootstrap oferece uma série de funcionalidades que podem ser implementadas em um site. Confira, a seguir, o que é possível fazer com essa ferramenta.

### Layout responsivo

Uma das principais funcionalidades do Bootstrap é permitir que a adaptação do layout da página seja feita de acordo com o tipo de dispositivo utilizado. Para garantir a responsividade, **o framework trabalha com a estilização do elemento <div> e com a utilização da classe container**.

Na prática, o elemento <div> funciona para criar uma série de grades, semelhante a uma tabela, que é capaz de estruturar a página de forma adaptável. As tabelas foram utilizadas no passado para tentar criar layouts responsivos, entretanto, havia limitações em função da definição da largura das colunas, o que inviabilizou a sua utilização em dispositivos menores, como os smartphones.

Já o elemento <div> é mais flexível, pois permite que a largura seja definida e redimensionada com facilidade. O Bootstrap atribui ao elemento <div> a característica da classe container, que funciona para determinar as dimensões adequadas para os elementos inseridos nesse espaço. Basicamente, o framework trabalha com três tipos de containers:

- container: em conjunto com a propriedade max-width, que determina qual é o tamanho da tela ideal para que haja a adaptação do layout da página;
- container-fluid: considera toda a largura da tela do dispositivo para a definição do layout. Para isso, é considerada a propriedade width:100% em todos os limites de tamanho de tela;
- container-{breakpoint}: considera width:100% até que um determinado tamanho seja atingido.

### Biblioteca de componentes

Outra funcionalidade interessante do framework é a quantidade de componentes que podem ser utilizados para **proporcionar maior interatividade e melhorar a comunicação com o usuário**. Confira, a seguir, alguns dos principais componentes do Bootstrap.

#### Alerts

O Bootstrap possibilita a configuração de forma simples e rápida de diferentes tipos de alertas, com cores específicas, de acordo com a situação. Para mostrar um alerta ao usuário para indicar atenção, por exemplo, basta utilizar a classe .alert-danger e será exibido uma caixa de texto com o fundo vermelho. Confira o exemplo a seguir:

```
<div class="alert alert-danger">
  <strong>Atenção!</strong> Cuidado com a mensagem de alerta!
</div>
```

#### Carousel

Um componente muito utilizado no Bootstrap é o Carousel. Trata-se de um slideshow, ou seja, uma ferramenta que permite a exibição de imagens de forma responsiva. Ele também possibilita a inclusão de efeitos especiais para a transição da imagem e controles de exibição, como os indicadores de próximo e anterior.

#### Navbar

Outro poderoso componente do framework é o Navbar, que permite a construção de um sistema de navegação responsivo. É possível configurar diferentes formas de apresentação do menu, como escolher entre o posicionamento lateral ou superior, e definir a forma de exibição, que pode ser estendida ou contraída.

Também é possível determinar a forma de exibição dos links do menu, que pode ser em formato de botão, link, menu suspenso, entre outras configurações, para **facilitar a implementação da navegação do site**.

## Como baixar o Bootstrap?

Existem diferentes formas de baixar o framework. Uma delas é fazer o download da versão compilada dos código CSS e JavaScript por meio da [página do Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/download/). Há também a opção de baixar o código-fonte do framework, já que ele é uma ferramenta de código aberto.

Quem não quiser baixar os arquivos pode ter acesso ao framework sem a necessidade de instalá-los no servidor. Na prática, os arquivos de instalação ficam em outro domínio, ou seja, em outro [DNS](https://rockcontent.com/br/blog/dns/). Para isso, é só utilizar os links para acessar o BootstrapCDN e, dessa forma, adicionar as referências para os arquivos necessários para a sua utilização.

Outra forma de baixar o framework é por meio de gerenciadores de pacotes. É importante dizer que **o Bootstrap pode ser utilizado com diferentes linguagens de programação**.

Por isso, ele pode ser baixado com o npm, do Node.js, com RubyGems, Composer ou Nuget, e utilizado para [criar um site](https://rockcontent.com/br/blog/como-criar-um-site/) em WordPress, em sites desenvolvidos em Ruby on Rails, em Asp.Net etc.

## Como configurar e utilizar o Bootstrap?

Existem diferentes formas de configurar o framework para utilizá-lo em uma aplicação web. Entretanto, para que ele funcione da maneira adequada, é preciso adicionar as bibliotecas JQuery e Popper.js, que são necessárias para a execução de alguns componentes do Bootstrap.

Para começar a usar o Bootstrap em uma página, é preciso **adicionar a referência dos principais arquivos do framework na página principal da aplicação**. Confira, a seguir, o código de uma página HTML com todas as referências necessárias para que o framework funcione.

```
<!doctype html>
<html lang="en">
 <head>
   <!-- Required meta tags -->
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
   <!-- Bootstrap CSS -->
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
   <title>Hello, world!</title>
 </head>
 <body>
   <h1>Hello, world!</h1>
   <!-- Optional JavaScript -->
   <!-- jQuery first, then Popper.js, then Bootstrap JS -->
   <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
   <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
   <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
 </body>
</html>
```

<Fonte: site [Getbootstrap.com](https://getbootstrap.com/docs/4.4/getting-started/introduction/#starter-template)>

É importante seguir a ordem das referências conforme o exemplo. Portanto, a primeira referência deve ser ao arquivo bootstrap.css localizado na tag <head>. Já as referências aos arquivos JavaScript devem ser inseridas no final da página, antes de encerrar a tag </body>. A ordem para os scripts devem ser: JQuery, Popper.js e Bootstrap.js.

Vale ressaltar que a forma de configurar o Bootstrap varia de acordo com o tipo de ambiente em que ele está. No WordPress, por exemplo, também é possível adicionar o framework por meio da alteração do arquivo functions.php do [template](https://rockcontent.com/br/blog/template/). Por isso, confira, a seguir, algumas dicas sobre como configurar e utilizar o Bootstrap.

### Faça um curso

Fazer um [curso](https://rockcontent.com/br/blog/cursos-online-gratuitos/) é a melhor forma de aprender com mais agilidade a utilizar as tecnologias disponíveis no mercado, como o Bootstrap. Isso porque contar com a ajuda de alguém nesse momento é importante para **entender as funcionalidades do framework e esclarecer as dúvidas** que nem sempre é possível solucionar em fóruns ou em buscas pela internet.

### Aprenda sobre plugins

Além das funcionalidades básicas, o Bootstrap também permite a [utilização de plugins](https://rockcontent.com/br/blog/como-instalar-um-plugin-no-wordpress/). Na prática, trata-se de uma série de recursos adicionais que ajudam a oferecer uma experiência ainda melhor ao usuário. Existem **diversos plugins gratuitos e pagos na internet** que podem ser baixados e utilizados com o framework.

### Tenha um bom guia por perto

Outra forma de aperfeiçoar o conhecimento no framework é por meio da consulta em guias de referência. O site oficial do Bootstrap, por exemplo, fornece uma **ampla documentação sobre todas as suas funcionalidades**, além de ser rico em exemplos. Além disso, existem diversos livros e sites de referência que ajudam a explorar ao máximo todo o potencial dessa ferramenta.

### Utilize a versão mais recente

Sempre que uma nova versão é lançada, há novas funcionalidades disponíveis, além de possíveis alterações em recursos já existentes. Portanto, é importante se certificar de **utilizar a última versão disponível do framework**, seja para aplicar em um site, seja para seu próprio aprendizado. Dessa forma, há a garantia de que os recursos utilizados na página sejam os mais atualizados.

**Você também pode se interessar por estes outros conteúdos!
** [**Stage: a solução completa em performance, conversão e segurança no seu WordPress**](https://rockcontent.com/br/blog/rock-stage/)**
** [**Entenda quais são os passos para a criação de um site profissional**](https://rockcontent.com/br/blog/como-fazer-um-site/)**
** [**Conheça os 10 melhores sites de domínio**](https://rockcontent.com/br/blog/melhores-sites-de-dominio/)

## Quais são os motivos para usar o Bootstrap?

De acordo com as estatísticas apresentadas pelo [site W3Techs](https://w3techs.com/), o Bootstrap ocupa a segunda posição como a biblioteca JavaScript mais utilizada, com 20,6% de sites que fazem uso da tecnologia. Existem diversas razões pelas quais vale a pena utilizar e aprender Bootstrap. Confira, a seguir, as principais delas.

### Mobile-first

O Bootstrap segue o conceito mobile-first. Isso significa que a preocupação do framework é, em primeiro lugar, **desenvolver uma página que funcione perfeitamente em dispositivos móveis** e, a seguir, em desktop.

A vantagem dessa estratégia é a garantia de ter um site que possa ser acessado por qualquer dispositivo, o que é essencial em função da quantidade de pessoas que utilizam o smartphone.

### Padrão visual

Os recursos disponíveis no Bootstrap oferecem uma experiência rica ao usuário. Isso porque **o padrão visual de estilização segue as tendências de design** utilizadas no momento. Além disso, existem inúmeros [temas](https://rockcontent.com/br/blog/temas-wordpress/) para Bootstrap gratuitos ou pagos que podem ser baixados na internet. 

### Reutilização de código

Para desenvolver muitas das funcionalidades existentes no Bootstrap, seria preciso escrever uma grande quantidade de linhas de código. Com isso, porém, há um aumento no tamanho dos arquivos e da quantidade de dados trafegadas para o carregamento da página.

Esses fatores podem prejudicar um bom rankeamento no Google e toda uma estratégia de [SEO](https://rockcontent.com/br/blog/o-que-e-seo/), pois o [tempo para o carregamento da página](https://rockcontent.com/br/blog/velocidade-do-site/) é uma das razões pelas quais o usuário desiste de esperar e vai embora do site.

Ao utilizar o framework, basta referenciar a classe ao elemento em que se deseja aplicar o recurso. Portanto, sua utilização elimina a necessidade de escrever muitas linhas de código e, ainda, contribui para **reduzir o tamanho dos arquivos trafegados**.

### Comunidade ativa

Por ser um framework de código aberto, o Bootstrap conta com uma comunidade ativa de desenvolvedores. Além de contribuir com as atualizações nas versões, o que é importante para **ter uma ferramenta sempre atualizada**, a comunidade também faz a manutenção da documentação, oferece um blog com dicas e novidades sobre a ferramenta, e ajuda em uma página no [site Stack Overflow](https://stackoverflow.com/questions). 

Como você pôde ver neste guia completo sobre o Bootstrap, **ele é um poderoso framework para o desenvolvimento de aplicações front-end responsivas** e oferece inúmeros componentes capazes de conferir um alto padrão visual às páginas. Para aprender a utilizar todos os seus recursos, invista em um bom curso, estude a variedade de plugins e consulte sempre um guia de referência.

Agora que você já conhece esse poderoso framework para aplicações front-end, que tal aprender um pouco mais sobre domínios de site? Então confira nosso conteúdo sobre [o que é WHOIS e como fazer uma consulta de domínio](https://rockcontent.com/br/blog/whois/)!




---

#### * DIO - Digital Inovation One *
######  [Inscreva-se na Dio](https://web.dio.me/sign-up?ref=R5J3ZLTIFS)  

######  [Vagner Bellacosa perfil na Dio](https://web.dio.me/users/vagnerbellacosa?tab=achievements)  

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/VagnerBellacosa/Curso_Bootstrap.svg?style=for-the-badge
[contributors-url]: https://github.com/VagnerBellacosa/Curso_Bootstrap/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/VagnerBellacosa/Curso_Bootstrap.svg?style=for-the-badge
[forks-url]: https://github.com/VagnerBellacosa/Curso_Bootstrap/network/members
[stars-shield]: https://img.shields.io/github/stars/VagnerBellacosa/Curso_Bootstrap.svg?style=for-the-badge
[stars-url]: https://github.com/VagnerBellacosa/Curso_Bootstrap/stargazers
[issues-shield]: https://img.shields.io/github/issues/VagnerBellacosa/Curso_Bootstrap.svg?style=for-the-badge
[issues-url]: https://github.com/VagnerBellacosa/Curso_Bootstrap/issues
[license-shield]: https://img.shields.io/github/license/VagnerBellacosa/Curso_Bootstrap.svg?style=for-the-badge
[license-url]: https://github.com/VagnerBellacosa/Curso_Bootstrap/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/VagnerBellacosa/
[product-screenshot]: BootCamps/images/capa.png