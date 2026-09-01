# Raiz &amp; Cia

Projeto individual para quem ta iniciando em HTML e CSS. Você vai construir, do zero, o site de
uma assinatura de sementes a partir de um guia de estilo, duas imagens de
referência e uma foto.

## Antes de começar

Faça o fork para a sua conta, clone o seu fork e so então começe a desenvolver.

## O briefing

A Raiz &amp; Cia é uma pequena loja que vende kits de sementes por
assinatura: toda caixa vem com sementes selecionadas para a estação, terra,
um vaso de fibra e um guia de plantio. Hoje quem quer assinar manda mensagem
pelo Instagram, e a dona da loja está perdendo pedido porque não dá conta de
responder todo mundo a tempo.

Ela contratou você para construir a primeira versão do site. Um designer já
entregou a identidade visual e as telas de referência (desktop.png e mobile.png); a Raiz &amp; Cia só
precisa que alguém transforme isso em uma página de verdade, que funcione
tanto no computador de quem está no escritório quanto no celular de quem
está com a mão suja de terra no meio do plantio. O pedido dela foi direto:
"quero conseguir mandar o link e a pessoa já conseguir escolher o kit e
assinar, sem precisar me chamar no direct".

## O que você recebe

```
raiz-e-cia/
├── img/
│   ├── mudas.png ................... foto de abertura da página
├── referencia-desktop.png ..................... como o resultado final deve parecer em tela larga
├── referencia-mobile.png ...................... como o resultado final deve parecer em tela estreita
├── guia-de-estilo.md ............... cores, tipografia, medidas e componentes
├── guia-de-estilo.png ............... Referência visual do guia de estilo
├── comportamento-interativo.md ..... como a página deve reagir a clique, toque, foco e rolagem
└── README.md ....................... este arquivo
```

## O que você entrega

Um `index.html` e um CSS (ex: `style.css`), organizados como preferir, 
que juntos reproduzam as duas imagens de
referência e sigam o guia de estilo e o documento de comportamento.

## O que você vai desenvolver

Ao concluir este projeto você terá praticado:

**HTML**
- Estrutura semântica (`header`, `nav`, `main`, `section`, `footer`, hierarquia de `h1` a `h3`)
- Listas (`ul`/`li`) e tabelas (`table`, `thead`, `tbody`, `th`)
- Formulários nativos: `label` ligado por `for`/`id`, `input` de vários
  tipos, `select`, `textarea`, `radio`, `checkbox`
- Atributos de acessibilidade básicos, como `alt` descritivo

**CSS**
- Variáveis (custom properties) para cor, fonte e medida
- Reset e `box-sizing: border-box`
- Flexbox: alinhamento, `gap`, quebra de linha
- Implentar `position`, `z-index`, `object-fit` e `object-position` para imagens
- Pseudo-classes de interação (`:hover`, `:focus-visible`) e
  pseudo-elementos como `::selection`
- Tabela com rolagem horizontal em tela estreita

**Conceitos gerais**
- Ler uma especificação visual (guia de estilo, imagens de referência) e
  traduzir isso em código, decidindo você mesmo nomes de classe, variável e
  organização de arquivo
- Ler um pedido de um cliente (o briefing acima) e identificar o que ele
  precisa de fato, não só o que ele descreveu com palavras técnicas
