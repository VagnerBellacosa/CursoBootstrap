# Bootstrap: o que é, como usar e para que serve esse framework?

- por[Michelle Horn](https://blog.betrybe.com/author/michelle-horn/)
- 7 de janeiro de 2021
- 7 minutos de leitura

Antes de falarmos sobre o que é **Bootstrap**, vamos contar um pouco de sua história. O framework surgiu em 2010, quando dois funcionários do Twitter, chamados Mark Otto e Jacob Thornton, desenvolveram uma ferramenta para padronizar as [aplicações web](https://blog.betrybe.com/desenvolvimento-web/aplicacoes-web/) desenvolvidas pela empresa.

O objetivo era permitir a reutilização de [códigos](https://blog.betrybe.com/tecnologia/algoritmo/) entre as aplicações com maior facilidade, além de oferecer uma melhor adaptação em diferentes dispositivos. O nome original da ferramenta era Twitter Blueprint. Entretanto, o nome foi alterado para Bootstrap e sua primeira versão como um projeto de [código aberto](https://blog.betrybe.com/tecnologia/codigo-aberto/) foi lançada em 2011.

Para que você conheça mais sobre o framework, preparamos este post que contém os seguintes tópicos:

- [O que é Bootstrap e como ele funciona?](https://blog.betrybe.com/framework-de-programacao/o-que-e-bootstrap/#1)
- [Quais as principais funcionalidades do Bootstrap?](https://blog.betrybe.com/framework-de-programacao/o-que-e-bootstrap/#2)
- [Quais os três arquivos primários do Bootstrap?](https://blog.betrybe.com/framework-de-programacao/o-que-e-bootstrap/#3)
- [Como baixar o framework?](https://blog.betrybe.com/framework-de-programacao/o-que-e-bootstrap/#4)
- [Como usar o Bootstrap?](https://blog.betrybe.com/framework-de-programacao/o-que-e-bootstrap/#5)

Boa leitura!

O que é Bootstrap e como ele funciona?

Basicamente, o **Bootstrap** é um framework CSS para ser utilizado no [front-end de aplicações web](https://blog.betrybe.com/carreira/front-end-e-back-end/). Ele utiliza [JavaScript](https://blog.betrybe.com/javascript/) e CSS para estilizar as páginas e adicionar funcionalidades que vão além de apenas proporcionar um visual bonito ao site. Isso porque ele permite implementar menus de navegação, controles de paginação, formulários, janelas modais e muito mais.

A principal característica do Bootstrap é a responsividade do site, ou seja, seu objetivo é permitir que os elementos da página sejam readaptados para o acesso em diferentes dispositivos, como notebooks, tablets, smartphones e, até mesmo, para monitores maiores que os tradicionais.

Para utilizar os recursos do Bootstrap, basta referenciar seus arquivos principais na página principal e aplicar os estilos correspondentes nos elementos da página. É importante dizer que o Bootstrap pode ser utilizado em aplicações desenvolvidas em diferentes linguagens de programação e frameworks, entre elas: [PHP](https://blog.betrybe.com/desenvolvimento-web/php/), [Ruby](https://blog.betrybe.com/linguagem-de-programacao/ruby/), .Net, [Angular](https://blog.betrybe.com/framework-de-programacao/angular/) e em CMS, como o WordPress, ou em uma simples página [HTML](https://blog.betrybe.com/desenvolvimento-web/aprender-a-programar-em-html/).

Isso significa que ele se adapta bem a diferentes tipos de aplicações. Não é à toa que o Bootstrap é o segundo colocado entre as bibliotecas de JavaScript mais utilizadas no mercado, conforme o [comparativo no site W3Techs](https://w3techs.com/technologies/overview/javascript_library).

Quais as principais funcionalidades do Bootstrap?

O Bootstrap oferece muito mais utilidade que a simples estilização de elementos, pois ele contém uma série de recursos adicionais para a [construção de aplicações front-end funcionais e interativas](https://blog.betrybe.com/desenvolvimento-web/usabilidade/). Confira abaixo as principais funcionalidades do framework.

### Construção de layouts responsivos

O Bootstrap foi desenvolvido para ser mobile-first. Isso significa que todos os seus estilos e componentes foram criados para funcionar primeiro em dispositivos móveis e ampliados para outros tamanhos de telas. Por isso, **sua principal característica é facilitar a criação de sites responsivos**.

Para que o site se adapte em diferentes tipos de tela, o framework utiliza um sistema de grids, no qual é feita a ordenação dos elementos que compõem o layout da tela. Para isso, ele utiliza classes [CSS](https://blog.betrybe.com/desenvolvimento-web/aprenda-css-com-facilidade/) no elemento [HTML](https://blog.betrybe.com/desenvolvimento-web/tudo-que-voce-precisa-saber-sobre-html/) <div> representando containers, linhas e colunas para estruturar a página e dimensionar os elementos de forma harmônica.

### Estilizar os elementos da página

Outra funcionalidade do Bootstrap é oferecer estilos aos elementos da página. Portanto, só de utilizar o framework ele já aplicará uma estilização padrão aos elementos básicos. Assim, as fontes e seus tamanhos serão os mesmos em todas as páginas, as cores de links, a distância entre linhas em parágrafos e em muitas outras características de elementos.

É importante dizer que é possível customizar os padrões definidos no Bootstrap. Entretanto, não é recomendado editar os arquivos do framework. A modificação de estilos pode ser feita pela adição de um arquivo próprio para alterar a classe desejada.

Porém, é preciso seguir o [procedimento descrito na documentação do framework](https://getbootstrap.com/docs/4.5/getting-started/theming/) para que a customização seja realizada com sucesso. Além disso, é possível baixar temas para o Bootstrap. Existem diversas opções gratuitas e pagas para downloads na internet que oferecem diferentes estilos e layouts. 

### Imagens responsivas

O framework também permite o redimensionamento automático de imagens ao abrir a página em diferentes dispositivos. Portanto, não é necessário manter diversas cópias com dimensões diferentes do mesmo arquivo no [servidor](https://blog.betrybe.com/tecnologia/o-que-e-servidor/).

A adequação do tamanho é feita de forma proporcional e sem distorções por meio da aplicação da classe “img-fluid” no elemento imagem <img>. Além disso, o framework permite adicionar cantos arredondados, formatar as bordas e realizar o alinhamento de imagens.

### Biblioteca de componentes

O Bootstrap também oferece uma biblioteca de componentes. Trata-se de um conjunto de recursos que proporciona maior interatividade entre a página e a pessoa usuária. A utilização e configuração desses recursos são feitas basicamente da mesma forma, ou seja, por meio da aplicação de classes em elementos específicos da página. Entre os recursos disponíveis no framework estão:

- menu de navegação;
- galeria de imagens;
- [janelas modais de alerta](https://blog.betrybe.com/javascript/javascript-alert/);
- formulários;
- dropdown, que é um menu ou lista suspensa;
- paginação;
- barra de progresso.

É importante ressaltar que alguns componentes podem exigir a instalação de bibliotecas JavaScript adicionais para funcionar de maneira adequada. Por isso, é preciso consultar a documentação do framework sempre que for utilizar esses recursos. Um exemplo é o componente Carousel, que é uma galeria de imagens e requer a utilização da biblioteca util.js.

Newsletter da Trybe

Junte-se a mais de 100.000 pessoas da nossa tribo que recebem conteúdos gratuitos e exclusivos em nossa newsletter semanal!

Quais os três arquivos primários do Bootstrap?

O framework Bootstrap é formado por um conjunto de arquivos JavaScript e [CSS](https://blog.betrybe.com/desenvolvimento-web/entenda-css/). Entretanto, existem alguns que são mais importantes por serem essenciais para que ele funcione de maneira adequada. Veja quais são eles, a seguir.

### Bootstrap.css 

Esse é um arquivo de folha de estilo, que contém todas as classes utilizadas para estilizar os elementos básicos da página HTML. Além disso, ele também traz a configuração das classes necessárias para a elaboração de layouts responsivos, bem como para a formatação de tabelas, de menus de navegação e muito mais.

### Bootstrap.js 

Alguns recursos e componentes do Bootstrap necessitam da execução de funções JavaScript para funcionarem de maneira correta, por exemplo: as janelas modais, que exibem mensagens de alerta e botões de confirmação à pessoa usuária, o controle de paginação e muitas outras funcionalidades do [framework](https://blog.betrybe.com/framework-de-programacao/o-que-e-framework/). Por isso, ele contém o arquivo chamado “bootstrap.js”.

### Glyphicons

A [utilização de ícones](https://blog.betrybe.com/tecnologia/favicon/) e símbolos em uma página são essenciais para oferecer uma apresentação mais amigável, funcional e elegante às pessoas usuárias. O Bootstrap utiliza o Glyphicons para isso. Trata-se de uma biblioteca que oferece uma série desses elementos para ser utilizados gratuitamente junto com o framework.

Vale ressaltar que o Glyphicons também oferece pacotes pagos de ícones e símbolos. Portanto, é possível utilizar ainda mais elementos para melhorar a aparência e funcionalidades do site.

Como baixar o framework?

O Bootstrap oferece diferentes formas de download e instalação. Uma das opções é baixar o framework a partir da página oficial da ferramenta. Estão disponíveis para download tanto a versão [compilada](https://blog.betrybe.com/tecnologia/compilacao/) quanto os [códigos fontes](https://blog.betrybe.com/tecnologia/codigo-fonte/).

É importante dizer que o Bootstrap também precisa de outras bibliotecas JavaScript para a utilização de alguns de seus componentes. Por isso, é necessário adicionar a referência do jQuery e do Popper.js.

A ordem em que as referências das bibliotecas são adicionadas na página também é importante para garantir o funcionamento de todos recursos. Mais adiante, mostraremos um exemplo de como referenciar os arquivos do framework.

Além disso, o Bootstrap pode ser baixado e instalado por meio de diferentes gerenciadores de pacotes, entre eles:

- NPM;
- Yarn;
- RubyGems;
- Composer;
- NuGet.

Quem não quiser realizar o download ou fazer a instalação do Bootstrap, pode utilizar o BootstrapCDN. Nessa opção, o framework está disponível em uma CDN e basta referenciar os arquivos principais para utilizá-lo em um site.

Como usar o Bootstrap?

Se a opção escolhida para a instalação do framework foi download, basta extrair o seu conteúdo na pasta desejada no site ou no ambiente de desenvolvimento. Já, se a instalação foi feita por meio de gerenciadores de pacotes, ele será adicionado na pasta específica criada para as dependências do projeto. No npm, por exemplo, o conteúdo será adicionado na pasta “node_modules”.

A seguir, é preciso adicionar as referências na página principal do projeto. É preciso atenção quanto à forma de realizar esse procedimento. O arquivo “bootstrap.css” deve ser referenciado logo no início, dentro da tag <head> da [página HTML](https://blog.betrybe.com/desenvolvimento-web/comandos-e-tags-html/). Já a adição dos scripts deve ser feita no final da página, antes do fechamento da tag <body>.

A ordem dos scripts também deve ser respeitada para que o framework não apresente [falhas](https://blog.betrybe.com/tecnologia/o-que-e-bug/). Portanto, a primeira referência deve ser à biblioteca jQuery, seguido do Popper.js e, por fim, do arquivo “bootstrap.js”. Vale ressaltar que a instalação dessas bibliotecas no projeto pode ser feita por meio dos gerenciadores de pacotes citados acima ou adicionando os links para as versões armazenadas em CDN.

Para facilitar a visualização, vamos mostrar um exemplo simples de código “[Olá, Mundo](https://blog.betrybe.com/desenvolvimento-web/hello-world-ola-mundo/)!” de uma página HTML com as configurações necessárias para usar o Bootstrap. Perceba que criamos uma estrutura básica de layout com um container com duas linhas e duas colunas na segunda linha para demonstrar como utilizar as respectivas classes. Veja o código.

![img](https://blog.betrybe.com/wp-content/uploads/2021/01/image-1024x798.png)



Vale dizer que esse é somente um exemplo, existem outras formatações possíveis, assim como outras classes no framework para a estruturação de layouts. Nesse exemplo, também utilizamos uma imagem na primeira linha para mostrar como é feito o redimensionamento em diferentes tamanhos de telas com o mesmo arquivo.

Agora você já sabe o que é Bootstrap e como utilizá-lo em uma aplicação web. Portanto, aproveite as funcionalidades disponíveis nesse framework para desenvolver páginas que podem ser acessadas em diferentes dispositivos, além de oferecer um visual elegante e funcional às pessoas usuárias!

Gostou do nosso conteúdo sobre o que é Bootstrap? Então, confira nosso post sobre [o que é Web Design e como trabalhar nessa área](https://blog.betrybe.com/carreira/web-design/)!