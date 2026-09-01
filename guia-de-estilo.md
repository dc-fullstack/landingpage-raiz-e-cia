# Guia de estilo - Raiz & Cia

Referência visual do projeto: cores, tipografia, medidas e componentes.
Este guia descreve a aparência, não o código. Nenhum nome de variável, classe
ou atributo aparece aqui de propósito: quem for reconstruir a página decide
como nomear as coisas.

## 1. Cores

Seis cores no projeto inteiro.

| Cor | Valor | Onde aparece |
| --- | --- | --- |
| Branco | `#ffffff` | fundo das páginas, texto sobre as áreas verdes |
| Verde bem claro | `#eef5ee` | fundo de destaque: aparece ao passar o mouse sobre linhas da tabela e sobre o botão de contorno |
| Preto esverdeado | `#16231a` | cor de todo o texto corrido e dos links do menu |
| Verde | `#2f7d4f` | botão principal, contorno de foco pelo teclado, cor de marcação das opções (radio e caixa de seleção) |
| Verde escuro | `#23623e` | links de texto e o estado de destaque do botão principal |
| Verde translúcido | `rgba(22, 35, 26, 0.14)` | todas as bordas e linhas divisórias |

## 2. Tipografia

Duas famílias, ambas sem serifa: uma para títulos, com peso 600, e outra para
texto corrido, nos pesos 400 (normal) e 600 (destacado). Sem conexão à
internet, o navegador usa a fonte padrão do sistema no lugar delas, sem
quebrar o layout.

| Onde | Fonte | Computador | Celular |
| --- | --- | --- | --- |
| Título de abertura da página | títulos, 600 | 46px | 33px |
| Título de cada seção | títulos, 600 | 26px | 24px |
| Nome do kit | títulos, 600 | 19px | 18px |
| Preço | títulos, 600 | 16px | 16px |
| Texto de abertura | texto, 400 | 17px | 17px |
| Texto corrido | texto, 400 | 16px | 16px |
| Texto de apoio (legendas e notas) | texto, 400, opacidade 72% | 14px | 14px |
| Rótulo de campo de formulário | texto, 600 | 13px | 13px |
| Botão | texto, 600 | 15px | 16px |
| Cabeçalho de tabela | texto, 600, caixa alta, espaçamento entre letras | 12px | 11px |

## 3. Medidas, bordas e espaçamento

- Largura máxima do conteúdo no computador: `980px`, centralizado.
- No celular não há largura máxima: o conteúdo acompanha 100% da tela, com
  respiro apenas nas laterais.
- Respiro nas laterais: `28px` no computador, `20px` no celular.
- Cantos arredondados: `2px` em tudo (botões, campos, cartões, foto).
- Espessura das bordas: `1px` sempre.
- Espaço entre os cartões de kit: `20px` no computador, `14px` no celular.
- Espaço entre campos do formulário: `18px`.
- Distância entre seções: `72px` no computador, `44px` no celular.
- Largura de campos de formulário, imagem e cartões dentro do próprio
  container: `100%`, para acompanhar o espaço disponível em qualquer tela.

## 4. Botões e links

Dois tipos de botão:

- **Botão principal**: fundo verde, texto branco.
- **Botão secundário**: fundo transparente, texto na cor do texto comum.

Fora deles, links de texto simples na cor verde escura.

Os links do menu do topo são a exceção do projeto: ficam na cor do texto
comum e sem sublinhado, ganhando verde só ao passar o mouse.

## 5. Campos de formulário

- Campo de texto de uma linha.
- Lista suspensa.
- Grupo de escolha única (várias opções, uma marcável por vez).
- Caixa de marcação avulsa (sim ou não).
- Área de texto de várias linhas.

Todos os campos de texto e a área de texto têm a mesma altura de borda,
o mesmo raio de canto e o mesmo espaçamento interno. O texto de exemplo
dentro de um campo vazio aparece em um tom acinzentado, mais claro que o
texto digitado.

## 6. Cartão de kit e tabela

**Cartão de kit**: nome em destaque, uma linha de descrição e, no pé do
cartão, a informação de apoio de um lado e o preço do outro. 

**Tabela**: cabeçalho em caixa alta e tamanho reduzido, uma linha fina
separando cada linha de conteúdo, e as duas últimas colunas (valor e
situação) alinhadas à direita, destacando os dados de resumo de cada plano.
