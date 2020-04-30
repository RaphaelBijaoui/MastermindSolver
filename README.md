# MastermindSolver
Final coursework for EE1-07 Software Engineering 1, taught by Dr. Max Cattafi.

This assignment deals with a game known as Mastermind or Master Mind, as can be seen in 
<a href="http://www.cs.uni.edu/~wallingf/teaching/cs3530/resources/knuth-mastermind.pdf">this paper</a> from Donald Knuth.
In the paper the code has length 4 and each element can take 6 possible values. We are going to consider a general case in which the length and the number of symbols can have different values (of course in any case greater than 0).

## Background
Mastermind is a game founded in 1970 by a Telecommunications expert named Mordecai Meirowitz. Always enthralled by the opportunity to solve codes, he wanted to bring this fascination to the greater public in the form of a board game. What started as a code breaking game soon manifested into a topic that captivated everyone from children to professors into the art of strategic guesswork. 

The generic game plays as follows: a player sets a code of length L, and the opponent then has a number of attempts to solve the code using N colours. During the game, feedback in the form of black pegs for a correct hit (i.e. a correct colour in the correct position) is updated with each attempt, and a white peg for a correct colour (in the wrong position).

<p align="center">
  <img src="https://github.com/RaphaelBijaoui/images/blob/master/MMlogo.png">
</p>
<p align="center">
  <i>The Mastermind Board Game</i>
</p>

This project focuses on a simulation of this game in C++, playable for all values of  L and N up to 15, where a dynamic algorithm was created to solve both the code in under 10 seconds, and in a minimum amount of attempts.

## Set-up
Clone repository
```
git clone https://github.com/RaphaelBijaoui/MastermindSolver.git
```
Compile C++ code
```
g++ -std=c++11 mastermindsolver.cpp -o mastermindsolver
```
Run program
```
./mastermindsolver
```

## Coursework guidelines
- All the variables to be declared in the scope of a function (either the main or some other one). In other words, global variables are not allowed.
- All the loops to be controlled/terminated either by the loop condition or by return. Statements such as break, continue, goto are not allowed anywhere in the program.
- No switch statement.
- Functions should not return vectors provided as output. In other words, vectors must be provided in output using output parameters (i.e. passing by reference).
- Only headers from the standard library are allowed, however the use of the header <algorithm> is not allowed. If you are not sure whether a header is part of the standard library or not, try compiling on the Linux install on the lab computers, if it works it's part of the standard library.
- Do not use the using namespace directive.
- Make use of structs format
 
## Final comments
Many thanks to our lecturer, Dr. Cattafi, @JaafarRammal for the fun all-nighter... and the Imperial library for being open 24/7 !! 😅

----------------------------------------------------------------------------------------------------------------------------

If anything, the door is always open. Contact details in bio.

Enjoy!
