# Acessibilidade aplicada: agrupar o conteúdo no elemento do artigo

`article` é outro dos novos elementos HTML5 que adiciona significado semântico à sua marcação. `article` é um elemento de seção e é usado para agrupar conteúdo independente e independente. A tag funciona bem com entradas de blog, postagens em fóruns ou artigos de notícias.

Determinar se o conteúdo pode ser autônomo é geralmente uma decisão judicial, mas existem alguns testes simples que você pode usar. Pergunte a si mesmo se você removeu todo o contexto circundante, esse conteúdo ainda faria sentido? Da mesma forma para o texto, o conteúdo aguentaria se estivesse em um feed RSS?

Lembre-se de que as pessoas que usam tecnologias assistivas dependem de marcações organizadas, semanticamente significativas, para entender melhor seu trabalho.

- Observe sobre `section` e `div` 

O `section` elemento também é novo no HTML5 e tem um significado semântico ligeiramente diferente de `article` . An `article` é para conteúdo autônomo e a `section` é para agrupar conteúdo relacionado tematicamente. Eles podem ser usados ​​um no outro, conforme necessário. Por exemplo, se um livro é o `article` , então cada capítulo é um `section` . Quando não houver relação entre grupos de conteúdo, use a `div`.

```
<div> - groups content
<section> - groups related content
<article> - groups independent, self-contained content
```