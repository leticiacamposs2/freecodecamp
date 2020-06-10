# Acessibilidade aplicada: melhore a acessibilidade do gráfico com o elemento da figura

O HTML5 introduziu o `figure` elemento, juntamente com o relacionado `figcaption` . Usados ​​juntos, esses itens agrupam uma representação visual (como uma imagem, diagrama ou gráfico) junto com sua legenda. Isso fornece um aumento de acessibilidade duplo, agrupando semanticamente o conteúdo relacionado e fornecendo uma alternativa em texto que explica o `figure` .

Para visualizações de dados como gráficos, a legenda pode ser usada para anotar brevemente as tendências ou conclusões para usuários com deficiência visual. Outro desafio aborda como mover uma versão da tabela dos dados do gráfico para fora da tela (usando CSS) para usuários de leitores de tela.

Aqui está um exemplo - observe que ele `figcaption` vai dentro das `figure` tags e pode ser combinado com outros elementos:

```
<figure>
  <img src="roundhouseDestruction.jpeg" alt="Photo of Camper Cat executing a roundhouse kick">
  <br>
  <figcaption>
    Master Camper Cat demonstrates proper form of a roundhouse kick.
  </figcaption>
</figure>
```