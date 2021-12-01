# Bootstrap

## O Que é Bootstrap?
##### Andrei L.

É bem provável que você esteja familiarizado com a funcionalidade dos frameworks. 

O conjunto de sintaxes de tarefas específicas que eles têm permite que os desenvolvedores construam sites muito mais rapidamente porque não é preciso se preocupar com comandos básicos e funções adicionais. 

Mesmo assim, existia uma falta de consistência devido ao uso demasiado de bibliotecas, o que acabou exigindo uma mudança rígida. O Bootstrap apareceu como a resposta para essa questão.   

O framework front-end e de código-aberto foi inicialmente criado por Mark Otto e Jacob Thornton para o desenvolvimento web mais rápido e prático. 

Ele contém todos os tipos de templates baseados em HTML e CSS para várias funções e componentes. Por exemplo, navegação, sistema de grades, carrosséis de imagens e botões. A lista não é exaustiva. 

Ainda que os Bootstraps realmente poupem o tempo que os desenvolvedores gastam para gerenciar seus templates, o objetivo principal dele é criar sites responsivos. 

Ele permite que a interface do usuário de um site seja otimizado para qualquer tamanho de tela, desde os dispositivos móveis até as telas mais robustas de computadores potentes.

Por conta disso, os desenvolvedores não precisam se preocupar em fazer muitas versões de um mesmo site para todos os tipos e tamanhos de telas disponíveis. Isso também não faz com que a audiência fique limitada.

Pela sua popularidade, mais comunidades sobre o Bootstrap têm surgido. Estes locais são ótimos para desenvolvedores e designers trocarem experiẽncia, conhecimento e discutir as últimas atualizações para as funções disponíveis.  

## Os 3 Arquivos Primários do Bootstrap

Como o Bootstrap consiste em uma coleção de sintaxes que desempenham funções específicas, ele só faz sentido quando  o framework tem diferentes tipos de arquivos consigo. 

Abaixo estão os 3 tipos de arquivos primários que gerenciam a interface de usuário e a funcionalidade de um site. 

### Bootstrap.css

Bootstrap.css é um framework CSS que organiza e gerencia o layout de um site. Enquanto o HTML gerencia o conteúdo e a estrutura de uma página na web, o CSS lida com o layout dela. Por essa razão, ambas as estruturas precisam coexistir para desempenhar uma ação particular.

Por conta das suas funções, o CSS permite criar um visual uniforme em quantas páginas e do jeito que você quiser. Diga adeus às horas de edição manual só para mudar a largura de uma borda numa linha.

Com CSS, tudo o que você precisa fazer é referenciar as páginas web no arquivo CSS. Qualquer alteração necessária pode ser feita nesse mesmo arquivo sozinho.

As funções do CSS não são limitadas a estilo de texto. Eles também podem ser usados para outros aspectos de uma página, como a disposição dos elementos e de imagens e também tabelas. 

Como o CSS tem muitas declarações e seletores, memorizar todos eles pode levar algum tempo. Sabemos que você está sedento para começar; então, fique com essa listagem de códigos CSS prontos para encurtar o processo de aprendizado.  

### Bootstrap.js

O arquivo Bootstrap.js é a parte central do Bootstrap. Ele consiste em arquivos JavaScript, responsáveis pela interatividade de um site.

Para poupar tempo em sempre terem que escrever sintaxes de JavaScript, os desenvolvedores tendem a usar jQuery. Essa é uma plataforma de código-aberto popular que permite adicionar várias funcionalidades em um site. 

Abaixo temos alguns exemplos do que o jQuery pode fazer:

- Executar funções Ajax, como remover dados de outros locais e de forma dinâmica;
- Criar widgets usando uma coleção de plugins JavaScript;
- Criar animações personalizadas usando propriedades do CSS;

Adicionar dinamismo e interatividade aos conteúdos de um site.
Mesmo que um Bootstrap com propriedades CSS e elementos HTML funcione bem, ele precisa do jQuery para criar um design responsivo. Caso contrário, você vai poder usar apenas as partes estáticas e inativas do CSS.

Precisa de mais informação? Acesse este artigo e aprenda mais sobre jQuery!

## Glyphicons 

Ícones são uma parte integral do front-end de um site. Eles são frequentemente associados com certos tipos de ações e dados disponíveis na interface do usuário. E o Bootstrap usa os Glyphicons para preencher essa necessidade. 

O Bootstrap já tem vários símbolos Glyphicons gratuitos já desbloqueados para usar desde o começo. A versão gratuita dele tem um visual padrão, mas dá conta do recado para as funções mais essenciais. 

Se você quer encontrar ícones mais estilosos, o Glyphicons vende vários conjuntos de ícones premium que, com certeza, vão fazer com que sites de nichos mais específicos tenham um visual deslumbrante. 

Se quiser, também é possível fazer download de ícones baseados em temas específicos. E sem gastar nada. Eles estão disponíveis em sites como Flaticon, GlyphSearch e Icons8.  

Alguns desses ícones podem ser afetados pelo CSS para que tenha designs diferentes, enquanto outros podem permanecer dna forma padrão. O mais indicado é usar aqueles que mais se encaixam com a proposta e as necessidades do seu site. 

## Como Usar o Bootstrap?

Para ter um entendimento melhor de como usar Bootstrap, dê uma olhada no exemplo abaixo.

'''
<html lang="en">
<head>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1" /> 
<title>Bootstrap 101 Template</title>
<link href="css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>
<h1>Hello, world!</h1>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="js/bootstrap.min.js"></script>
</body>
</html>
...

Agora, vamos destrinchar cada trecho apresentado no código acima.

> meta charset="utf-8"

Mostra o conjunto de caracteres usado para escrever o site.

> meta http-equiv="X-UA-Compatible"

Determina a versão do Internet Explorer que deve renderizar a página. Usando a versão Edge do navegador, ele fica configurado para usar o modo mais elevado disponível.

> meta name="viewport"

Garante que a página tem a proporção de 1:1 em qualquer tamanho de visualização.

> link href="css/bootstrap.min.css" rel="stylesheet"

É a parte onde adicionamos o CSS do Bootstrap.  

> src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"

Carrega o jQuery pelo CDN do Google. É melhor carregá-lo de um CDN via HTTP, pois os arquivos podem ficar armazenados em cache por um ano.

> src="js/bootstrap.min.js

Adiciona o JavaScript do Bootstrap. Essa sintaxe deve ser sempre abaixo da sintaxe do jQuery para funcionar corretamente. E o processo de adição pode ser feito pela URL do Google ou por download manual. 

## Conclusão

O Bootstrap é um framework gratuito que tem ganhado cada vez mais popularidade entre os desenvolvedores front-end.

Ele pode ser usado facilmente e poupa muito tempo dos desenvolvedores em não ter mais que escrever manualmente as sintaxes todas as vezes que forem programar.

O framework também é muito flexível e pode acomodar quase todas as necessidade do desenvolvimento web front-end. As suas melhores habilidades incluem, mas não se limitam, a funções que permitem que páginas na internet funcionem em telas de qualquer tamanho. 

Se você é um desenvolvedor front-end, essa é a hora perfeita para começar a usar Bootstrap! 

[Artigo original](https://www.hostinger.com.br/tutoriais/o-que-e-bootstrap)