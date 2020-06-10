# Acessibilidade Aplicada: Salte Diretamente para o Conteúdo Usando o Elemento Principal

O HTML5 introduziu uma série de novos elementos que oferecem aos desenvolvedores mais opções e também incorporam recursos de acessibilidade. Essas marcas incluem `main`, `header`, `footer`, `nav`, `article`, e `section`, entre outros.

Por padrão, um navegador renderiza esses elementos de maneira semelhante à humilde div. No entanto, usá-los quando apropriado dá um significado adicional à sua marcação. Somente o nome da tag pode indicar o tipo de informação que ela contém, o que adiciona significado semântico a esse conteúdo. As tecnologias assistivas podem acessar essas informações para fornecer um melhor resumo da página ou opções de navegação para seus usuários.

O `main` elemento é usado para quebrar (você adivinhou) o conteúdo principal e deve haver apenas um por página. Ele serve para cercar as informações relacionadas ao tópico central da sua página. Não pretende incluir itens repetidos nas páginas, como links de navegação ou banners.

A `main` tag também possui um recurso de referência incorporado que a tecnologia assistida pode usar para navegar rapidamente para o conteúdo principal. Se você já viu um link "Ir para o conteúdo principal" na parte superior de uma página, o uso de uma tag principal fornece automaticamente aos dispositivos auxiliares essa funcionalidade.
