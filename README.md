# PDM2025FinalProject
"Color Match" is a memory game where a sequence of colors will be displayed on screen. After the colors disappear, players will use buttons to select red, yellow, or blue. They will have to use these colors to match the colors that were displayed on the screen. The game ends when the player completes all the levels. The levels get harder with more colors at a time as well as having to mix colors to display new colors.

The physical arduino has 4 lights, 3 buttons, and a potentiometer. The 3 buttons corespond to 3 of the lights: red, yellow, and blue.![20250506_075012](https://github.com/user-attachments/assets/1ed29983-2812-4a2d-a50a-4851584935a6) When you press the button and the led lights up, you have selected that color. When two lights are on, the color mixes. For example, if the yellow and red lights are on, the color selected is orange. The green light is special. It indicates the brightness of the color: dark, dim, or bright. When the light is off it is dark. ![20250506_085110](https://github.com/user-attachments/assets/feee147d-2b15-4ea2-ad5b-e25dae69a104) When the light is dim, the color is dim. !![20250506_085058](https://github.com/user-attachments/assets/845987a5-fb90-4e54-ba9b-f53246e2cead) When the light is on and bright, the color is bright. ![20250506_085104](https://github.com/user-attachments/assets/f41a72c7-69ed-4105-a867-7258673f4769)

For example: when the light is bright and the color selected is red, the color selected is pink. If the green light is dim and red, blue, and yellow are all not selected, the color chosen is grey. If the light is off, the color is black. If the light is on, the color is white. 

Here is the color chart table:

Green light is off/dim:                                                   Green light is bright:                               Green light is dim/off/on (it doesn't matter):
Red light on: Red                                                         No other lights on: White                            Yellow light is on: Yellow
Blue light on: Blue                                                       Red light on: Pink                                   Yellow and red lights are on: Orange
Blue and yellow lights are on: Dark Green                                 Blue light on: Light Blue/Cyan                       Blue and red lights are on: Purple
_____                                                                     Blue and yellow lights are on: Light Green/Lime      Blue, red, and yellow lights are on: Brown
Green light is just dim and no other lights are on: Grey
Green light is completely off and no other lights are on: White

Clicking next level/continue will bring you to the next screen. The screen will flash with different colors. When the screen asks what the colors were, select the first color and hit continue. If you were correct, the screen will pop up with the correct screen. Then do the next color. ***You only submit one color at a time. If you were incorrect, the you will get a wrong screen and then the colors will flash again. You will not have to start from the beginining of the level. Just continue to put in your next color. When all the colors have been submitted for the level, the picture on the first screen will fill up with more colors: ![image](https://github.com/user-attachments/assets/a06bd248-8f39-47b2-aed2-7ff2d716b3f6) to ![image](https://github.com/user-attachments/assets/2d474fcc-69a3-4fa6-81d6-1aae22a821fd). Clicking next level will bring you to the next level until you reach the end of the last level, level 7. Then you will get a screen that says you have completed the game. All the lights light up on the arduino board when you get something correct.

Tone: There are 2 sequences running in the background as the background music. When the screen where the colors flash for you to memorize them, there is a different sequence that plays as the background music instead. When a color is selected, they each play a different continuous note. When the next level or continue button is pressed, a sample is played. The incorrect and correct screens also have different samples that play when their screen comes up. After level 4, the background music will gradually start to get faster. 

Video example: https://www.youtube.com/watch?v=TDoLrNYoPyM

In the future, I would probably make more levels and add an instructions screen. I would add something on the screen that says the color that is selected. (note: I have added it for the documentation submission)
