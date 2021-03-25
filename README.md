# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Maia Gervasone**

Time spent: **2.5** hours spent in total

Link to project:

**Live site:** https://planet-cultured-beak.glitch.me
**Code:** https://glitch.com/edit/#!/planet-cultured-beak

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/yqu1im7.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.rapidtables.com/web/css/css-color.html#cyan -> Used for choosing CSS colors

https://www.w3schools.com/cssref/css_websafe_fonts.asp -> Used for choosing CSS Web Safe Fonts

https://www.schemecolor.com/indian-pan-card-background.php -> Used for choosing CSS colors that match together in a color scheme


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

For me, the hardest part in creating this submission was creating a new Cue Hold Time which would also work with the extra buttons I created. I had to test the game several times to ensure that the Cue Hold Time would work without any problems. If I decremented the Cue Hold Time by too much in each round of the game, then by the end of the game, the Cue Hold Time was too short and wouldn't hold the buttons for long enough so that a human could understand the pattern and repeat it. After trial and error, I found a good Cue Hold Time.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Rather than questions, I am more so fascinated in finding out what more I could do to a webpage. For example, I would like to learn how to implement effects such as movements, so that when a button was clicked, it would (for example) expand or shrink. Additionally, I would like to learn how to implement a visible counter so that the user knows how many rounds are left in the game rather than just playing without knowing when the game would come.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time, I would do as I stated in question 3. I would like to implement affects so that when the player clicked a button, it might shrink or expand. Additionally, I would have liked to include a visible counter so that the player knows how many rounds they have completed and how many more they still have to finish. If I wanted to make this game even harder, I could maybe implement a "bonus round" where only the sound cues are played and the player has to repeat back the pattern without any visual cues (such as the changing color of the buttons). Another thing that I would love to implement would be a "Game Score", and the quicker the player selects the correct button, the more points they get for the Game Score.



## License

    Copyright [Maia Gervasone]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
