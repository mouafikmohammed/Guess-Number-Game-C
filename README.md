# Guess Number Game C
Let's look at the guessing game as an example to use the Divide and Conquer Algorithm by halfing our possible number of guesses. To play the guessing, a person (player A) will choose a random number from n to m, another person (player B) will have to guess player A's number in "x" turns. Player A will assist player B by telling player B if the number they guessed is higher than or lower than player A's randomly chosen number. The Divide and Conquer Algorithm will tell you if it is possible to guess player A's number in the given amount of turns x, and will tell the maximum amount of tries or guesses you will need in order to guess there number correctly.
## Algorithms:
Here is the actual Steps (Algorithm) we just used:


    1.	Add the Highest Range + Lowest range - 1 = Possible Guesses.
    
    2.	Divide Possible Guesses by 2 Round Up (your guess), ask is this your number?
    
    3.	If your guess is to low:
      o	the Lowest Range = your guess +1
      
    4.	If your guess is to high:
      o	the Highest Range = your guess - 1
      
    5.	If your guess isn't to low or to high:
      o	You are done don't go to next step.
      
    6.	Repeat


## Experiment results:

<img src="image/.jpg" width=600/>

## Conclusion:
Okay, so where did we get the guessing numbers 50, 75 and 88? They came from adding the lowest range "1" and the highest range "100" minus "1", which equals 100 (the total possible numbers you can guess), and then dividing by 2 to get 50. The player then says if our guess is low or high either way, we now get rid of 50 possible numbers, in this case the number is higher, this means our guess was too low. So, the new lowest range is 51 and the highest range is still 100 so (100 +51-1) /2 = 75, so our next guess is 75. So now we got rid of another half of the range, in total we have gotten rid of 3/4 of the numbers. This leaves us with 1/4 of 100 numbers left, which is 25 possible numbers, the numbers are 76 to 100. Now, to get the third number 87. First Player A will tell us if the number 75 is too high or too low, in this case it's too low, so our lowest possible number is 76 and the highest possible number is still 100, so add 100 + 76 - 1 = 175 and then divide it by 2, round up (175/2 = 87.5) = 88. The reason why we round is because we only deal in integers or whole numbers. Our guess 88 is the correct number!
