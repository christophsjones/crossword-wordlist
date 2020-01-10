# crossword-wordlist
Scored wordlist for use with construction software such as Crossword Compiler or Crossfire

## How to use this list
Import the list into Crossword Compiler by going to "Words", then "Word List Manager", then "Convert", then "Plain text file...".

Now if you go to "Words" then "AutoFill" the grid, you can select this list.

Roughly the scoring is:
- 50 = common word or phrase that you wouldn't hesitate to put in the grid 
- 25 = an acceptable word
- 2 = lowest score in the list
- 1 = not yet present, but in the future I may put in extra semi-words with this score to ensure a fill is always found

## How was this list constructed?
The words in the list are winnowed down from many sources: NYT, WSJ, WaPo, UKACD, [Peter Broda's list](https://peterbroda.me/crosswords/wordlist/), [Peter Norvig's frequency counts](https://norvig.com/ngrams/), a few smaller newspapers' puzzles, ~5k handpicked words. A score is computed for each word based on the number of occurrences in each of these.

The guiding philosophy of this list was to try not to include too many non-words. As a consequence, the list isn't extremely comprehensive and it's quite possible it won't be able to fill a trickier grid. [Peter Broda's list](https://peterbroda.me/crosswords/wordlist/), on the other hand, is extremely comprehensive although the scorings are all over the place.

## I want to contribute!
Make a pull request with some of your favorite modern real-world phrases (especially if they are 15 letters long)! Or fix some of the scorings of this list!
