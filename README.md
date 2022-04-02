# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kyle Hu

Time spent: 1 hour spent in total

Link to project: https://glitch.com/edit/#!/twilight-solstice-tennis

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
<img src = 'http://g.recordit.co/3ntJnrXQpQ.gif'>
<img src = 'http://g.recordit.co/86QiiVvyDf.gif'>
<img src = 'http://g.recordit.co/sXIbYh47cT.gif'>
<img src = 'http://g.recordit.co/q3obi8Akbz.gif'>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. <br />
I used only the w3schools website to reference some of JavaScript's functionality.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)<br />
One challenge I had was understanding the logic of the playClueSequence function. The way I overcame it was through reading each line of the function and trying to grasp the intentions and ideas behind the function. However, this only gave me a general idea of how playClueSequence worked. With my basic knowledge, I tried tracing the logic of the function on pen and paper. I would list each step and what each line of code in the function performed. After tracing out the logic, I used some console statements to clarify any confusion I had with the function.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)<br />
After looking at how quickly I managed to make a simple game on a website, I thought about what are the limitations of a website? What can a website be and what is something that a website never can be? Thinking about the possibilities of a website, I have always wondered how websites such as Facebook incorporate a database or data storage functionality into their websites? I am really interested in what it takes to connect a database to the website for a user to see. I also wonder what are the advantages and disadvantages of using Javascript as a back end for a website? I have seen tutorials online of people using Python, Ruby, and other languages to program websites.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)<br />
I would first comment every part of script.js, index.html, and style.css. By doing this, I will allow other programmers to get a better understanding of the code. In addition, if I decide to revisit the code, I can rely on the comments to remember how the program functions. I would combine the loseGame and winGame functions into a single function since their only difference is the alert message. I would have a function with an if statement that only changes the alert message. I would also split the script.js into different sections. By this I mean I would organize functions that are similar together and use comments to label each section. If possible, I would have different files JavaScript files for each section.



## Interview Recording URL Link

[My 5-minute Interview Recording] https://drive.google.com/file/d/1y8PgnNSrS2UUm4fPKxw1J26x96huv6fA/view?usp=sharing


## License

    Copyright Kyle Hu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
