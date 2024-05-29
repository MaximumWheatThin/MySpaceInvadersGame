# MySpaceInvadersGame
<h3>This is simply an adaption of the Space Invaders game 
for my Intermediate Programming class.</h3>
<h2>Earth needs someone who will defend them from Aliens! 
Only you can venture off into Space to fend off the
approaching army that wants to invade Earth!</h2>
<h3>Ship</h3>

<p>The player will control a ship that moves horizontally
along the bottom of the screen and shoots a laser at 
the aliens.
	
<br>1: The Ship design is an artwork that I drew myself
<br>2: Left and right arrow keys control ship movement. If
the ship should continue to move when an arrow key is
held down. The ship does not move off the edge of the
playing area. 
<br>3: The space bar shoots a laser. The ship cannot fire
again until the current laser is destroyed.
<br>4: Lasers shot by the ship make a laser blaster sound
<br>	Credit for sfx:	https://www.youtube.com/watch?v=FuvmTL1nPDs
<br>5: If ship is destroyed, plays an explosion sound
(credit below)</p>

<h3>Aliens</h3>
<p>Initially there are 28 aliens. (7 rows, 4 columns) The
size of each alien is 55 height x 25 width.
	
<br>1: The Alien artwork is an artwork that I drew myself
<br>2: Aliens move back and forth in unison. 
The speed at which Aliens move changes with the 
difficulties set by the player. When the alien
group reaches the edge of the playing area, they all
move down and reverse horizontal direction.
<br>3a: Aliens shoot missiles at random intervals. They fire
at random intervals after a period of time depending on
the difficulty chosen by the player. 
<br>3b: The Aliens make a plasma blaster sound when 
<br>4: If the aliens reach the ship or the bottom of the
playing area, the game ends. If all the aliens are
killed, start a new level with more aliens.
<br>5: Alien speed and alien count change dependent on 
your current level (how many times you've won)</p>

<h3>Laser and Missiles</h3>
<p>1: If a laser or missile goes out of bounds, it is
destroyed.
<br>2a: If a laser hits an alien or missile, it is destroyed
and so is the object it hit.
<br>Credit: https://www.youtube.com/watch?v=Xv1sDorNSmU
<br>2b: If the laser hits a missile, the player gains a life
<br>3: If a missile hits the ship, the missile is destroyed
and the ship loses a life. Plays an explosion SFX.
<br>Credit: https://pixabay.com/sound-effects/search/explosion/
It was one of the sounds from this royalty-free library </p>

<h3>Game Play and Scoring</h3>
<p>1: Game begins when user presses the start/pause button.
<br>2: Text of the button changes to pause.
<br>  - If pause button is pressed, pause the game.
<br>  - When game is paused, aliens don't move, ship does
<br>    not respond to the keyboard, etc. 
<br>  - Click this button to un-pause as well since text also
    changes to "Unpause" which will resume game
<br>3: Difficulties can be changed with some radio buttons
	
<br><b>EASY:</b>
<br>     - 3 lives
<br>     - Enemies are slower.
<br>     - Reduced score multiplier.
<br><b>NORMAL:</b>
<br>     - 3 lives.
<br>     - Enemies are normal speed.
<br>     - Normal score multiplier.
<br><b>HARD: </b>
<br>     - 2 lives
<br>     - Enemies are faster
<br>     - Enhanced score multiplier
	
<br>4: Each time a missile hits the ship, lose a life and
reset the ship position to its original starting location.
<br>5: Score increases when aliens are destroyed. 
<br>6: When the game is over, displays that the game is over
and resets to "title" to allow for a fresh new game
Changes score back to 0 after done.
<br>7: When game is won increases level and as levels get
higher, aliens get faster and more aliens spawn
After a certain amount of levels the speed and count
won't increase
<br>8a: Start button changes when
<br>	<b>NO GAME:</b> to "Start"
<br>	<b>START:</b> to "Pause"
<br>	<b>PAUSED:</b> to "Unpause"
<br>8b: Score and lives are displayed in current game but
hidden when on the title screen
isn't a current game.
<br>8c: Difficulty radio buttons are displayed in title screen
but hidden when there is a current game.</p>

<h3>EXTRAS:</h3>
<br>- Fancy game over screen
<br>- Audio sfx for laser, missile, ship explosion
<br>- Fancy win screen
<br>- Title screen
<br>- Fancy ship and alien design
<br>- Respawn timers
<br>- Progressive Level System
<br> * more aliens
<br> * faster aliens
<br>- Respawn cooldown to make sure player won't 
<br>- Fancy ship explosion GIF
<br>- Game Difficulty Modifier
<br>	<b>EASY:</b>
<br>* 3 Lives
<br>* Slower Enemies
<br>* Score multiplier is less
<br>* Only one alien shoots at a time
<br>	<b>NORMAL:</b>
<br>* 2 Lives
<br>	 * Normal Enemy Speed
<br>	 * Score multiplier is normal
<br>	 * Two aliens shoot at a time
<br>	<b>HARD: </b>
<br>	 * Actually pretty difficult
<br>	 * 2 Lives
<br>	 * Faster enemies
<br>	 * Score Multiplier is more
<br>	 * Three aliens shoot at a time

<h4>CREDIT:</h4>
<br>shiplasersfx.wav
<br>    https://www.youtube.com/watch?v=FuvmTL1nPDs
<br>alienmissilesfx.wav
<br>    https://www.youtube.com/watch?v=Xv1sDorNSmU
<br>explodesfx.wav
<br>    https://pixabay.com/sound-effects/search/explosion/
<br>Sonic4ExtraLife.wav
<br>    Sonic the Hedgehog 4 - Extra Life Ep. 1-4 SFX
