# MySpaceInvadersGame
This is simply an adaption of the Space Invaders game 
for my Intermediate Programming class.
========================================================
Earth needs someone who will defend them from Aliens! 
Only you can venture off into Space to fend off the
approaching army that wants to invade Earth!
========================================================
Ship
The player will control a ship that moves horizontally
along the bottom of the screen and shoots a laser at 
the aliens.
1: The Ship design is an artwork that I drew myself
2: Left and right arrow keys control ship movement. If
the ship should continue to move when an arrow key is
held down. The ship does not move off the edge of the
playing area. 
3: The space bar shoots a laser. The ship cannot fire
again until the current laser is destroyed.
4: Lasers shot by the ship make a laser blaster sound
Credit for sfx:
	https://www.youtube.com/watch?v=FuvmTL1nPDs
5: If ship is destroyed, plays an explosion sound
(credit below)

Aliens
Initially there are 28 aliens. (7 rows, 4 columns) The
size of each alien is 55 height x 25 width.
1: The Alien artwork is an artwork that I drew myself
2: Aliens move back and forth in unison. 
The speed at which Aliens move changes with the 
difficulties set by the player. When the alien
group reaches the edge of the playing area, they all
move down and reverse horizontal direction.
3a: Aliens shoot missiles at random intervals. They fire
at random intervals after a period of time depending on
the difficulty chosen by the player. 
3b: The Aliens make a plasma blaster sound when 
4: If the aliens reach the ship or the bottom of the
playing area, the game ends. If all the aliens are
killed, start a new level with more aliens.
5: Alien speed and alien count change dependent on 
your current level (how many times you've won)

Laser and Missiles
1: If a laser or missile goes out of bounds, it is
destroyed.
2a: If a laser hits an alien or missile, it is destroyed
and so is the object it hit.
Credit: https://www.youtube.com/watch?v=Xv1sDorNSmU
2b: If the laser hits a missile, the player gains a life
3: If a missile hits the ship, the missile is destroyed
and the ship loses a life. Plays an explosion SFX.
Credit: https://pixabay.com/sound-effects/search/explosion/
It was one of the sounds from this royalty-free library

Game Play and Scoring
1: Game begins when user presses the start/pause button.
2: Text of the button changes to pause.
  - If pause button is pressed, pause the game.
  - When game is paused, aliens don't move, ship does
    not respond to the keyboard, etc. 
  - Click this button to un-pause as well since text also
    changes to "Unpause" which will resume game
3: Difficulties can be changed with some radio buttons
EASY:
     - 3 lives
     - Enemies are slower.
     - Reduced score multiplier.
NORMAL:
     - 3 lives.
     - Enemies are normal speed.
     - Normal score multiplier.
HARD: 
     - 2 lives
     - Enemies are faster
     - Enhanced score multiplier
4: Each time a missile hits the ship, lose a life and
reset the ship position to its original starting location.
5: Score increases when aliens are destroyed. 
6: When the game is over, displays that the game is over
and resets to "title" to allow for a fresh new game
Changes score back to 0 after done.
7: When game is won increases level and as levels get
higher, aliens get faster and more aliens spawn
After a certain amount of levels the speed and count
won't increase
8a: Start button changes when
	NO GAME: to "Start"
	START: to "Pause"
	PAUSED: to "Unpause"
8b: Score and lives are displayed in current game but
hidden when on the title screen
isn't a current game.
8c: Difficulty radio buttons are displayed in title screen
but hidden when there is a current game.

EXTRAS:
- Fancy game over screen
- Audio sfx for laser, missile, ship explosion
- Fancy win screen
- Title screen
- Fancy ship and alien design
- Respawn timers
- Progressive Level System
    * more aliens
    * faster aliens
- Respawn cooldown to make sure player won't 
- Fancy ship explosion GIF
- Game Difficulty Modifier
	EASY:
	 * 3 Lives
	 * Slower Enemies
	 * Score multiplier is less
	 * Only one alien shoots at a time
	NORMAL:
	 * 2 Lives
	 * Normal Enemy Speed
	 * Score multiplier is normal
	 * Two aliens shoot at a time
	HARD: 
	 * Actually pretty difficult
	 * 2 Lives
	 * Faster enemies
	 * Score Multiplier is more
	 * Three aliens shoot at a time
CREDIT:
shiplasersfx.wav
    https://www.youtube.com/watch?v=FuvmTL1nPDs
alienmissilesfx.wav
    https://www.youtube.com/watch?v=Xv1sDorNSmU
explodesfx.wav
    https://pixabay.com/sound-effects/search/explosion/
Sonic4ExtraLife.wav
    Sonic the Hedgehog 4 - Extra Life Ep. 1-4 SFX
