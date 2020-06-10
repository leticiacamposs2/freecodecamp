# Acessibilidade aplicada: melhore a acessibilidade do campo de formulário com o rótulo Elemento

Melhorar a acessibilidade com a marcação HTML semântica se aplica ao uso de nomes de tags apropriados e de atributos. Os próximos desafios abrangem alguns cenários importantes usando atributos em formulários.

A `label` tag agrupa o texto para um item de controle de formulário específico, geralmente o nome ou o rótulo de uma escolha. Isso vincula o significado ao item e torna o formulário mais legível. O `for` atributo em uma `label` tag associa explicitamente isso `label` ao controle de formulário e é usado pelos leitores de tela.

Você aprendeu sobre os botões de opção e seus rótulos em uma lição na seção HTML básico. Nessa lição, colocamos o elemento de entrada do botão de opção em um `label` elemento junto com o texto do rótulo para tornar o texto clicável. Outra maneira de conseguir isso é usando o `for` atributo conforme explicado nesta lição.

O valor do `for` atributo deve ser o mesmo que o valor do `id` atributo do controle de formulário. Aqui está um exemplo:

```
<form>
  <`label`  for="name">Name:</`label` >
  <input type="text" id="name" name="name">
</form>
```