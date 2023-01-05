---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

- Project by <a href="https://picoluetjens.github.io/">Pico Lütjens</a>
- Source Code is available <a href="https://github.com/PicoLuetjens/Pinball-Alternate">here</a>

![image](img/pinball1.PNG)

# General

Pinball-Alternate is a 3rd Semester-Project that i did for a course. It is using the Box2D-Engine for Game Physics - this Engine is used in many popular games such as for example "Angry Birds". The goal of the game is to challenge yourself with a self designed playground. You can also import one of the Presets or create and safe your own Preset to your disk. The game can be played either in 720p or in 1080p by changing the size()-function in the setup.pde source code file. However the default is 720p and it is also recommended to play in 720p! Reach a high score and put yourself on top of the scoreboard!

# Installation

The Project comes in Processing source code. A Java Installer with a JRE bundled is not available at the moment. What that means is that for the code to run you need to have Processing installed, as well as the Libraries the game relies on. Once you installed Processing you can install all the Libraries via the Processing Library Manager. Clone the Repository and run the code with Processing to play the game.

> Warning: The Game does not always run as smooth as it should. Especially on lower performance computers that can cause bugs with the paddles. This is a known issue however i did not have the time to look into it yet. Also there is no ball back mechanic right now so if something is stuck you will need to restart from the menu.

![image](img/pinball2.PNG)

# Edit Mode
Although the game is really easy to understand and explains everything more or less by itself, here is a short summary of the Edit Mode. This is where you create your Playground. Either load a Preset or start creating your own. Once you start to draw a new shape you have to finish it before you can remove it. Even if you remove all shape points the shape drawing is still active and you have to finish drawing a shape to get out of this state.<br>
Shapes does not have to be closed. In fact for some Boundary-Types it makes more sense to leave the shape open.
There are four possible Boundary-Types:
- Bumper - Ball will bounce heavier from it
- Normal - Ball will bounce from it like a normal wall
- Score - Adds to score once the ball touches it(it makes sense to use closed shapes with this type of boundary)
- Random - This will add a random functionality and an own color. It is not possible to know the functionality before the ball first touches the boundary

![image](img/pinball3.PNG)

Happy Playing!