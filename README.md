# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Victor Dai**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/chain-warm-crush

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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
![Game Win Demo](http://recordit.co/vvPCVWbg0E)
![Game Lost Demo](https://recordit.co/FECpqYlZ2O)
![Start/Stop Demo](http://recordit.co/80SJvPQBud)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://developer.mozilla.org/en-US/docs/Web/CSS

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I was struggling with figuring out the cases for the function guess(btn). I referred to the solutions and understood that the key component of what I was not understanding was the existence of the pattern array and how that is how we can compare the guessed button with the actual answer. Through this whole process, I was also fixing bugs that I had made by mistyping when copying certain code snippets from the instructions of the prework. In the final function guess(btn), I had typed pattern[guessCounter] = btn instead of pattern[guessCounter] == btn in the if statement, which was the reason why the alert for "Game Over. You lose!" would never occur! In addition, I found another bug in this part of my code where I had incremented the guessCounter when I should have incremented the progress variable. These are additional reasons that gave me a headache when trying to figure out how to code guess(btn). I learned from this experience that it is important to first plan the structure of your code and execute it swiftly, making sure there little to no confusion for what you are coding and why are you doing it for a specific segment.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I am highly interested in web development and want to know more about JavaScript in particular. Questions I have are about DOMs, Website Databases, how to get the code for the sound producing of each of the buttons, useful resources to help beginning web developers, and things of this nature that will help me improve my fluency in web development. How do programmers maintain websites on a day-to-day basis and what are key principles in developing good applications and websites in terms of design and performance?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I was given a few more hours to work on this project, I would first focus on making the pattern array change for every new game that is started. Afterwards, I would also want to try changing the sounds of the buttons to see what other noises I can make the buttons produce. I also felt like the delay times and wait times between sounds is too long, so I would definitely make sure that the delay is shortened and also try to fulfill the other challenge feature of making the duration of time between each sequence of buttons faster. 


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Victor Dai

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
