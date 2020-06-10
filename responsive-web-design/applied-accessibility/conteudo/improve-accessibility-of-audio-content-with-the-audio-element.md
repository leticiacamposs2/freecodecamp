# Acessibilidade Aplicada: Melhore a Acessibilidade do Conteúdo de Áudio com o Elemento de Áudio

O `audio` elemento HTML5 fornece significado semântico ao agrupar o conteúdo do fluxo de som ou áudio na sua marcação. O conteúdo de áudio também precisa de uma alternativa em texto para ser acessível a pessoas surdas ou com deficiência auditiva. Isso pode ser feito com texto próximo na página ou um link para uma transcrição.

A `audio` tag suporta o `controls` atributo Isso mostra a reprodução, pausa e outros controles padrão do navegador e suporta a funcionalidade do teclado. Este é um atributo booleano, o que significa que não precisa de um valor; sua presença na tag ativa a configuração.

Aqui está um exemplo:

```
<audio id="meowClip" controls>
  <source src="audio/meow.mp3" type="audio/mpeg" />
  <source src="audio/meow.ogg" type="audio/ogg" />
</audio>
```

Nota: O conteúdo multimídia geralmente possui componentes visuais e auditivos. Ele precisa de legendas sincronizadas e uma transcrição para que usuários com deficiência visual e / ou auditiva possam acessá-lo. Geralmente, um desenvolvedor da web não é responsável por criar as legendas ou a transcrição, mas precisa saber para incluí-las.

