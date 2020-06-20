# Minefield
This is just an old Android game I made in Unity

There was initially also a windows version, but I lost the project so I only have the android apk since it's on my phone.
Hitherto unreleased because I never bothered too much with making it look really nice and I didn't want to release something that looks so much like an unfinished game. Regardless, I did finish all the functional parts I had planned to add, so here it is.

The goal of the game is to drag the player circle around the screen to dodge all of the little enemy circles that spawn from the outer edges.

At the start, circles only spawn in the four corners, but at certain time intervals spawn points are added one by one until there are 9, 4 corners, 4 sides, and the center.

Circles spawn on a timer, every time the timer ticks, there is a random chance for each spawner to spawn a circle. The circle's velocity will be directed at the player's current position and it's speed will be directly proportional to the distance away from the player when it spawns. Enemy circles have a constant velocity.

As time passes, the timer will get shorter and shorter, causing more and more circles to spawn, until a new spawn point is added and the timer returns to its default length.

At certain time intervals, a green circle will appear on the screen. If the player touches it, all enemy circles will go away.

The player's score is simply the time, in seconds, they survive without touching an enemy circle.

Top 10 scores are stored both locally and online under the given player name entered on the menu screen.
