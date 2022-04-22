# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Bryan Loera

Time spent: 4 hours spent in total

Link to project: https://quasar-insidious-action.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
file:///Users/bryanloera/Desktop/CodePathPreworkGIF.gif

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One specific challenge I faced was locating the specific location in which to insert an attribute for an object. I overcame this by simply testing out different areas and seeing which would return me the response or effect that I wanted. I actually liked having this type of problem because it allowed me to either go search for outside resources which could help or figure it out myself by tinkering around with the program and using a cause/effect style of testing to see the different outputs I would get. Something else that wasn't necessarily a challenge but more or less fear was having to build a brand new program with unfamiliar programming languages. luckily the walkthrough was helpful and I was able to use some of my java skills with this program as well such as being able to organize my code in a readable human-friendly manner, using correct syntax even when it wasn't shown in the walkthrough and the overall formatting order in which I called functions to create a frictionless body of code in general. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Although I got a good idea of how the format of websites comes to be (ex. buttons, headers, and paragraphs), I still wonder what different techniques developers use in order to make unique formatting and style into their projects. Tinkering with HTML made me realize how versatile web development can be and how many tools are at one's disposal to create different types of websites depending on customers' needs. One of my questions right now involving web development would be how do the front and backend of a website communicate with each other. I think my primary idea of web development includes simply designing and creating the user interface but I'm not too familiar with how website UIs can communicate data and other information to the backend or other departments. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
With more time, I'd try implementing levels and different difficulties. For example, once one pattern was completed or won, id set up a function where a new series or patterns comes up while also altering the amount of time a user has to listen to the button sound, in this case, change from 1000 milliseconds in the original pattern to 750 in the 2nd, and 500 in the 3rd and so on. Another thing I would probably add would be a counter to see how many levels or patterns you've gone through. A different iteration of this idea but still fairly similar can be to track their progress using a tracker which checks how many individual integers within a pattern have been matched and how many are left. For example, in a pattern of let's say 8, (2, 2, 4, 1, 3, 1, 2, 4) I would create a separate variable like progressTracker = 0 and have it add 1 (++1) every time a button was correctly pressed this number would consecutively add up during the progress of the game. And lastly, building off the idea I just mentioned, a scoreboard would be a good idea as well. Using that same progressTracker variable, the user would be able to store their highest score (or highest value of the variable progressTracker itself) and save it to the name the user can input. Little changes like these can make the program feel more intuitive and user-friendly to encourage constant usage.  



## Interview Recording URL Link

[My 5-minute Interview Recording]https://www.loom.com/share/67056b6961f747cfab04f67fd1a10aba


## License

    Copyright BRYAN LOERA

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
