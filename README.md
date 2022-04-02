# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Angelo Alvarado**

Time spent: **3** hours spent in total

Link to project: (https://aquatic-fossil-amethyst.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![x](http://g.recordit.co/26kFioJRQe.gif)
![x](http://g.recordit.co/H8I4c9UdAV.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
 I referred to assignments in the web design course I am currently in as well as w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I think the most difficult part of this assignment was definitely the function to determine whether the user won or lost the game. It took me a bit to figure out, I would say a good portion of my time used with creating this website/game was spent on the winning function. I broke this down into two problems with an if statement: if the guess matches the answer pattern at the index, then that’s great! Otherwise, the guess was incorrect and you get a strike. In this else statement, it checks for 3 strikes in the program and will lose the game if so. I would then check if the turn is over, if not, I would increment the guessCounter. If so, we move onto the next statement (the game winner), if this is the last turn and you guessed it, you win! If it isn’t in the last turn, it would increment the progress counter and play the next button. I found the flowchart logic provided extremely helpful in this program. I believe breaking down the problem in half and continuously doing so really helps me, even in my Computer Science and Web Development courses.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I personally am curious about how these various web technologies interact with one another and how similar they are. I read about web development sometimes, and I see many web developers stating how studying a new framework affects the work you do. What is it that frameworks can complete that standard javascript cannot accomplish? What about framework against a framework (Angular against React, or Vue against Node for example). I also have the same question for backend frameworks. It seems like there's many technologies for different aspects of websites, when and how are web stacks used? Web development seems like a never ending adventure when it comes to learning these new technologies, but it seems like a satisfying challenge. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
 I would implement an “unlimited” mode for the pattern, once the user reaches the index before the array ends, and concatenate a new random array to the pattern. I would also scale in difficulty with a time limit. To feel like a true game, I would also use localStorage to store the user’s score and compare it to the high score (if one is not created, then this score will be the new high score) and will prompt the user for their name and store it in localStorage as well. I would have a leaderboard of 3 people available and make the appropriate comparisons to determine which score belongs in what place. I would also replace the sounds in the game to the appropriate Mario Kart item noise on the button. I believe adding different game states with divs would be great instead of alerts to the user’s window. I would have a div for game start, won,and  lost restart screen. When the website is first loaded, it would begin with the game start div, and upon winning or losing the game, the respective div is displayed and the others are hidden with css. The won and lost screen will have a restart button that allows the user to re randomize the pattern and play the game again.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/0b17b13b11b44d41a1ba7527a7f639bf)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
