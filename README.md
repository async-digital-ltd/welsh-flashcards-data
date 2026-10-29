# A free list of 1,000 common Welsh words

This is a list of the 1,000 most common Welsh nouns, verbs, adjectives and adverbs, in order of how often they are used, each with an English meaning, its word class and, for nouns, its gender. Beside it is a list of 25,909 mutated and inflected forms, so that a word like *mhlentyn* (as in *fy mhlentyn*, my child) leads back to *plentyn*.

It is the word list behind Cardiau Cymraeg, a Welsh flashcard app for iPhone, and it is published here so that anyone can use it, free, under an open licence.

The list has not yet been checked by a fluent Welsh speaker, so corrections are welcome (see below). The ranks have gaps, because some words in the frequency list, such as function words, were left out.

## For teachers and learners

- **Open `Deck.csv` in any spreadsheet**, such as Numbers, Excel or Google Sheets. The words are in order of frequency, so the first rows are the words you will meet most often.
- **Make your own materials**: vocabulary lists for a class, printed flashcards, quizzes, or a deck for a flashcard app that imports CSV files, such as Anki.
- **North and South Wales words** are marked: where the two regions use different words for the same thing, such as *nawr* and *rŵan* (now), each is labelled `south` or `north`.
- **Look up a mutated word** in `Forms.csv` to find the word it comes from.

The files are UTF-8, so letters such as ŵ and ŷ display correctly. If Excel shows them garbled, open the file with **Data > From Text/CSV** and choose UTF-8.

## The files

`Deck.csv` has one row per word:

| Column | Holds |
|---|---|
| `id` | a number that stays with the word when the list is updated, even if its rank or meaning changes |
| `rank` | the word's position in the frequency list it was taken from; lower is more common |
| `headword` | the Welsh word, in its dictionary form |
| `meaning` | its English meaning |
| `word_class` | `noun-m`, `noun-f` or `noun-mf` (a masculine, feminine, or either-gender noun), `noun-pl` (a plural noun), `verb`, `adj` (adjective) or `adv` (adverb) |
| `region` | `north` or `south` for a word used mainly in one part of Wales, and empty otherwise |
| `packs` | the word sets the word belongs to, separated by spaces; every word is in `core` |

`Forms.csv` has one row per form: `form`, a mutated or inflected form, and `headword`, the word in `Deck.csv` it belongs to.

## Licence

The word list is licensed under CC BY-SA 4.0. You may copy, share and adapt it for any purpose, including commercial use, as long as you give credit and share what you make from it under the same licence. [LICENCE.md](LICENCE.md) has the credits to give and a suggested credit line.

## Corrections

If you find a wrong meaning or a missing form, please open an issue. The files are generated, so a correction is made where the list is built and then published here, rather than by editing the files directly.
