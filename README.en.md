# Java Collections — Oral Exam Flashcards

[Português](README.md) · **English**

**Open the flashcards:** https://joaocalixto.github.io/java-collections-flashcards/

Study cards for the oral exam on Java Collections and data structures.
One side of each card has the question; the other side has the expected answer.

It is a single page (`index.html`). Nothing to install: open the link above, or open
the file in a browser, on a computer or a phone.

## Topics

| Topic | Cards |
| --- | --- |
| **Final Review** (mock exam covering every topic; shown as "Revisão Final" in Portuguese) | 100 |
| Arrays and Lists | 7 |
| Queue and Stack | 6 |
| HashMap and Hashing | 10 |
| Set implementations | 9 |
| Comparable and Comparator | 8 |
| PriorityQueue and Heap | 16 |
| Trees — Theory | 15 |
| Graphs — Theory | 42 |
| Graphs — MST (Prim and Kruskal) | 18 |

### Final Review

It is the first topic in the menu, and the page opens on it with the cards already
shuffled, like an exam. It has 100 cards:

- 35 Java Collections questions (concepts, "what does this print?" and "write the code");
- 45 new questions, 5 from each of the other 9 topics;
- 20 cards repeated from the other topics. They use the original card's text, so fixing
  the original also fixes the copy.

Each card shows which topic it comes from (for example "Oral question · Graphs").
The answers to the "what does this print?" questions were checked by running the code in Java.

## How to use

- **Tap or click the card** to see the answer. The card spins and shows the other side.
- **Needs review / Mastered**: mark how well you answered each card.
- **Filter**: show all cards, only the ones to review, the ones not yet assessed, or the mastered ones.
- **Shuffle**: changes the order of the cards in the topic.
- **Clear topic ratings**: removes the marks for that topic.

Keys on a computer: `Space` flips the card, `←` and `→` move between cards,
`1` marks "needs review" and `2` marks "mastered".

Progress is saved in your own browser. Someone who gets the file starts from scratch.

## Languages

Portuguese (Portugal), Portuguese (Brazil), English, Spanish, French, German,
Italian and Chinese. Choose it from the 🌐 menu at the top of the page.

The **Final Review** cards are in Portuguese only. In the other languages, the topic
name is translated and the cards stay in Portuguese.

## Phones

The page is adjusted for small screens: the topics sit in a strip you swipe sideways,
the buttons are large enough for a finger, and code inside the cards wraps to fit the screen.

## Editing the cards

The cards are at the start of the `<script>` in `index.html`, in the `decks` list.
Each topic has an `id`, a `name` and a `cards` list, where each card is
`['question', 'answer']`.

To show code in a box, put it between lines with three backticks:

````
'O que imprime?\n```\nSystem.out.println(1 + 1);\n```'
````

The translations of the original topics are in the lists `translationsEN`, `translationsES`,
`translationsFR`, `translationsDE`, `translationsIT` and `translationsZH`.
