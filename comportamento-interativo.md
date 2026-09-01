# Comportamento esperado na tela - Raiz & Cia

Este documento descreve como a página deve reagir à interação: o que muda
ao passar o mouse, clicar, navegar pelo teclado ou reduzir a largura da
tela. Tudo isso é resolvido só com HTML e CSS, sem nenhum JavaScript.

## 1. Rolagem da página

- O topo acompanha a rolagem: mesmo descendo a página, ele continua visível,
  fixo na parte de cima da tela, sempre por cima do restante do conteúdo.
- Ao clicar em um link que aponta para um ponto da própria página, a
  rolagem até lá é suave, não instantânea.

## 2. Links

- Fora do menu do topo, os links de texto aparecem sublinhados por padrão
  e mudam para um tom de verde mais vivo ao passar o mouse.
- Os links do menu do topo são a exceção: ficam na cor do texto comum, sem
  sublinhado, e só ganham a cor verde ao passar o mouse por cima.

## 3. Botões

- **Botão principal**: escurece ao passar o mouse; escurece ainda mais no
  instante do clique.
- **Botão secundário**: ganha um fundo verde bem claro ao passar o mouse.

## 4. Campos de formulário

- Ao clicar ou tabular até um campo de texto, lista suspensa ou área de
  texto, a borda do campo muda para verde, indicando que ele está ativo.
- Grupos de escolha única e caixas de marcação usam o verde do projeto
  quando marcados.
- Clicar no texto na label de um campo também marca ou dá foco ao campo
  correspondente, não só clicar exatamente em cima do campo.

## 5. Lista de kits e tabela

- Ao passar o mouse sobre uma linha da tabela, ela recebe um fundo verde
  claro, destacando qual linha está sendo observada.
- Os cartões de kit não têm nenhuma interação

## 6. Comportamento ao redimensionar a tela

- **Largura ampla (computador)**: a área de abertura mostra texto e foto
  lado a lado; os kits aparecem em duas colunas; o formulário também se
  organiza em duas colunas, com os campos que precisam de mais espaço
  ocupando a linha inteira.
- **Largura estreita (celular)**: kits e formulário passam para uma única
  coluna. A tabela deixa de espremer as colunas e passa a rolar de lado
  dentro da própria caixa, sem afetar o restante da página.
