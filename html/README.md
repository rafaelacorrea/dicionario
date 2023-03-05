# Tags necessárias: 

```html
<head>/<body> - Toda estrutura html precisa de um <head> (cabeça) e <body> (corpo) para se manter estruturado, assim como o <html> para englobar toda essa estrutura. É usando o <html> que nós informamos ao navegador que vamos exibir na tela uma página html e assim renderizar o conteúdo da forma certa.
```
```html
<title> -  Dentro dessa "cabeça" (head) nós precisamos de um título, um nome para essa página que irá aparecer na aba do navegador.
```
```html
<header> - Toda página html que se preze precisa de um cabeçalho e para fazer isso precisamos colocá-la dentro da tag <body>. E dentro do header podemos inserir o título da nossa página (um <h1>, por exemplo), um menu (usando a tag <nav>).
```
```html
<section> -  Como o próprio nome já diz a sessão é uma tag que serve pra gente dividir partes do nosso site em seções, num exemplo mais lúdico: imagine que você está em um supermercado. Dentro dele há diversas seções: seção de laticínios, limpeza, açougue, etc. A section poderia ser definida assim. Nós dividimos cada bloco de informação dentro do nosso html, então, por exemplo, você tem a página da PrograMaria onde na primeira seção (<section>) aparece uma foto que ocupa a tela inteira com uma frase de boas-vindas e aí logo abaixo dessa foto principal existe uma outra sessão que mostra uma breve história da Programaria.
```
```html
<div> - A div é uma tag que nos ajuda a dividir nossos elementos em blocos, então se você precisa criar um bloco de elemento no qual irá exibir uma foto e texto dentro de uma seção você pode usar uma div para englobar esse conteúdo. Na div podemos atribuir uma ID ou CLASS:

ID - as id’s são únicas. Cada elemento poderá conter apenas 1 id. Não é recomendado usar várias id’s dentro uma página ou bloco. Se você quiser atribuir um nome a outro bloco é necessário usar o class.

CLASS - ao contrário das id’s, as classes não são únicas e você pode atribuí-las a qualquer elemento. Você também pode usar a mesma classe para outros elementos.
É necessário usá-la para definir os nossos estilos no CSS.
```
```html
<footer> - O nosso rodapé. Geralmente utilizamos para colocar informações de direitos autorais (copyright), links de redes sociais, email, telefone.
```
```html
<h1> - Os hipertextos como vocês já sabem existem vários (h1, h2, h3, h4, h5, h6), mas vou falar apenas do <h1> em específico porque é o que geralmente utilizamos numa página html para definirmos o título da nossa página dentro do header. 
```
```html
<p> - O <p> serve para definirmos o nosso parágrafo, textos corridos, separando em quebra de linhas.
```
```html
<a> - O hiperlink, ou simplesmente link, é o que nós utilizamos para criar textos clicáveis, igual a que algumas de vocês fizeram lá no site final da Ada para conseguir acessar alguns itens da página. 
```
```html
<img> - A tag de imagem nos permite adicionar imagens no nosso html. Voltando ao projeto da Ada, foi através dessa tag que vocês conseguiram mostrar uma foto dela, por exemplo.
```
```html
<details> - é a nossa tag principal para a criação do accordion. Sem ela não conseguimos fazer o efeito funcionar. É através dela que conseguimos especificar o que estará dentro do nosso accordion.
```
```html
<summary> -  é o nosso sumário, a tag que define um cabeçalho para o elemento <details>. É através dele que o título do nosso accordion se torna clicável, permitindo que a gente visualize/oculte detalhes.

Lembrando que para o accordion funcionar é necessário que o mesmo esteja dentro do <details>. 
```
```html
<blockquote> - Tag que nos permite criar blocos de marcação indicando que aquele texto é uma citação, ajudando o navegador a entender o que é aquilo, semanticamente falando. Junto com o blockquote há também uma outra tag na qual podemos utilizar que é o <q>.
```
```html
<q> -  Nada mais é do que o quote, com ele costumamos usar para adicionar aspas em pequenas frases.
```