# Acessibilidade aplicada: saber quando o texto alternativo deve ser deixado em branco

No último desafio, você aprendeu que incluir um `alt` atributo ao usar `img` tags é obrigatório. No entanto, às vezes as imagens são agrupadas com uma legenda que já as descreve ou são usadas apenas para decoração. Nesses casos, o `alt` texto pode parecer redundante ou desnecessário.

Nas situações em que uma imagem já é explicada com conteúdo de texto ou não adiciona significado a uma página, ela `img` ainda precisa de um `alt` atributo, mas pode ser configurada para uma sequência vazia. Aqui está um exemplo:

´´´
<img src="visualDecoration.jpeg" alt="">
´´´

As imagens de plano de fundo geralmente também se enquadram no rótulo 'decorativo'. No entanto, eles geralmente são aplicados com regras CSS e, portanto, não fazem parte do processo dos leitores de tela de marcação.

Nota: Para imagens com legenda, você ainda pode querer incluir `alt` texto, pois ajuda os mecanismos de pesquisa a catalogar o conteúdo da imagem.
