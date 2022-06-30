# Greed
Have a crack at hunting for gems! Each gem gets you a point, find the same gem again and it will be 
worth an extra bonus point from the last time you found it! Be careful though, hit an O and you
will loose one of those precious points.

---
## Getting Started
Make sure you have Python 3.8.0 or newer installed and running on your machine. Open a terminal and browse to the project's root folder. Start the program by running the following command.
```
python3 greed 
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
The project files and folders are organized as follows:
```
root                    (project root folder)
+-- greed              (source code for game)
  +-- game              (specific classes)
    +-- casting
        +-- actor.py    (class: a visible moveable thing that participates in the game)
        +-- cast.py     (class: a collection of actors)
        +-- gem.py      (class: an indiviual gem or block on the screen)
        +-- player.py   (class: the person playing the game)
    +-- directing
        +-- director.py (class: directs gameplay and controls updates, inputs and outputs)
    +-- services
        +-- keyboard_service.py (class: controls input from the keyboard)
        +-- video_service.py    (class: outputs the current game state)
    +-- shared
        +-- color.py            (class: for comparing and converting a tuple into color info)
        +-- point.py            (class: used for x and y coordinates on screen)
  +-- __main__.py       (program entry point)
+-- README.md           (general info)
```

## Required Technologies
* Python 3.8.0

## Authors
* Chris Mills
* admin@themillsclan.com
