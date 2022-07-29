# Guess-Number-Game-C
Let's look at the guessing game as an example to use the Divide and Conquer Algorithm by halfing our possible number of guesses. To play the guessing, a person (player A) will choose a random number from n to m, another person (player B) will have to guess player A's number in "x" turns. Player A will assist player B by telling player B if the number they guessed is higher than or lower than player A's randomly chosen number. The Divide and Conquer Algorithm will tell you if it is possible to guess player A's number in the given amount of turns x, and will tell the maximum amount of tries or guesses you will need in order to guess there number correctly.
## Algorithms:
Here is the actual Steps (Algorithm) we just used:
    1.	Add the Highest Range + Lowest range - 1 = Possible Guesses
    2.	Divide Possible Guesses by 2 Round Up (your guess), ask is this your
    number?
    3.	If your guess is to low:
      o	the Lowest Range = your guess +1
    4.	If your guess is to high:
      o	the Highest Range = your guess - 1
    5.	If your guess isn't to low or to high:
      o	You are done don't go to next step.
    6.	Repeat
