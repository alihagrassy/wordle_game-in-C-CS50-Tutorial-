# wordle_game-in-C-CS50-Tutorial-
i'm  trying to create a wordle50 game which is basically  a code  script for the game without a gui in C and it basically if you are not familiar with the game:
# it's a guess game the machine takes a random  word from n.txt  which each (n) stands for number of character in words is named with it's amount of characters  and tells you 3 things :
# Green means right charactrer in rightposition .
# Yellow mean right character but wrong position .
# RED means wrong character.
as the game is built for you have an extra guess for each  type file for example if your fills are 4-character length you will have  5 guesses and so on .
to be able to combile it in your mobile use :
# cc wordle50.c -o wordle50 cs50.c
and to run it :
# make sure that you are in the right path of the file and it's better to download WSL on your windows to be able to run smoothly without any errors.
# ./wordle50 n
n is number from 5-8  that refereces to the name of the file which is the number of characters in word.

