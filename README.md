# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Rajvi Maisuria

Time spent: 4.5 hours spent in total

Link to project:

- Live Website: https://caterwauling-wistful-swift.glitch.me
- Project Code: https://glitch.com/edit/#!/caterwauling-wistful-swift

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

## Video Walkthrough (GIF)

<img src="https://imgur.com/bHuQuq1.gif" width=200><br>

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- https://htmlcolorcodes.com/
- https://www.w3schools.com/cssref/css_websafe_fonts.asp#:~:text=The%20following%20list%20are%20the%20best%20web%20safe,Courier%20New%20%28monospace%29%2010%20Brush%20Script%20MT%20%28cursive%29

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   
- A challenge I encountered was trying to figure out the logic behind the guess function. I wrote down the steps and what the game wanted to do and was able to then take the idea and sequence of steps down to create that logic. For example, I used the flowchart given to figure out that it would need to be a series of if and else statements nested together. Figuring out the code behind it was a little bit more difficult because I began with wanted to have a stand-alone if statement on the opposite rather than focusing on if the guess was correct and moving to the nested if statements which is what I couldn't figure out how to code, I coded if(!guess) with loseGame() in the inside. However, figuring out the rest based on that proved to be rather difficult. I took a peek at what was provided to see how I could the natural progression on what would happen if the guess was correct and was able to figure out the rest of the code from there. As the guess was correct, you could move on to look at the progress and sequences of the guesses before losing the game which would be the end all else statement.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   
- I learned a lot about web development through this project. Some questions that remain are what other libraries exist within in Javascript? We touched upon the sound libraries but didn't go too indepth about it and I was wondering what other databases exist to add other unique features to the website. How do you add underlinings to text in HTML? How can we adding movement and graphics? How can we make a website where users can login and save their progress or create a leaderboard? In terms of data storage, how would web development go about creating these profiles and connecting with people all over the globe? How would I go about creating a nav bar and menu to add different pages on one website? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
- If I had a few more hours to work on this project, I would have changed the colors of the tiles, added a score counter to be displayed and possibly a timer as well. I would have added extra buttons next to the start such as pause, hints, replay etc. I would have added different modes as well, where the patterns go by much faster or two tiles go off at the same time. I would also add additional tiles to make the game more difficult. These modes would probably go down this page until I were to figure out a menu option which would include a profile page and settings. These would require further code through the addition of functions and make the game a bit more fun and complicated. 

## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1Nhiqk3m06zW3l8Oje1pUJ1UCpPTrNon2/view?usp=sharing)

## License

    Copyright Rajvi Maisuria

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
