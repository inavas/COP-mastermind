# COP-mastermind

Mastermind or Master Mind is a code-breaking game for two players. The modern game with pegs was invented in 1970 by Mordecai Meirowitz, an Israeli postmaster and telecommunications expert. It resembles an earlier pencil and paper game called Bulls and Cows that may date back a century or more. (Source Wikipedia)

## Rules
1. The first player will select 4 letters from A to F. Letters can not be duplicated but there will always be exactly 4.
2. The second player has to guess the code.
2. The Mastermind will return the following feedback:
- Number of pins that are both the right letter and position
- Number of pins that are correct in letter but in the wrong position
      
## Example 1
Secret ABCD and guess ABCD must be evaluated to: rightPosition = 4, wrongPosition = 0. All letters are guessed correctly in respect to their positions.

## Example 2
Secret ABCD and guess CDBA must be evaluated to: rightPosition = 0, wrongPosition = 4. All letters are guessed correctly, but none has the right position.

## Example 3
Secret ABCD and guess ABDC must be evaluated to: rightPosition = 2, wrongPosition = 2. A and B letters and their positions are guessed correctly. C and D letters are guessed correctly, but their positions are wrong.
