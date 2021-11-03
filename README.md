# trex-dino-game-py3
Dino game bot using python3.x -- no AI

---

**Juptyper Lab**  
[Jupter Get Started](https://jupyter.readthedocs.io/en/latest/tryjupyter.html)

My Setup  
Windows 8.1 x64  
Python 3.7  
pip3  

`pip3 install jupyterlab`

---

Windows .bat for easy launching  

Add to Jupyter folder 
`start_jupyter.bat`
  
Then type `jupyter lab`

---

In your project folder add these folders

```
-> images
-------> boxes
-------> dino
```

---

Most of the code should be self explantory. Here are some the may need explaining

```
textScore -- Image capture box to read the speed up cyccles
textGameOver -- Turns off the bot if the game is over, otherwise the spacebar is continually pressed
dinoBox -- Image capture box around dino, it is move automatically to the right for obsticles
dinoTail -- Image capture box to check if the jump failed or not and reset to jump

xOffset -- Pre looking distance to right right checking for obsticles
xIncrement -- Adds more distance to right with ever 100 point speed up cycle
```



Second to last code area is for setting up image capture boxes. Make sure f_stopMe() is on if doing so.
```
#f_displayDino()
# f_checkScore(True)
# f_checkBox(True)
#f_checkGameOver(True)
# f_checkTail(True)
#
# f_stopMe()
```

The last box is the main running while loop.

First time do >> to run the all the code blocks

**Note** - My cpu may faster or slower than yours so the xOffset and xIncrement may need tweaking.
I tried to have the dino land just after the obsticles to begin with


Lastly this if for fun only so let's not take away human high score slots.

---
2k Score -- Perhaps could be better by adding crouch
  
![Screen Capture](https://a.jcbellc.com/images/github/dino_screen_capture.png)









