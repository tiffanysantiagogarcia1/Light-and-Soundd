# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tiffany Santiago Garcia**


## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I did not use any outside resources to help complete this submission.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[ A challenge I encountered in creating this submission was writing the conditional logic for the guess function. To overcome this challenge, I resorted to paper in pencil. Similar to the flow chart, I drew out and wrote pseudocode for each possible case. This process helped me gather my thoughts and gain an idea of how the code should work and look before I began typing. Once I had my pseudocode, I used my prior knowledge to start writing actual code for each possible case. I broke down this task into smaller sections - a technique I often use when coding since it helps me stay focused and ensures I cover every base. Therefore, making fewer mistakes, which means less debugging!
Now, explaining the thought process:  if the guess is correct, it proceeds to the next 'if-else' statment, which chekcs if the game is over. If so, it calls the 'winGame' function, displaying the winning statment; otherwise, it increments progress and calls the playClueSequence. If the GuessCounter does not equal progess itll increment the guessCount.If the guess was initally wrong, it skips all of the above and calls the loseGame function to display the losing statment. Although this was a challenge, taking the time to do pseudocode and breaking down the task helped me push through the challenge.]

4. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing my submission, my curiosity in web development has increased, particularly regarding the AudioContext library. While I understand that it was beyond the scope of this project, I am excited to learn more about it and explore its possibilities. My primary question revolves around the potential of web development—how much I can explore and how far I can push the boundaries. Specifically, concerning the improvements I mentioned in question 5: How can I implement these enhancements, and how can I create an inclusive and fun experience for my users with web development? I am extremely excited to learn more and research how I can implement my ideas to make a fully accessible and more advanced light and sound game!]

5. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would love to make it more accessible. Although we kept contrast in mind, I would like to add keyboard navigation, a screen reader for the text, game speed/ difficulty settings, and adjustment for volume. For the game, I would like to add different difficulty levels (easy, medium, hard) to allow a wide range of users to enjoy the game. For example, 'hard' may include more buttons and a faster time, while 'easy' may include fewer buttons and show the pattern at a slower rate. It would also be fun to keep track of the score; for instance, a scoreboard would be nice. I would also like the user to be able to enter a codename, which keeps track of their improvement and allows them to start off where they left off if they were to log in with their codename at another time. Additionally, I would like to make it an option to make the game increasingly harder. If someone doesn't want to jump to 'hard' immediately, they could start the game on easy, and once they hit a certain score, the game changes to medium and so on.]

## Video Walkthrough 

Add your screen recordings for specified implemented features here:
![losing screen recording] (https://www.loom.com/share/013a7f7121524bbeb3b7cbc9396a342e?sid=c32a3bd0-3ad7-4999-b025-bc4a9b93878f)

![winning screen recording] (https://www.loom.com/share/8c258d5cf93c4d7680df716a0a67f01e?sid=51973afb-0b7c-41e3-afd2-8a4f610e6dee)
## Interview Recording URL Link




## License

    Copyright [Tiffany Santiago Garcia]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
