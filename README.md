<h1>The Maze Runner : Infinite Labyrinth</h1>

![](Img/Binus.jpg)

<p align="center">Revision: 0.0.0</p>
 
<p align="center">Final Project Report</p>
<p align="center">Game Design Development</p>
 
 
  
<p align="center">COMP6205 – Computer Graphics</p>
<p align="center">Computer Science Program</p>
<p align="center">Bina Nusantara University International</p>
<p align="center">2016/2017</p>
 
 
<p align="center">License</p>
<p align="center">If you use this in any of your games. Give credit in the GDD (this document) to Alec Markarian and Benjamin Stanley. We did work so you don’t have to.  </p>
 
<p align="center">Feel free to Modify, redistribute but not sell this document.</p>
 
 
<p align="center">TL;DR - Keep the credits section of this document intact and we are good and do not sell it.</p>

<h1>Table of Content</h1>
 
Overview………………………………………………………………………………………………...3<br>
&emsp;Theme / Setting / Genre<br>
&emsp;Project Description<br>
 
Core Gameplay Mechanics Brief…………………………………………………………….4<br>
&emsp;Targeted platforms<br>
&emsp;Project Scope<br>
 
Story and Gameplay……………………………………………………………………………….8<br>
&emsp;Story<br> 
&emsp;Gameplay<br> 
 
Assets Needed……………………………………………………………………………………….9<br>
&emsp;2D<br>
&emsp;3D<br>
&emsp;Animation<br>
 
Schedule……………………………………………………………………………………………….10<br>
 
Full Coding……………………………………………………………………………………………11<br>
 
Screenshots of game…………………………………………………………………………….39<br>

<h1>Overview</h1>

![](Img/Game_logo.jpg)

<h1>Theme / Setting / Genre</h1>
<ul>
	<li>Advanture</li>
  <li>Puzzle</li>
  <li>Strategy</li>
 </ul>

<h1>Project Description</h1> 
  Our project for this course, Computer Graphic, is a maze game with a genre of adventure, puzzle, and strategy. We named our game for the project is “The Maze Runner : Infinite Labyrinth”. Why we named it like that? Because when you go inside and trap in the maze you can not go out of the maze.
  The background of why we decided to make game maze is because a game with a concept maze and try to win with collect an object is very rare in this era, usually those game were famous back in the 2000’s where the game view is 2D so we decided to make the game with 3D concept.
  The game will consist of a maze from walls, a character that the player will control, a ground, sky, apple for the character to collect so the character could win the game and solve the mystery of the whole maze.
  In this game the character will play as Third person shooter (TRD). where the camera will follow the character movements from behind. The character itself we used Leon from Resident Evil 4 game. We chose Leon because the character Leon fits the situation of the game.

<h1>Limitations</h1>
<ol>
	<li>If the character acceleration with the wall is too big, impulse shall apply, and character will fall. Should such case happens, currently there is no way for character to get up but to refresh the game </li>
</ol>

<h1>How to install the game</h1>
<ol>
	<li>Git pull / clone this repository</li>
	<li>Search for the finalproject.html file</li>
	<li>Open it in Mozilla Firefox in order to play (Chrome, IE, etc are not yet tested)</li>
	<li>Have Fun</li>
</ol>

<h1>Core Gameplay Mechanics Brief</h1>
  <h3>Keyboard</h3>
<ul>
	<li>W key - In order to move forward </li>
  <li>A key - In order to move left</li>
  <li>S key - In order to move backward</li>
  <li>D key - In order to move right</li>
</ul>
<br>
  <h3>Mouse</h3>
<ul>
  <li>Mouse left click + ( Slide mouse to right ) - Rotate camera clockwise</li>
  <li>Mouse left click + ( Slide mouse to left ) - Rotate camera counterclockwise</li>

</ul>

<b4>
<h1>Targeted platforms</h1>
	<p>Web Based Game</p>
    <ul>
      <li>Mozilla Firefox</li>
    </ul>

<br>
<h1>Project Scope</h1>
<ul> 
  <li>Game Time Scale </li>
    <ul>
      <p>This game usually took two minutes of gameplay in average. It depends on where the apple spawn, because in this game the apple is set to random in the map. If the apple spawn in front of the character, the game will be short but if the character spawn far away from the character the player must walk wall to wall to find the apple and it will take time for that.
		  <br> <br>
    Shortest gameplay	: < 1 minute <br>
		Average		: 2 minutes <br>
		Longest gameplay	: > 3 Minutes</p>
    </ul>
</ul>
	

<h1>Team Size</h1>
<ul>
      <li>Core Team</li>
        <ul>
            <li>Giorgio Fasolini - 1901498082 - https://github.com/giorfasolini </li>
            <li>Ramada Atyusa - 1901498763 - https://github.com/ramadayusa </li>
        </ul>
</ul>
	
  <h1>What does they do?</h1>
<ul>
    <li> Giorgio Fasolini 
        <ul>
          I am the one who did coding to the maze. I was the one who implemented physics in the game to make the game even more real, The physics included impulse, restitution, and gravity. All of the walls and the character have been applied with impostor so that they can detect collisions with each other more clearly, when the character acceleration is too fast to the wall, the impulse shall apply and the character will receive force equal to his acceleration, and in the end character will fall. 
I was also the one who made the apple in the blender, I also make it so the apple will appear random every time the scene is rendered, should the apple is intersected with any other wall, the location will be re-randomized, Therefore the apple will always random and it will never stuck inside the wall. 
I also implemented skybox i have previously learned in class, for more elaborate background, we chose sky because we think that besides it is beautiful, a sky background is also more freshening and made player’s spirit more fired up 
Lastly i implemented camera lock based on its radius axis, so that the player cannot zoom-in or zoom-out to cheat to view the maze.  
        </ul>
   </ul>
   
   
   <ul>
    <li> Ramada Atyusa 
        <ul>
          For the front end project, I decided to search for the character object that will be played in the game. I decided to took Leon as the character because it fits for the game but the model is not good enough when I did the animation so I need to weight painting the character to make it nicer
	The character model I implemented armature bone for the animation. I created the animation for walk to the character  so it could be use in the game
 
Back end
For the back end I made the fixed camera of the third person shooter because the default camera is at the opposite that we want to be so I need to adjust it. For the camera also I made the the intersect with the wall so the camera cannot rotate through the wall. After that I decided to lock based on beta axis so player cannot rotate to up and down.
I also made the character implementation in babylon so when the player press W, A, S, and D the character will do the walk animation
And the last one is I made the walls for the maze. And make the pattern of the maze so the maze is little bit hard. And I decided to give the texture to the wall and ground to make it more realistic.
  

   </ul>
        
    
<h1>Licenses / Hardware </h1>
<ul>
  <ul>
   <p>Tested In</p>
    <ul>
          <li>
          Laptop ASUS P450L <br>
          Processor		: Intel Core i5 4210U<br>
          RAM			: 8 GB<br>
          VGA			: Nvidia 820m<br>
          Operating System	: Windows 8.1 Pro<br> 
          </li>
          <br>
          <li>           
    Laptop ASUS ROG GL552JX <br>
    Processor		: Intel Core i7 4720HQ <br>
    RAM			: 4 GB <br>
    VGA			: Nvidia 950m <br>
    Operating System	: Windows 10<br>      
          </li>
     </ul>
</ul>

<br> 

<h1>List Of library being used</h1>
  <ul>
    <li>babylon.js</li>   
    <li>babylonObjLoader</li>   
    <li>Hand-1.3.7</li>   
    <li>Blender</li>  
    <li>CSS</li>  
     <li>.Html</li>   <br>
  </ul>


<h1>Story</h1> 

The story is about a man both as famous detective and adventurer, he has conquered many puzzles and mysteries all around the world, and his hard work turned fruitful in form of fame and reputation. Now he seeks to conquer the last and most difficult maze in the world that no one has ever completed before.


<h1>Gameplay</h1>

For our gameplay of the maze game, the player must search an apple to win the game but the difficulty is the maze and the camera. We set the camera to lock the Z axis and Y axis so it makes the game more difficult because the player cannot zoom in and zoom out the map. The maze also difficult because we manage to make the maze hard so the player will confused when the are in the maze.
	For the controller in the game, the game will set at third person shooter and the player will use the character to explore the maze. As in general, to move the character forward press W button, to backward press S button, to turn left press A button, and to turn right press D button. And also, the player need to use mouse in the gameplay so the player can see the environment around him. Player needs to left click and slide the mouse to the right to turn the camera to the right and click left mouse and slide the camera to the left to turn the camera to the left 
	



<h1>Assets Needed</h1>

<h3>2D</h3>
	<ul>
		<li>Textures</li>
		&emsp;Groundtex.jpg to make the ground looks like grass (ground texture)
		<br>
		<li>Block.jpg to make the walls looks like real walls with bricks (wall texture)</li>
		<li>Skybox</li>
		&emsp;Skybox_nx.jpg<br>
		&emsp;Skybox_ny.jpg<br>
		&emsp;Skybox_nz.jpg<br>
		&emsp;Skybox_px.jpg<br>
		&emsp;Skybox_py.jpg<br>
		&emsp;Skybox_pz.jpg<br>
		<br>
		<li>Sound</li>
		&emsp;Insaniquarium.mp3 for background music<br>
		&emsp;Clap.mp3 for congratulation when player won the game
		<br>	
	</ul>
	
<h3>3D</h3>
<ul>
	<li>Characters List</li>
		&emsp;Char.babylon for the character Leon.S.Kennedy
		<br>
	<li>Environmental Art Lists</li>
		&emsp;Wall mesh for the wall in the maze<br>
		&emsp;Apple.obj for object apple
		<br>
</ul>

<h3>Animation</h3>
<ul>
	<li>Environment Animations </li>
		&emsp;None
		<br>
	<li>Character Animations</li>
		&emsp;Player<br>
		&emsp;Walking Animation
		<br>
	<li>NPC</li>
		&emsp;None<br>

</ul>
<h1>Schedule</h1>
	We started discussing the topic of the game around week 4. We actually have changed the game once, we previously wanted to make a snake game, where the player assumes control over the snake to collect as many points as possible in the game without dying (Hit by rock, or eating inedible fruit), Unfortunately, we lack knowledge in performing backtrack for snake movement and displaying appropriate canvas for the point thus resulting in the game unfinished 
	Upon entering week 8 after midterm, we decided to change the snake into character for more elaborate movement, we started to code thereafter, However we see that the game may be too simple and easy to play. Based on that idea we have decided to implement one last feature in our game which is the maze. Around week 9 to week 10 we started dividing the work equally with Giorgio doing backend, and Ramada doing frontend. This process takes about 1-2 weeks, by the beginning of week 12 we have combined our code and push it to github. And the remaining one week we decided to patch our code by improving its features such as (ex : textures).
 
 

<h1>Full Coding</h1>
	<br>- Group 5 Repository</br>
		<br>https://github.com/CSBinusInternational/L4BC-Group-5</br>

<h1>Screenshot of the Game</h1>
1. Character (Leon.S.Kennedy)<br>

![](Img/Img1.jpg)<br>

<br>2. Maze Overview

![](Img/Img2.jpg)<br>

<br>3. Apple Object

![](Img/Img3.jpg)<br>

<br>4. Ground Texture (grass)

![](Img/Img4.jpg)<br>

<br>5. Wall Texture (Brick)

![](Img/Img5.jpg)<br>

<br>6. Skybox Texture

![](Img/Img6.jpg)<br>

<br>7. Medallion display when winning the game (Canvas)

![](Img/Img7.jpg)<br>

