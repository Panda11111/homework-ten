# homework-tenDebugging Coin Toss
The following program is meant to be a simple coin toss guessing game. The player gets two guesses (it’s an easy game). However, the program has several bugs in it. Run through the program a few times to find the bugs that keep the program from working correctly.
Importin  random
guess = ''
while guess not in ('heads', 'tails'):
    print('Guess the coin toss! Enter heads or tails:')
    guess = input()
toss = random.randint(0, 1) # 0 is tails, 1 is heads
if toss == guess:
    print('You got it!')
else:
    print('Nope! Guess again!')
    guesss = input()
    if toss == guess:
       print('You got it!')
    else:
        print('Nope. You are really bad at this game.')
Debugging:
	In line two the two parens need to be in parens
	The while in guess not the if function needs to be I in place
	In the parens of the parens the 
	In the sixth line the random and randint needs to be in front of the toss
	The first else statement should have no colon
	The guess input and the if toss should be changed and one of the statements should be where the other one was.
