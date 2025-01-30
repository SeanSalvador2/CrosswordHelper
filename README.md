### Project Introduction
- **Goal**: The goal of this project is to create a crossword helper that provides the user additional hints/clues to make solving crosswords more enjoyable. For now, the crossword helper assumes that you have access to the correct answers, but the end product would not require this. Moreover, a separate computer vision piece is being developed so a user can just take a picture of the entire crossword and request help where needed. For now, the crossword will operate on a clue/answer pair as being the input. As far as hint generation goes, the project is heading in a few different directions with varying levels of complexity, which include but are not limited to:
  1. Provide synonyms/related words/antonyms to the answer --> use embeddings/thesaurus
  2. Provide answer classification so the user know what *kind* of word they should be thinking of --> classification problem, probably exists
  3. Provide clue classification so the user knows what *kind* of hint they are looking at --> classification problem
  4. Provide new additional hints so the user can look at an answer from a different perspective --> train a transformer?
- Data: The data used in this project consists of NYT crossword data from 1993-2021.
