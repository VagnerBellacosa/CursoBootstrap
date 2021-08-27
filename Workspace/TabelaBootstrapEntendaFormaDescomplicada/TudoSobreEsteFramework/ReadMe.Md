# O que é Bootstrap: Tudo sobre este Framework

![O que é Bootstrap](https://www.homehost.com.br/blog/wp-content/uploads/2019/08/download.jpg)

Você sabe o que é o Bootstrap, para que serve e como utilizar? Neste artigo vamos entender o que é, como surgiu e como utilizar o principal framework CSS da atualidade. Também veremos sobre suas vantagens e desvantagens.

Portanto, você encontrará os seguintes tópicos:

- [O que é o Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top01)
- [Como surgiu o Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top02)
- [A importância do Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top03)
- [Como usar o Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top04)
- [O que eu posso fazer](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top08)
- [Características e Vantagens do Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top05)
- [Desvantagens de usar o Bootstrap](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top06)
- [Usar ou não usar?](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/#top07)

 



## O que é o Bootstrap

O Bootstrap nada mais é que um framework Front End utilizados por milhares de desenvolvedores web pelo mundo. A partir dele, muitas etapas do desenvolvimentos web se tornam mais rápidas e dinâmicas, pois já trazem consigo diversos elementos prontos e estilizados.

Ele é uma ferramenta gratuita para desenvolvimento [HTML](https://www.homehost.com.br/blog/criar-sites/html-basico/), [CSS](https://www.homehost.com.br/blog/criar-sites/html-css/) e JS. Portanto, é uma ferramenta de código fonte aberto para todos. Contudo, hoje em dia, é o framework Front End mais conhecido e mais utilizado pelo mundo.

## Como surgiu o Bootstrap

Como uma tentativa de resolver uma incompatibilidade dentro da própria equipe, os engenheiros Jacob Thorton e Mark Otto, criaram em 2010 o que é hoje o Bootstrap.

O objetivo inicial era otimizar o desenvolvimento através da adoção de uma estrutura única, reduzindo assim, inconsistências entre as diversas formas de codificar que variavam de cada profissional. E a tentativa deu tão certo que eles perceberam o grande potencial da ferramenta, lançando-a no GitHub como um software livre.

Sendo lançado no GitHub no segundo semestre de 2011, o framework logo ganhou fama, sendo uma das ferramentais mais populares no GitHub já no começo de 2012.

O Bootstrap oferece uma enorme variedade de Plugins e temas compatíveis com outros frameworks. Além disto, possui integração com qualquer linguagem de programação. Também é um software de código aberto, gratuito. Em pouco tempo após o seu lançamento já recebeu a contribuição de inúmeros desenvolvedores de todo o planeta. Desta forma, tornando-o o software livre mais ativo do mundo.

## A importância do Bootstrap

Conforme explicado anteriormente, o Bootstrap é hoje um dos frameworks/Front End mais utilizados pelo mundo inteiro. Portanto, sua importância para a criação de websites é de enorme referência.

Seus padrões seguem os princípios de usabilidade e as tendências de design para interfaces. Além disso, sua padronização permite que os sites tenham um visual atraente, ou seja, uma forma de [criar páginas](https://www.homehost.com.br/blog/criar-sites/criar-site-profissional/) esteticamente agradáveis.

## Como usar o Bootstrap

Para utilizar faça o download do Bootstrap no site [oficial](https://getbootstrap.com.br/) da ferramenta. Adicione os arquivos “bootstrap.min.css” e “bootstrap.min.js” nas pastas correspondentes a eles dentro do seu site. Depois, é só chamar o CSS e o JS dentro da [tag](https://www.homehost.com.br/blog/criar-sites/tags-html/) **<head>** do[ HTML.](https://www.homehost.com.br/blog/criar-sites/html-basico/) É importante lembrar que este framework acessa a biblioteca jQuery para ativar o comportamento de seus plugins. Portanto, lembre-se de inseri-lo em sua página para que tudo funcione perfeitamente.

Outra forma, é chamando através de um artigo externo, conforme o próprio exemplo do Bootstrap:

#### CSS

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
```

#### JavaScript

```
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

#### Template inicial

Dessa forma, temos o template inicial conforme o código abaixo:

```
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <!-- Meta tags Obrigatórias -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Olá, mundo!</title>
  </head>
  <body>
    <h1>Olá, mundo!</h1>

    <!-- JavaScript (Opcional) -->
    <!-- jQuery primeiro, depois Popper.js, depois Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```



## O que eu posso fazer

Com o Bootstrap é possível realizar a criação de interfaces gráficas para sua página na web de forma rápida e fácil. Portanto, é possível fazer diversas coisas. Você pode estar estudando a variedade de opções através da [documentação](https://getbootstrap.com.br/docs/4.1/getting-started/introduction/) do Bootstrap. Vamos citar aqui alguma das principais ferramentas utilizadas para o desenvolvimento com este framework.

#### 1. Utilizar layout de Grid responsivo

Inicialmente, temos que utilizar a [meta tag](https://www.homehost.com.br/blog/criar-sites/meta-tag/) para ativar o responsivo em nossa página. Basta incluir no Head do nosso documento a seguinte linha de código:

```
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
```

Com isso podemos utilizar facilmente o [sistema de contêiner](https://www.homehost.com.br/blog/criar-sites/html-div/) e [grid](https://getbootstrap.com.br/docs/4.1/layout/grid/) do Bootstrap para poder realizar a criação de interfaces gráficas responsivas. Como por exemplo no código abaixo:

```
<div class="container">
    <div class="row">
        <div class="col-sm">
          Uma de três colunas
        </div>
        <div class="col-sm">
          Uma de três colunas
        </div>
        <div class="col-sm">
          Uma de três colunas
        </div>
    </div>
</div>
```

Com isso, obtemos uma página com 3 colunas de proporções idênticas. Porém, graças a classe col-sm, ao chegar no tamanho de 576px (tamanho do valor SM), ela realiza uma quebra de linhas automaticamente. Inicialmente teremos algo como na imagem abaixo:

![Exemplo de colunas responsivas com bootstrap](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/exemplo01.jpg)

Ao chegarmos a uma tela com valor de 576px ou menor, é realizado a quebra de linha e obtemos então algo como na imagem abaixo:

![Exemplo de colunas no modo responsivo com bootstrap](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/exemplo02.jpg)

#### 2. Criar tabelas

Com o Bootstrap, podemos estar criando [tabelas Bootstrap](https://www.homehost.com.br/blog/criar-sites/tabela-bootstrap/) com padrões pré definidos de uma forma rápida e simples. Vejamos o exemplo abaixo:

```
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Nome</th>
      <th scope="col">Sobrenome</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>João</td>
      <td>Antônio</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>André</td>
      <td>Luís</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Bruno</td>
      <td>Junior</td>
    </tr>
  </tbody>
</table>
```

Dessa forma, teremos como resultado algo como na imagem abaixo:

![Tabela ](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/exemplo03.jpg)

Você pode estar aprendendo mais sobre tabelas em [nosso artigo sobre tabelas](https://www.homehost.com.br/blog/criar-sites/tabela-bootstrap/) Bootstrap. Com a leitura desse artigo você será capaz de [criar qualquer tabela](https://www.homehost.com.br/blog/criar-sites/tabela-html/) com esse framework.

#### 3. Criar figuras com estilos bases

Use as classes **.figure**, **.figure-img** e **.figure-caption** para conseguir alguns estilos bases para os elementos [HTML5](https://www.homehost.com.br/blog/uncategorized/html5/) **<figure>** e **<figcaption>**. Imagens na [tag](https://www.homehost.com.br/blog/criar-sites/tags-html/) **<figure>** não possuem tamanhos explícitos, por isso, tenha certeza de colocar a classe **.img-fluid** no elemento [****](https://www.homehost.com.br/blog/criar-sites/html-img/), para fazer com que ela seja responsiva.

Vejamos um simples exemplo abaixo:

```
<figure class="figure">
  <img src=".../400x300" class="figure-img img-fluid rounded" alt="figura generica de 400x300">
  <figcaption class="figure-caption text-right">Uma legenda para a imagem acima.</figcaption>
</figure>
```

Com isso teremos como resultado algo como na imagem abaixo:

![Figura com legenda a direita](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/exemplo04-300x240.jpg)

#### 4. Criar um modal Bootstrap

Com o framework é possível estar criando um [modal](https://www.homehost.com.br/blog/tutoriais/modal-bootstrap/). Um modal é basicamente uma janela que abre sobre o conteúdo da página sem se desfazer dele. Como na imagem abaixo:

![Modal Bootstrap](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/exemplo05.jpg)

Você pode estar lendo mais a respeito e aprendendo a criar o seu próprio modal bootstrap [em nosso artigo sobre](https://www.homehost.com.br/blog/tutoriais/modal-bootstrap/).

##### 5. Botões

Os [botões Bootstrap](https://www.homehost.com.br/blog/criar-sites/botao-bootstrap/) são botões personalizados, com suporte a tamanhos, estilos e muito mais. Portanto, são [utilizados dentro de formulários,](https://www.homehost.com.br/blog/criar-sites/formulario-html/) diálogos ou outras coisas.

O Bootstrap possui vários estilos de botões pré-definidos para diversos propósitos, além de outros recursos extras para mais controle.

Vejamos o exemplo abaixo:

```
<button type="button" class="btn btn-primary">Primary</button> 
<button type="button" class="btn btn-secondary">Secondary</button> 
<button type="button" class="btn btn-success">Success</button> 
<button type="button" class="btn btn-danger">Danger</button> 
<button type="button" class="btn btn-warning">Warning</button> 
<button type="button" class="btn btn-info">Info</button> 
<button type="button" class="btn btn-light">Light</button> 
<button type="button" class="btn btn-dark">Dark</button> 
<button type="button" class="btn btn-link">Link</button>
```

Dessa forma temos diversos tipos de botões como na imagem abaixo:

![Botões bootstrap](https://www.homehost.com.br/blog/wp-content/uploads/2019/09/Sem-t%C3%ADtulo-1.jpg)

Você pode estar lendo mais sobre em [nosso artigo sobre botões](https://www.homehost.com.br/blog/criar-sites/botao-bootstrap/) Bootstrap, onde explicamos detalhadamente. Com a leitura deste, temos a certeza que você conseguirá criar e utilizar botões a vontade em suas páginas com o Bootstrap.

#### 6. E muito mais

Além de tudo que citamos, é possível fazer muito mais. O Bootstrap é um framework bem completo e extremamente poderoso. Com ele você é capaz de criar páginas modernas completas. Portanto recomendamos a [leitura da documentação](https://getbootstrap.com.br/docs/4.1/getting-started/introduction/) para o aprendizado assim como ver alguns [exemplos que estão disponibilizados](https://getbootstrap.com/docs/4.3/examples/).

## Características e Vantagens do Bootstrap

Agora, vamos ver mais a fundo as características que fazem este framework valer a pena. Entre elas:

- Biblioteca de componentes;
- Reuso de código;
- Documentação e comunidade;
- Padrão visual;
- Responsividade.

#### Biblioteca de componentes

Talvez uma das características mais interessantes deste framework é o fato dele possuir uma extensa biblioteca de componentes, como ícones, caixas de texto, painéis e cores em links.

#### Reuso de código

Assim como é objetivo de todo framework, ele permite que menos código possa ser escrito, já que ele entrega uma série de formatações visuais prontas. A única necessidade do desenvolvedor é saber qual a classe ele deve chamar.

Se você já é desenvolvedor, deve saber como este recurso pode ser útil na sua vida. Menos código digitado significa uma excelente forma de ganhar tempo.

#### Documentação e Comunidade

No site oficial do Bootstrap, você encontra uma documentação bem completa do framework. Por ter uma documentação sempre atualizada e de fácil acesso, tirar dúvidas da ferramenta é extremamente fácil.

Não apenas dúvidas, mas uma documentação atualizada permite que as melhores práticas de programação com o framework sejam conhecidas. Isto aumenta a chance de novos projetos serem feitos com qualidade visual e técnica, o que é ótimo para o valor final do produto.

#### Responsividade

O Bootstrap traz consigo um sistema de layout 100% responsivo, o que facilita muito a vida do desenvolvedor. Utilizando apenas o Bootstrap é capaz de manter a página completamente responsiva. E isso tudo com poucas linhas de código.

## Desvantagens de usar o Bootstrap

Apesar de tantas qualidades, o uso do Bootstrap, assim como de qualquer ferramenta, também tem suas desvantagens.

A principal desvantagem seu uso é o excesso de padronização. Por ser muito utilizado mundo afora, é possível perceber vários sites que seguem um mesmo padrão, como se fossem praticamente cópias um dos outros. Isso torna ruim do ponto de vista de inovação. Porém, ainda assim, não é um fator decisivo que comprometa o uso ou desuso do framework.

Outra desvantagem, é que, para desenvolvedores mais avançados, soluções caseiras podem ser muito melhor. Pois, permitem melhores customização dos elementos. Claro que com o domínio dos dois, é possível mesclar entre o framework e estilização próprias.

## Usar ou não usar?

Agora que você já sabe o que é, todas suas vantagens e também desvantagens, cabe a cada um decidir seu deve implementa-los em seu projetos ou não. Porém, independente de seu uso, conhecer seus recursos é muito importante para um desenvolvedor, pois diversas páginas são feitas utilizando esta ferramenta.