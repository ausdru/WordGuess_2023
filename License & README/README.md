# WordGuess_2023

## Description:
The motivation behind this project was to 

## Usage:

## License:

MIT License

Copyright (c) 2023 Austin Drury

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

USER STORY--------------------------------------------------
The completed application should meet the following criteria:

* As a user, I want to start the game by clicking on a button. 

* As a user, I want to try and guess a word by filling in a number of blanks that match the number of letters in that word.

* As a user, I want the game to be timed. 

* As a user, I want to win the game when I have guessed all the letters in the word.

* As a user, I want to lose the game when the timer runs out before I have guessed all the letters.

* As a user, I want to see my total wins and losses on the screen. 

ACCEPTANCE CRITERIA------------------------------------------
* When a user presses a letter key, the user's guess should be captured as a key event.

* When a user correctly guesses a letter, the corresponding blank "_" should be replaced by the letter. For example, if the user correctly selects "a", then "a _ _ a _" should appear. 

* When a user wins or loses a game, a message should appear and the timer should stop. 

* When a user clicks the start button, the timer should reset. 

* When a user refreshes or returns to the brower page, the win and loss counts should persist.