# Acessibilidade aplicada: use títulos para mostrar relações hierárquicas de conteúdo

Os títulos ( `h1` por meio de `h6` elementos) são tags de trabalho que ajudam a fornecer estrutura e rotulagem ao seu conteúdo. Os leitores de tela podem ser configurados para ler apenas os cabeçalhos de uma página, para que o usuário obtenha um resumo. Isso significa que é importante que as tags de cabeçalho na sua marcação tenham significado semântico e se relacionem entre si, não sendo escolhidas apenas pelos valores de tamanho.

O significado semântico significa que a tag usada no conteúdo indica o tipo de informação que ele contém.

Se você estivesse escrevendo um artigo com uma introdução, um corpo e uma conclusão, não faria muito sentido colocar a conclusão como uma subseção do corpo em seu esboço. Deve ser sua própria seção. Da mesma forma, as tags de cabeçalho em uma página da web precisam estar em ordem e indicar os relacionamentos hierárquicos do seu conteúdo.

Os títulos com classificação igual (ou superior) iniciam novas seções implícitas, os títulos com classificação inferior iniciam as subseções da seção anterior.

Como exemplo, uma página com um `h2` elemento seguido por várias subseções rotuladas com `h4` tags confundiria um usuário de leitor de tela. Com seis opções, é tentador usar uma tag porque fica melhor em um navegador, mas você pode usar CSS para editar o tamanho relativo.

Um ponto final, cada página deve sempre ter um (e apenas um) `h1` elemento, que é o assunto principal do seu conteúdo. Este e os outros títulos são usados ​​em parte pelos mecanismos de pesquisa para entender o tópico da página.
