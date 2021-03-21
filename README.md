# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Mengfei Zhang

Time spent: **3** hours spent in total

Link to project: https://materialistic-workable-chevre.glitch.me<br/>
Code to project: https://glitch.com/edit/#!/materialistic-workable-chevre

## Required Functionality

The following **required** functionality is complete:
* [Yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Yes] Game buttons each light up and play a sound when clicked. 
* [Yes] Computer plays back sequence of clues including sound and visual cue for each button
* [Yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Yes] User wins the game after guessing a complete pattern
* [Yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Yes] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Yes] Buttons use a pitch (frequency) other than the ones in the tutorial
* [Yes] More than 4 functional game buttons
* [Yes] Playback speeds up on each turn
* [Yes] Computer picks a different pattern each time the game is played
* [Yes] Player only loses after 3 mistakes (instead of on the first mistake)
* [Yes] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [Yes] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
After being directed to the web page, the user can start the game by clicking the start button. Then the user will hear different sounds played by one of the five buttons. After the sound ends, the user will need to enter the corresponding pattern of the picture as the computer displays before. If the user guesses wrong for 3 times, the game will end. Otherwise, the user will be prompted to hear the next sound/image in the sequence and being asked to enter again. User will win the game if she/he guesses all the 8 sounds/images right. During the game process, the user can stop the game anytime by clicking the end button.
<img src = "https://media.giphy.com/media/0ucte1nd6HnA9OUR6U/giphy.gif" width = 250><br>
Start Game<br/>
<img src = "https://media.giphy.com/media/twPnG3okwaWzHbEllm/giphy.gif" width = 250><br>
Follow a Long Sequence<br/>
<img src = "https://media.giphy.com/media/fyOqsTMJBPysGRhk14/giphy.gif" width = 250><br>
Fail to Play the Game<br/>
<img src = "https://media.giphy.com/media/UFhLX8xxPPDBnXOuQu/giphy.gif" width = 250><br>
Success in Playing and End Button Shown<br/>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/html/<br/>
https://giphy.com/upload/upload

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?
One issue I face wasto adjust the waiting duration of each button. First, it decreases continuously throughout the game as I didn't set it back when we restart the game.
I also met a few difficulties when trying the display buttons as images. First, I could not find the right directory of the images I uploaded. I searched in command line for a while and finally figured out that glitch automatically saved our uploaded images as an url, so we can put the url into our project instead of using the images locally.
When I'm trying to add images into the button, I first find it difficult to adjust the image into the same size of the button. Then, I choose to add the image style inside the Botton in html. However, in this way, the bottom style will always remain the same and the user can not differentiate which button is playing the music. As a result, I decided to change the button in the css file so that the bottom can show different images at different state (active or nonactive.) So I searched for this function online and implemented it.
I also encounter some glichy while uploading thegid to README.me by using quicktime. I searched online on how other people solve the problem then figured I counld use giphy to make a gif url and link it to README.me on github.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
How is React different from the html+css+javascript methodology I'm using for the assignment. What's the comparative advantages for each of them.
How can we separate frontend and backend development? Because in this assignment, I feel like I'm at the same time dealing with all these three html+css+javascript files. However, for a large projects which require software engineers to work on different parts, how can they divide their work?
Can we shift/slide the position of the button module while using playing the game?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would first make the webpage more artistic. For instance, I would change the image, button color, position, and add more user prompt to guide user through the gaming process.
Second I would add the game process window so that the user can see their game progress and number of mistakes made.
Third, I will let the user to adjust the difficulty level of the game by prompting them to choose the number of buttons, maximum length of sequence.
Furthermore, I would like to make the game being played by multiple users. If they log into the website and enter into the same game room, they can alternatively guess the game sequence and play in teams.

## License

    Copyright Mengfei Zhang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
