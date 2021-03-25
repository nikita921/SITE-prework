# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nikita Patra**

Time spent: **5** hours spent in total

Link to project: [https://glitch.com/edit/#!/resonant-majestic-camp](https://glitch.com/edit/#!/resonant-majestic-camp)

## Required Functionality

The following **required** functionality is complete:

* Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* "Start" button toggles between "Start" and "Stop" when clicked. 
* Game buttons each light up and play a sound when clicked. 
* Computer plays back sequence of clues including sound and visual cue for each button
* Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* User wins the game after guessing a complete pattern
* User loses the game after an incorrect guess

The following **optional** features are implemented:

* Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* Buttons use a pitch (frequency) other than the ones in the tutorial
* More than 4 functional game buttons
* Computer picks a different pattern each time the game is played
* Player only loses after 3 mistakes (instead of on the first mistake)


## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/2c4ea9bf-68ad-4f56-8961-3d3123c8fd37%2Fgeneral%20procedure.gif?v=1616615904165)
Winning the game:
![](https://cdn.glitch.com/2c4ea9bf-68ad-4f56-8961-3d3123c8fd37%2Fwin.gif?v=1616615649139)
Losing the game:
![](https://cdn.glitch.com/2c4ea9bf-68ad-4f56-8961-3d3123c8fd37%2Flose.gif?v=1616615648447)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
> for Javascript and CSS help:  
[https://www.w3schools.com](https://www.w3schools.com)  

>for CSS colors:  
[https://www.rapidtables.com/web/css/css-color.html](https://www.rapidtables.com/web/css/css-color.html)  

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
> In general, I felt comfortable with the process of creating this submission; the tutorial gave me a good foundation to experiment with various characteristics of the game. However, the portion I had the most difficulty was with the game logic and the nested if-statements.

> I didn’t want to look at the solution before figuring out the entire thing, so I first analyzed the flowchart in a way that allowed me to translate it into pseudocode. I tried thinking about the steps I would have to take in terms of the if-statements, and rearranged my comments in the order I would implement them in. I then began building incrementally. First, I coded the statement that would run if I chose the wrong button, which was easy to test. Once that worked, I moved on to the conditional statements that figured out whether the player’s turn was over or not. I chose to work on this portion after because it was the next easiest thing to test. From here, it was simple to add on what happens if the player wins. I figured out that the game would be over once the computer had finished playing the entire sequence and the player’s last turn was over. 

> Working incrementally helped me efficiently problem solve this area of the project. This method also helped me with easily implementing more guesses for the player, because I understood the way it was set up. I also encountered small issues with other areas of the project, but the preview pane allowed me to quickly catch my mistakes, which in turn helped me digest the material even further because I had to understand what caused the mistakes.   

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
> After completing this project, I had a lot of specific questions about the languages themselves, because I had never coded in HTML, CSS, or Javascript. For example, when I read about how we chose multiple fonts to fall back on in CSS (arial, sans-serif), if we didn’t include those, would the font fall back on the web browser’s default? Also, the way CSS uses inheritance reminds me a lot of basic polymorphism and object oriented programming principles; I wonder if these principles come into play when creating a more complex project. Would a more complex project require multiple CSS files, and if so, how do those files communicate with each other while remaining efficient? In C++ we have header files with guards for this, so do we do the same with CSS or is there a different method for such circumstances.  
  
> Other questions I thought about was regarding Javascript; the submission reminded me of how in the other languages I coded in, Java and C++, there were a few important differences when coding arrays. I would definitely want to explore the differences and similarities of Javascript arrays to these languages. The fact that it is dynamically typed is also new to me; when, if ever, would you need to declare the variable/parameter type or return type of a function? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
> If I had a few more hours to work on this, I would want to implement levels in the game. I would include a timer countdown, and as the player progresses, I would want there to be less time between each turn for them to guess. The computer will play back the sequence more quickly as well. I would also want to make the sequences longer as the player progresses, which would raise the difficulty even more.

> It would be interesting to add in difference modes that the player could choose. Modes would include the normal version, the computer only showing the sequence in colors and no sounds, and the computer only showing the new tile instead of the tiles that were played before. The player could also choose how many new squares they want to be shown by the computer each turn; for example, of the computer playing one new square every turn, it could play two or three.

> Changing the aesthetic of the game would be fun as well. Having several themes such as dark, light, or high contrast that the player can choose from would allow a level of personalization and would help accessibility. 




## License

    Copyright Nikita Patra

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
