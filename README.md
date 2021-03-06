# Pong

## Assignment 0

### Specification

> - Implement an AI-controlled paddle (either the left or the right will do) such that it will try to deflect the ball at all times. Since the paddle can move on only one axis (the Y axis), you will need to determine how to keep the paddle moving in relation to the ball. Currently, each paddle has its own chunk of code where input is detected by the keyboard; this feels like an excellent place to put the code we need! Once either the left or right paddle (or both, if desired) try to deflect the paddle on their own, you’ve done it!

### Solution

Creating a function called updatePaddleAi which takes in the ball as a parameter. Changes the coordinates of the paddle so that the paddle is allways aligned with the center of the ball.

![pong](https://user-images.githubusercontent.com/19653954/91645631-fb1fd880-ea46-11ea-950e-1e58f195c0e5.png)

# Flappy-Bird

## Assignment 1

### specification

> - Randomize the gap between pipes (vertical space), such that they’re no longer hardcoded to 90 pixels.
> - Randomize the interval at which pairs of pipes spawn, such that they’re no longer always 2 seconds apart.
> - When a player enters the ScoreState, award them a “medal” via an image displayed along with the score; this can be any image or any type of medal you choose (e.g., ribbons, actual medals, trophies, etc.), so long as each is different and based on the points they scored that life. Choose 3 different ones, as well as the minimum score needed for each one (though make it fair and not too hard to test :)).
> - Implement a pause feature, such that the user can simply press “P” (or some other key) and pause the state of the game. This pause effect will be slightly fancier than the pause feature we showed in class, though not ultimately that much different. When they pause the game, a simple sound effect should play (I recommend testing out bfxr for this, as seen in Lecture 0!). At the same time this sound effect plays, the music should pause, and once the user presses P again, the gameplay and the music should resume just as they were! To cap it off, display a pause icon in the middle of the screen, nice and large, so as to make it clear the game is paused.

### Solution

> - Add the medals to the game

![Peewee Bird 18-9-2020 14_07_04](https://user-images.githubusercontent.com/19653954/93596234-44fe3d80-f9b9-11ea-874e-bb5c955981be.png)

> - randomized the gapheight and space. Add a new screen for the pause.

![Peewee Bird 18-9-2020 14_18_44](https://user-images.githubusercontent.com/19653954/93597022-a246be80-f9ba-11ea-8005-c93cb4ffc177.png)
