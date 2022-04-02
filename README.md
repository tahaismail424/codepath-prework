# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Taha Ismail**

Time spent: **3** hours spent in total

Link to project: (https://glitch.com/edit/#!/misty-calico-agustinia)

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
![x](https://drive.google.com/file/d/1fJ7B4IpQWDnygbtL318NsHaSGMqE_LtO/view?usp=sharing)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I fortunately did not encounter any specific issues when it came to coding and uploading the submission. I did, however, run into some issues with understanding what it was that I was actually coding. When it came to playing the tones, it was difficult for me to understand how the sounds were produced and how I may manipulate them if I wanted to. I did not have a solid understanding of the "Audio Context" object so I was unsure of how it was getting the sounds to play in the game. I believe to remedy this issue I would have benefited from reading the documentation on the Audio Context class as I would be able to gain more insight into how sounds (outside of video and audio files) may be produced on a web page. Moreover, syncing the audio to specific mouse clicks was a process that was difficult for me to understand, so I think in general I would benefit from learning about these modules and classes that help make websites interactive (clicks, key presses, drag, movement, etc.) so that I may one day be able to make my own web pages interactive as I see fit without many issues. I fortunatley did not have any issues to overcome when it came to trying to make the game functional, just in understanding the specific code I was writing. With more practice with these modules and classes I believe I will become more comfortable with these concepts. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have questions about the "window" module in JavaScript. In the game, we used the "AudioContext" class inside it to generate sounds for our game as the colored buttons were pressed. It seems the "window" module likely contains other classes, functions, etc. that are responsible for controlling activity on the webpage as a whole and helping make it more responsive/interactive (refreshing, draggging, key presses, etc.) so I'm interested in learning more about it so that I may be able to develop more interactive web applications in the future. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would add additional features to make the game more interesting. As the webpage loaded, it would be nice to add a difficulty setting. So a user could pick between easy, medium, and hard more. Easy mode would be similar to the game as we coded it. Medium mode could add additional buttons and ask for a longer pattern, and hard mode could do that with even more buttons and a longer pattern. 

Other than the functionality of the game, I believe the UI could be definitely updated because as coded it is somewhat plain. If the background were of a different color, the buttons a little more polished looking, and the sounds more interesting (perhaps through playing a familiar melody - Jingle Bells, etc.), I believe it would make for a more enjoyable experience for whoever were to play the game.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/19cwmwFKv7lIAQ1Mn8iZVesrA8zk_ZtZh/view?usp=sharing)


## License

    Copyright Taha Ismail

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.