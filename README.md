# Ants_Vs_SomeBees
![alt text](https://github.com/zhiji95/Ants_Vs_SomeBees/edit/master/splash.png)
As the ant queen, you populate your colony with the bravest ants you can muster. Your ants must protect their queen from the evil bees that invade your territory. Irritate the bees enough by throwing leaves at them, and they will be vanquished. Fail to pester the airborne intruders adequately, and your queen will succumb to the bees' wrath. This game is inspired by PopCap Games' Plants Vs. Zombies.
 
 


To start a text-based game, run

```
python3 ants.py
```
To start a graphical game, run
```
python3 gui.py
```
To start an older version of the graphics, run
```
python3 ants_gui.py
```
![alt text](https://github.com/zhiji95/Ants_Vs_SomeBees/edit/master/new-ants-gui.png)

In the starter implementation, you have unlimited food and your ants only throw leaves at bees in their current Place. Try playing the game anyway! You'll need to place a lot of ThrowerAnts (the second type) in order to keep the bees from reaching your queen.

The game has several options that you will use throughout the project, which you can view with --help.
```
usage: ants.py [-h] [-d DIFFICULTY] [-w] [--food FOOD]

Play Ants vs. SomeBees

optional arguments:
  -h, --help     show this help message and exit
  -d DIFFICULTY  sets difficulty of game (easy/medium/hard/insane)
  -w, --water    loads a full layout with water
  --food FOOD    number of food to start with when testing
  ```
