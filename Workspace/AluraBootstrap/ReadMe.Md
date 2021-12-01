# Bootstrap - O que é, como e quando usar?

![mulher em frente a dois monitores com código html e css ](https://www.alura.com.br/artigos/assets/bootstrap/fundo-bootstrap.jpg)

![guilherme-lima](https://cursos.alura.com.br/assets/images/forum/avatar_g.png)

guilherme-lima

21 de Julho

COMPARTILHE

- 
- 
- 
- 

[![img](https://www.alura.com.br/assets/api/formacoes/categorias/front-end.svg)Esse artigo faz parte daFormação HTML e CSS](https://www.alura.com.br/formacao-html-e-css)

![Na imagem, lê-se a palavra “Bootstrap” e uma tela de notebook com algumas linhas de código ](https://www.alura.com.br/artigos/assets/bootstrap/bootstrap.png)

Quando vamos criar um site, precisamos tomar diversas decisões, como qual banco de dados, linguagem e framework vamos usar, ou ainda onde faremos o deploy da aplicação.

Porém, um ponto muito importante é conseguir deixar nossa página com um visual bacana, customizando cores, fontes, margens e assim por diante. Para isso, precisamos estilizá-la por meio de inúmeras classes do CSS, o que não é uma tarefa simples para todos que desenvolvem.

Pensando nisso, vamos ver uma forma de estruturar e estilizar suas aplicações com Bootstrap.

### Bootstrap: O que é?

[Bootstrap](https://getbootstrap.com/) é um framework front-end que fornece estruturas de CSS para a criação de sites e aplicações responsivas de forma rápida e simples. Além disso, pode lidar com sites de desktop e páginas de dispositivos móveis da mesma forma.

Originalmente, o Bootstrap foi desenvolvido para o Twitter por um grupo de desenvolvedores liderados por Mark Otto e Jacob Thornton Logo e se tornou uma das estruturas de front-end e projetos de código aberto mais populares do mundo.

Antes de ser uma estrutura de código-fonte aberto, o Bootstrap era conhecido como [Twitter Blueprint](https://pt.wikipedia.org/wiki/Bootstrap_(framework_front-end)). Após alguns meses de desenvolvimento, o Twitter realizou sua primeira Hack Week: o projeto ganhou uma grande popularidade quando desenvolvedores de todos os níveis de habilidade usaram o framework sem qualquer orientação externa. Após o evento, ele serviu como guia de estilo para o desenvolvimento de ferramentas internas na empresa por mais de um ano antes de seu lançamento se tornar público.

### Como o Bootstrap é distribuído?

Geralmente, o Bootstrap é distribuído usando o [site oficial](https://getbootstrap.com/) e [npm](https://www.npmjs.com/). Você também pode criar sua própria distribuição usando o código-fonte, ou por meio da própria rede de distribuição de conteúdo conhecida como [CDN](https://pt.wikipedia.org/wiki/Rede_de_fornecimento_de_conteúdo) do Bootstrap. Um CDN permite que um site da web recupere com frequência arquivos públicos usados de servidores distribuídos globalmente.

### Como instalar o Bootstrap?

Na [página de download oficial](https://getbootstrap.com/docs/5.0/getting-started/download/) você encontra com detalhes todas as formas de instalar o Bootstrap.

Nós vamos aprender a instalá-lo via CDN.

Para alcançar o mesmo resultado deste artigo na sua instalação, crie uma pasta e um arquivo chamado `index.html`.

No arquivo, inclua o seguinte código:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo Bootstrap</title>
</head>
<body>
    <h1>O Bootstrap é bem legal</h1>
</body>
</html>
```

Ao abrir a página com navegador, teremos o seguinte resultado:

![Bootstrap no navegador com a frase "O bootstrap é bem legal" ](https://www.alura.com.br/artigos/assets/bootstrap/bootstrap-no-navegador.png)

Para incluir o Bootstrap, vamos acessar [este link](https://getbootstrap.com/docs/5.0/getting-started/download/#cdn-via-jsdelivr) e incluir o seguinte código na tag `head` da página:

```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
```

Nosso resultado será:

Confira o código completo:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <title>Exemplo Bootstrap</title>
</head>
<body>
    <h1>O Bootstrap é bem legal</h1>
</body>
</html>
```

### Componentes do Bootstrap

Na documentação, você encontra uma [série de componentes](https://getbootstrap.com/docs/5.0/components/alerts/) como referência para suas próprias criações, como [alertas](https://getbootstrap.com/docs/5.0/components/alerts/), [botões](https://getbootstrap.com/docs/5.0/components/buttons/), [menu](https://getbootstrap.com/docs/5.0/components/navs-tabs/), [formulários](https://getbootstrap.com/docs/5.0/forms/overview/), entre muitos outros.

### Vamos ver alguns exemplos práticos?

No Bootstrap, existe uma ampla gama de classes para alinhar margem responsiva e o espaçamento. Observe o exemplo abaixo utilizando a classe `mt-5` para alterar a margem superior do título da página:

![Bootstrap no navegador com a frase "O bootstrap é bem legal" ](https://www.alura.com.br/artigos/assets/bootstrap/bootstrap-classes.png)

```
<div class="mt-5">
            <h1>O Bootstrap é bem legal</h1>
</div>
```

Nosso resultado será:

![Bootstrap no navegador com a frase "O bootstrap é bem legal" ](https://www.alura.com.br/artigos/assets/bootstrap/bootstrap-h1.png)

Observe a lista de classes que podemos usar.

`m` -> define a margem

`p` -> define o padding

`t` -> define margem superior ou padding superior

`b` -> define a margem inferior ou padding inferior

`l` -> define a margem esquerda ou padding esquerdo

`r` -> define a margem direita ou padding direito

`x` -> define tanto padding esquerdo como padding direito ou margem esquerda e margem direita

`y` -> define tanto padding superior e padding inferior ou margem superior e margem inferior.

[**Aqui você pode encontrar mais detalhes sobre espaçamento.**](https://getbootstrap.com/docs/4.5/utilities/spacing/)

### Exemplo prático

Observe o seguinte layout:

![Bootstrap no navegador com a frase "O bootstrap é bem legal" ](https://www.alura.com.br/artigos/assets/bootstrap/bootstrap-layout.png)

Nele, há um menu com 3 links: Navbar, Home e Quem somos. Logo abaixo, vemos um título que diz `O Bootstrap é bem legal` e 2 inputs, um para email e outro com uma área de texto para escrever o que mais gostou no Bootstrap.

Para finalizar, temos 2 botões, um azul e outro vermelho, que dizem `Enviar` e `Voltar` respectivamente. Por fim, lê-se o texto `Parágrafo final centralizado`, ao centro.

[**Aqui você encontra o layout com código completo.**](https://github.com/guilhermeonrails/bootstrap-artigo-alura)

### Conclusão

Neste artigo, vimos que o Bootstrap é uma estrutura de código aberto HTML, CSS e JavaScript (inicialmente criada pelo Twitter) que você pode usar como base para criar sites ou aplicativos da web.

Quer aprender mais sobre Bootstrap? Olha esses links que separei:

- [Curso de Bootstrap 4](https://www.alura.com.br/curso-online-bootstrap-landing-page)
- [Sequência de cursos de HTML e CS](https://cursos.alura.com.br/formacao-html-e-css)