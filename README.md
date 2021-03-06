## Game Of Life

The Game of Life is a simple cellular automaton simulation that was devised by mathematician Jhon Horton Conway in 1970. 
Conway recently died due to Covid-19, so I decided to implement his game with pygame. Conway was an awesome mathematician, appart from his extensive contributions to game theory he has appeared in many videos of [numberphile](https://www.youtube.com/channel/UCoxcjq-8xIDTYp3uz647V5A) which is a great youtube channel I follow.

The Game of life has really simple rules, each and every cell of the grid is oblidged to them:

1: ***Any live cell with two or three live neighbours survives.***

2: ***Any dead cell with three live neighbours becomes a live cell.***

3: ***All other live cells die in the next generation. Similarly, all other dead cells stay dead.***

Feel free to play around with these "core rules", there are many insteresting variations. 
     
The code is partly inspired on a youtube video by [Dot Csv](https://www.youtube.com/channel/UCy5znSnfMsDwaLlROnZ7Qbg).

### Set up

In order to execute this file you will need python, which will likely come pre-installed in most linux distributions.
You will also need Pygame which doesn't come pre-installed.
To install Pygame simple run the following comand on your terminal:

```
python3 -m pip install -U pygame --user
```

The --user flag indicates python to install Pygame into the home directory rather than globaly.


Once you've installed Pygame simply execute it as a python file:

```
python GameOfLife.py
```

The game interface should appear now.
Enjoy!


### Game instructions

You can draw blocs on the grid simply by leftclicking on them. In order to draw a set of them you have to press any key on the keybord and the game will stop, then you will be able to draw as many blocs as you want. To resume the game just press again any key.

There are some insteresting cell configurations to play with as shown below:

![Alt Text](https://camo.githubusercontent.com/a710386de69bcb8577875246196c7fb07144ff0c/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f3456565a547654717a5252304255774e49482f67697068792e676966)

Source Wikipedia
