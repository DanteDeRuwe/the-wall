# The Wall

This is a practice project for popular TV Trivia show "[The Wall](https://www.nbc.com/the-wall)". I used this concept to host a family trivia night on Christmas eve 2017.


It was built using [p5.js](https://github.com/processing/p5.js) (graphics) and [matter.js](https://github.com/liabru/matter-js) (physics).


## Where to find it?
https://the-wall.netlify.app/

## How does it work?
First, enter the name of the contestants.
Then, choose a round (usually one would start with round one)

The scores underneath *the wall* will update. 

The quizmaster asks a question, after that you can click on the tip of the wall to spawn balls, or you can put them in a specific spot by clicking the number-icons at the bottom of the side panel.

While the balls fall, the contestant has time to think about the answer. When the balls are in the bins below, scores will show up underneath. Thinking time is over.

The contestant answers the question. If it is correct, move the slider in the side panel towards the left (✅), the balls will turn green. If the answer is wrong, move the slider to the right (❌).

When the balls are colored, you can add the score (or subtract in case of red) automatically to the current player by using the `➕ score` button.

Now you can move on to the next player with the `➡ player` button. The balls will be cleared and the current-player indicator will move.

If for any reason you want to clear the balls or pause and play the simulation, there are buttons for that as well.

![](https://i.imgur.com/ZUPoFy4.png)




<br><br><br><br><br>
_I am not affiliated, associated, authorized, endorsed by, or in any way officially connected with NBC or any of the other broadcasters of this television show; nor with Glassman Media, SpringHill Entertainment or CORE Media Group. The use in this website and/or in related promotional print or video material of trademarked names and images is strictly for educational purposes, and no commercial claim to their use, or suggestion of sponsorship or endorsement is made by Dante De Ruwe._
