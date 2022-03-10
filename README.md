# Wordle-Solver
A tool that helps people who struggle with vocabulary enjoy the famous game of WORDLE.
# How does Wordle-Solver work?
Based on probability, Wordle-Solver helps WORDLE players find the best words for the next try. Wordle-Solver uses every bit of information gained from WORDLE’s responses to build the search criteria. The responses from the tries will help Wordle-Solver narrow down to a single, if not a few, possible English word(s).

Usually, in the first two or three tries, the list of possible words may still be quite long. Wordle-Solver works out the probabilities of letters with unknown inclusion/exclusion status and suggests words with letters of higher frequencies. It does not matter whether or not these high-frequency letters end up in the hidden word. WORDLE’s responses to these high-frequency letters will help Wordle-Solver shrink the search space efficiently.
# Usage of Wordle Solver
On running the program, a word will be suggested by it. Enter the same word in the wordle game as your first guess.
Enter WORDLE’s response into Wordle-Solver in the form of a five letter long string.

Use x for ⬜ indicating a letter not in the hidden word in any spot.

Use y for 🟨 indicating a letter in the hidden word but in the wrong spot.

Use g for 🟩 indicating a letter in the hidden word and in the correct spot.

Pick a suggested word shown by Wordle-Solver. Enter it into WORDLE. Repeat this step until Wordle-Solver finds the hidden word for you.
# Credits
The “answer/possible” word list is derived from MIT’s 2000-word list. The “accepted/guess" word lists are derived from the alpha variant of dwyl’s “List of English Words”.
