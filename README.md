*Bookshelf — Catálogo de Livros*

*Descrição do Projeto:*
O Bookshelf é um site de catálogo de livros desenvolvido com HTML5 e CSS3, cujo objetivo é apresentar diferentes obras literárias de forma visual, organizada e responsiva.
O projeto simula uma estante virtual, permitindo a navegação por gêneros, visualização das capas e acesso a links externos dos livros.
O foco principal do projeto é a aplicação de Flexbox e breakpoints, garantindo um layout adaptável a diferentes tamanhos de tela.

*Uso do Flexbox:*
O Flexbox foi utilizado para estruturar o layout e alinhar os elementos de forma responsiva. Ele está presente nas quatro partes principais do site:

- Cabeçalho (.cabecalho)
Utilizado para alinhar o título do site
Centraliza os elementos verticalmente
Permite reorganização do layout em telas menores

- Menu de navegação (.menu)
Distribui os links horizontalmente em telas grandes
Ajusta os links para disposição vertical em telas menores
Facilita a navegação em dispositivos móveis

- Catálogo de livros (.catalogo e .livros)
Organiza os cards de livros em formato de grade
Usa flex-wrap para quebra automática de linha
Centraliza os elementos e mantém espaçamento consistente

- Seção Hero (.hero-content, .hero-stats, .hero-buttons)
Organiza textos, botões e estatísticas
Controla alinhamento e espaçamento interno
Garante melhor adaptação do conteúdo em diferentes resoluções

*Breakpoints Utilizados*
O projeto utiliza breakpoints em CSS para garantir responsividade. Eles atuam nas seguintes seções:

PoolSeção Hero
Os breakpoints ajustam:
- .hero-container → muda de uma coluna para duas colunas
- .hero-title → aumenta o tamanho da fonte em telas maiores
- .hero-description → melhora a legibilidade do texto
- .hero-buttons → reorganiza os botões horizontalmente

*Breakpoints usados:*
@media (min-width: 768px)
@media (min-width: 1024px)

*Cabeçalho*
.cabecalho
Em telas menores, o layout passa de linha para coluna, evitando sobreposição de elementos
Breakpoint usado:
@media (max-width: 768px)

*Menu*
.menu
Os links deixam de ficar horizontais e passam a ficar empilhados verticalmente em telas menores
Breakpoint usado:
@media (max-width: 768px)

*Rodapé (Footer)*
footer
O layout é reorganizado para melhorar a visualização e acessibilidade em dispositivos móveis
Breakpoint usado:
@media (max-width: 768px)
