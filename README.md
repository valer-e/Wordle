# Wordle
Solver for the recently famous word puzzle

Goes through all possible 5 letter word combinations, with a few cuts here and there to optimize like green letters, each of which
cut the time by 1/26

Known problems:
- Can only use one slot for each misplaced letter, for example if the letter p is yellow in both slot 2 and slot 4, you have to pick one
