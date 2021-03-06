# Keys Per Second ![](https://img.shields.io/github/release/RoanH/KeysPerSecond.svg) ![](https://img.shields.io/github/downloads/RoanH/KeysPerSecond/total.svg)

KeysPerSecond is a program that counts how many times certain keys are pressed. And shows what the average, maximum and current number of keys pressed per second is. The program can also show a nice graph of the key presses over time.    
Almost all aspects of the program are also fully customizable.   

[Jump directly to downloads](#downloads)

# Introduction
Originally I wanted to know how many keys I pressed per second in osu! And I had already seen programs like this on live streams.
I could however not find a program that worked well on my computer so I decided to write one myself.

The program when active looks like this:    
![Interface](http://i.imgur.com/9cCzB0Q.png)  ![Interface](http://i.imgur.com/bLQXABw.png)    
There is also a right click menu to configure all the settings:    
![Menu](https://i.imgur.com/lltS2NK.png)    

For each configured key the program will show how many times it was pressed. By default it will also show the maximum, average and current number of keys pressed per second.
When enabled it can also show a graph of the number of keys pressed per second over time and the total number of keys pressed.

Everything shown in the pictures above can be toggled on or off and all the panels can be arranged in a lot of different ways.      
![Config](https://i.imgur.com/QcEm7Og.png)  ![Key config](https://i.imgur.com/Zjuc7Na.png)    
![Layout](https://i.imgur.com/w61exGO.png)    

There are also some commands that can be sent to the program:    
**Ctrl + P**: Causes the program to reset the average and maximum value.    
**Ctrl + U**: Terminates the program.    
**Ctrl + I**: Causes the program to reset the key press statistics.    
**Ctrl + Y**: Shows / hides the GUI.    
**Ctrl + T**: Pauses / resumes the counter.    
**Ctrl + R**: Reloads the configuration file.

You can also move the program using the arrow keys or snap it to the edges of your screen.

Well I hope some of you find this program useful and/or will use it for your streams (I would love to see that happen  :) ).
And if you find any bugs feel free to report them. If you have any features you'd like to see added please tell me as well!

## Notes
- The horizontal line in the graph represents the average number of keys pressed per second.
- You can add any key, and any number of keys to the program.
- You can also track mouse buttons with this program.
- The overlay option is far form perfect it just ask the OS to place the program on top. It'll not overlay most full screen games.
- To change a GUI colour in the colours menu, click on the current colour
- An opacity of 100% means completely opaque and an opacity of 0% means completely transparent.
- The snap to screen edge function works on multi-monitor setups.
- You can move the window with the arrow keys at 3 different speeds 1, 2 & 3 pixels at a time (2=Ctrl, 3=Shift).
- You can pass the path to the config file to load via the command line or a shortcut so you can skip the configuration step. Setting the program as the default program to open the configuration file with may work as well as long as you don't move the executable afterwards.
- When resetting something it will also be printed to the console if this program is running using cmd/shell.    
- [For some people](https://youtu.be/E_WHAaI_-Zw) running the program in Windows 98 / ME compatibility mode makes it so it can overlay full screen osu! so if you're lucky this might work.

## Todo list / working on
It's kinda empty here right now :c, so please suggest things c:    

## Downloads
_Requires Java 8 or higher_    
_Tested operating systems: Mac 10.11.6, Ubuntu Linux 16.04 LTS, Windows 7 & 8 & 10_    
- [Windows executable](https://github.com/RoanH/KeysPerSecond/releases/download/v8.3/KeysPerSecond-v8.3.exe)    
- [Runnable Java Archive](https://github.com/RoanH/KeysPerSecond/releases/download/v8.3/KeysPerSecond-v8.3.jar)

All releases: [releases](https://github.com/RoanH/KeysPerSecond/releases)    
GitHub repository: [here](https://github.com/RoanH/KeysPerSecond)    
Original osu! forum post: [post](https://osu.ppy.sh/community/forums/topics/552405)    

## Examples
The following two examples show the layout while it is being edited. All the panels have to line up with the grid, but the size of the grid cells can be changed.    
![](https://i.imgur.com/kfXaqwX.png)    
![](https://i.imgur.com/DP5MNVq.png)    
Next are two other examples of possible layouts.    
![](https://i.imgur.com/ImE4zTU.png)    
![](https://i.imgur.com/fBgohIA.png)    
Last are some very simple layouts to highlight the title-value display options.    
![Modes](https://i.imgur.com/0769n9E.png)      

## History
Project development started: 23 January 2017
