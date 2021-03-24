Time spent: 2 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
![](https://i.imgur.com/FRNk5ay.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources.
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
Something that I did not get was how to make the button change color when clicked to notify whoever was playing the game that they are clicking on the buttons. I overcame it by just remembering that the properties available for your use in css reminded me a little bit of dart which is why I had tried to use the active property to see if it would change colors. Which it had successfully done. Something that was also a little hard to find out was the playClueSequence because at first I did not know how to do the function. But after looking at the video tutorial I realized immediately you need to have some kind of delay as well as a for loop. So we can have the game go for a certain number of times until it is over. Which is how I was eventually able to figure out the function.
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some questions I have about web development after doing this mini project ishow do you randomize the number of rounds this game can contain. Also another question I was curious about while doing this project was how to have different difficulties of the game where it lasts longer or if the button of the sound is just produced and they have to determine which button it is. Something that really interested me was how many different properties there are because they are so helpful when doing web development. How to be able to add pictures to your website. Something that I was thinking about was instead of having a certain amount of frequencies is there a way to randomly choose different frequences out of random so the 4 buttons does not have the same sounds.  
4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I actually would like to implement a couple more features like for example have different difficulties and trying to figure that out for myself. Having different modes like instead of having the buttons shown lighting up we can have the sound play and then you have to determine which button was pressed. Something that would be also interesting is to be able to change the sounds every time the game is played and instead of having a certain amount of frequencies to choose from. I also think that I would like to implement maybe different songs instead of having frequencies because I think it will be fun to do. Something that also sounds interesting is to make it so the user has to hold the button for a certain amount of time for it to go through. Like having a bar fill up through the button until it is all the way filled for it to work.



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