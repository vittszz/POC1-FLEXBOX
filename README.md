# POC1-FLEXBOX
Descrição
Este projeto é uma prova de conceito (PoC) simples que demonstra o uso do Flexbox no CSS para criar um layout básico e responsivo. O layout contém três itens distribuídos horizontalmente dentro de um contêiner flexível. A PoC foi projetada para mostrar como o Flexbox facilita o alinhamento e a distribuição de elementos em um layout.

Estrutura do Projeto
O projeto é composto por dois arquivos principais:
index.html: Contém a estrutura HTML básica do projeto.
styles.css: Contém o código CSS responsável pelo layout e pelo design do projeto.

Funcionamento do Código
index.html
Este arquivo define a estrutura básica da página. Ele inclui um contêiner (div) com a classe container, que abriga três itens (divs) individuais com a classe item. Cada item contém texto simples, que é centralizado no layout usando Flexbox.

styles.css
O arquivo CSS define o estilo do layout usando Flexbox:

.container: Esta classe aplica o modelo Flexbox ao contêiner principal. Os itens dentro deste contêiner são alinhados horizontalmente (flex-direction: row), com espaçamento igual entre eles (justify-content: space-around), e são centralizados verticalmente (align-items: center).

.item: Cada item é estilizado com um fundo azul, texto branco, padding para espaçamento interno, e bordas arredondadas. Esses itens se ajustam automaticamente ao tamanho do contêiner e ficam centralizados de forma responsiva.

O que esperar ao abrir o codigo?
Ao abrir o arquivo index.html, você verá três blocos de itens dispostos horizontalmente, com espaço igual entre eles e centralizados na tela. O layout é responsivo e se adapta a diferentes tamanhos de janela, mantendo os itens centralizados e distribuídos uniformemente.
