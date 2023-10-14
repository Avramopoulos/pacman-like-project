Compilation is performed with:
```
g++ *.cpp -o a.out -lncurses
```
or for spefically compiling with c++ version 11:
```
g++ -std=c++11  *.cpp -o a.out -lncurses
```
and then to run the game give the map folder and the highscores file as arguments:
```
./a.out map1.txt scores.bin
```
Description:
The game has 2 difficulties easy and hard, in easy one enemy chases after the gem while in hard two enemies do.
Once you collect a gem your score increases by 10 and the map restarts placing the players once again in random positions while retaining the score, 
that design choice was made to add replaybality to the game. Once an AI player gets to the gem or they kill you the game ends. Once the game ends you 
are requested to type a name and if the score is high enough it will be placed in the top 5 highscores in the scoreboard option.

The player can move around the map using the arrow keys or stay idle by pressing the spacebar.

