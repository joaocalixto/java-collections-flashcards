# Java Collections — Flashcards da Prova Oral

Cartões de estudo para a prova oral de Java Collections e estruturas de dados.
De um lado do cartão fica a pergunta; do outro, a resposta esperada.

É uma página só (`index.html`). Não precisa instalar nada: basta abrir o arquivo
no navegador, no computador ou no celular.

## Tópicos

| Tópico | Cartões |
| --- | --- |
| **Revisão Final** (simulado com todos os tópicos) | 100 |
| Arrays e List | 7 |
| Queue e Stack | 6 |
| HashMap e Hashing | 10 |
| Set e implementações | 9 |
| Comparable e Comparator | 8 |
| PriorityQueue e Heap | 16 |
| Árvores — Teoria | 15 |
| Grafos — Teoria | 42 |
| Grafos — MST (Prim e Kruskal) | 18 |

### Revisão Final

É o primeiro tópico do menu, e a página já abre nele, com os cartões embaralhados,
como numa prova. Tem 100 cartões:

- 35 perguntas de Java Collections (conceitos, "o que imprime?" e "escreva o código");
- 45 perguntas novas, 5 de cada um dos outros 9 tópicos;
- 20 cartões repetidos dos outros tópicos. Eles usam o texto do cartão original,
  então corrigir o original também corrige a cópia.

Cada cartão mostra de que tópico é (por exemplo, "Pergunta oral · Grafos").
As respostas das perguntas de "o que imprime?" foram conferidas rodando o código em Java.

## Como usar

- **Toque ou clique no cartão** para ver a resposta. O cartão gira e mostra o outro lado.
- **Precisa de revisão / Dominado**: marque como foi cada resposta.
- **Filtro**: mostre todos os cartões, só os para rever, os não avaliados ou os dominados.
- **Baralhar**: muda a ordem dos cartões do tópico.
- **Limpar avaliações do tópico**: apaga as marcações daquele tópico.

Teclas no computador: `Espaço` vira o cartão, `←` e `→` passam os cartões,
`1` marca "precisa de revisão" e `2` marca "dominado".

O progresso fica guardado no próprio navegador. Quem recebe o arquivo começa do zero.

## Idiomas

Português (Portugal), Português (Brasil), English, Español, Français, Deutsch,
Italiano e 中文. A escolha fica no menu 🌐 no topo da página.

Os cartões da **Revisão Final** estão só em português. Nos outros idiomas, o nome do
tópico aparece traduzido e os cartões continuam em português.

## Celular

A página foi ajustada para telas pequenas: os tópicos ficam numa faixa que se arrasta
para o lado, os botões são grandes para o dedo, e o código dentro dos cartões quebra
a linha para caber na tela.

## Como editar os cartões

Os cartões ficam no começo do `<script>` do `index.html`, na lista `decks`.
Cada tópico tem um `id`, um `name` e a lista `cards`, em que cada cartão é
`['pergunta', 'resposta']`.

Para mostrar código num quadro, coloque-o entre linhas com três crases:

````
'O que imprime?\n```\nSystem.out.println(1 + 1);\n```'
````

As traduções dos tópicos antigos ficam nas listas `translationsEN`, `translationsES`,
`translationsFR`, `translationsDE`, `translationsIT` e `translationsZH`.
