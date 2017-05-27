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

- 2D
	- Textures
		- Environment Textures
	- Heightmap data (If applicable)
		- List required data required - Example: DEM data of the entire UK.
	- Etc.
- 3D
	- Characters List
		- Character #1
		- Character #2
		- Character #3
		- etc.
	- Environmental Art Lists
		- Example #1
		- Example #2 
		- Example #3
		- etc.
- Animation
	- Environment Animations 
		- Example
		- etc.
	- Character Animations 
		- Player
- Example 
- etc.
		- NPC
			- Example
			- etc.


<h1>Schedule</h1>
- <Object #1>
	- Time Scale
		- Milestone 1
		- Milestone 2
		- Etc.
	
<h1>Full Coding</h1>
	<br>- Group 5 Repository</br>
		<br>https://github.com/CSBinusInternational/L4BC-Group-5</br>
	<br>- finalproject.html</br>
		<!DOCTYPE html>
<html>
<head>
	<title>The Maze Runner : Infinite Labyrinth</title>
	<!-- Declaring Javascript for Babylon.js-->
	<script src="babylon.js"></script>
	<script src="hand-1.3.7.js"></script>
	<script src="babylonObjLoader.js" ></script>
	<!-- Importing CSS file-->
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<canvas id="mycanvas"></canvas>
	<script>
		// Declaring Canvas
		var canvas = document.getElementById("mycanvas");
		var engine = new BABYLON.Engine(canvas, true);

			// Declaring Scene
			var scene = new BABYLON.Scene(engine);

			// Enable Physics for the game
			scene.enablePhysics();

			// Importing background music named insaniquarium.mp3
		 	var music = new BABYLON.Sound("music", "insaniquarium.mp3", scene, null, { loop: false, autoplay: true });

		 	// Using ArcRotateCamera For the game
			var camera = new BABYLON.ArcRotateCamera("camera",0,0,0,BABYLON.Vector3.Zero(0,1,0), scene);
			camera.setPosition(new BABYLON.Vector3(0,10,30)); 	// Set Camera positing in x = 0 , y = 10, z = 30;
			camera.attachControl(canvas,true);
			scene.activeCamera.alpha += 3.13; // To set camera behind the object

			camera.checkCollisions = true; // Enable camera collision


			// Building Maze 
			// South Wall
			var southwall = new BABYLON.Mesh.CreateBox("southwall",3,scene); southwall.position.z = -99; 
				southwall.position.y = 5; 
				southwall.scaling.x = 67;
				southwall.scaling.y = 4;
				// Enable physic impostor for wall, and enable camera collisions for specific wall
				southwall.physicsImpostor = new BABYLON.PhysicsImpostor(southwall, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: -10, friction: 10000}, scene);
				southwall.checkCollisions = true;
				//Texture
				var matSouthwall = new BABYLON.StandardMaterial("southwall", scene);
				matSouthwall.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
				southwall.material = matSouthwall;

			// North Wall
			var northwall = new BABYLON.Mesh.CreateBox("northwall",3,scene); northwall.position.z = 99; 
				northwall.position.y = 5; 
				northwall.scaling.x = 67;
				northwall.scaling.y = 4;
				// Enable physic impostor for wall, and enable camera collisions for specific wall
				northwall.physicsImpostor = new BABYLON.PhysicsImpostor(northwall, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
				northwall.checkCollisions = true;
				//Texture
				var matNorthwall = new BABYLON.StandardMaterial("northwall", scene);
				matNorthwall.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
				northwall.material = matNorthwall;

			// East Wall
			var eastwall = new BABYLON.Mesh.CreateBox("eastwall",3,scene); eastwall.position.x = 99; 
				eastwall.position.y = 5;		   
				eastwall.scaling.z = 65;
				eastwall.scaling.y = 4;
				// Enable physic impostor for wall, and enable camera collisions for specific wall
				eastwall.physicsImpostor = new BABYLON.PhysicsImpostor(eastwall, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
				eastwall.checkCollisions = true;
				//Texture
				var matEastwall = new BABYLON.StandardMaterial("eastwall", scene);
				matEastwall.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
				eastwall.material = matEastwall;

			// West Wall
			var westwall = new BABYLON.Mesh.CreateBox("westwall",3,scene); westwall.position.x = -99; 
				westwall.position.y = 5;
				westwall.scaling.z = 65;
				westwall.scaling.y = 4;
				// Enable physic impostor for wall, and enable camera collisions for specific wall
				westwall.physicsImpostor = new BABYLON.PhysicsImpostor(westwall, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
				westwall.checkCollisions = true;
				//Texture
				var matWestwall = new BABYLON.StandardMaterial("westwall", scene);
				matWestwall.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
				westwall.material = matWestwall;

			// Wall North To Soutch #1
			var wall1 = new BABYLON.Mesh.CreateBox("wall1",3,scene);			
			wall1.position.x = -80;
			wall1.scaling.z = 10; 
			wall1.position.z = -85;
			wall1.position.y = 5;
			wall1.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall1.physicsImpostor = new BABYLON.PhysicsImpostor(wall1, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall1.checkCollisions = true;
			//Texture
			var matWall1 = new BABYLON.StandardMaterial("wall1", scene);
			matWall1.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall1.material = matWall1;

			var wall2 = new BABYLON.Mesh.CreateBox("wall2",3,scene);			
			wall2.position.x = -90;
			wall2.scaling.z = 7; 
			wall2.position.z = -45;
			wall2.position.y = 5;
			wall2.scaling.y = 4;
			wall2.rotation.y = 4.7;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall2.physicsImpostor = new BABYLON.PhysicsImpostor(wall2, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall2.checkCollisions = true;
			//Texture
			var matWall2 = new BABYLON.StandardMaterial("wall2", scene);
			matWall2.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall2.material = matWall2;

			var wall3 = new BABYLON.Mesh.CreateBox("wall3",3,scene);
			wall3.position.x = -80;
			wall3.scaling.z = 35;
			wall3.position.z = 30;
			wall3.position.y = 5;
			wall3.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall3.physicsImpostor = new BABYLON.PhysicsImpostor(wall3, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall3.checkCollisions = true;
			//Texture
			var matWall3 = new BABYLON.StandardMaterial("wall3", scene);
			matWall3.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall3.material = matWall3;

			var wall4 = new BABYLON.Mesh.CreateBox("wall4",3,scene);
			wall4.position.x = -60;
			wall4.scaling.z = 20;
			wall4.position.z = -50;
			wall4.position.y = 5;
			wall4.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall4.physicsImpostor = new BABYLON.PhysicsImpostor(wall4, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall4.checkCollisions = true;
			//Texture
			var matWall4 = new BABYLON.StandardMaterial("wall4", scene);
			matWall4.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall4.material = matWall4;

			var wall5 = new BABYLON.Mesh.CreateBox("wall5",3,scene);
			wall5.position.x = -55.5;
			wall5.scaling.z = 18;
			wall5.position.z = -21.1;
			wall5.rotation.y = 4.72;
			wall5.position.y = 5;
			wall5.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall5.physicsImpostor = new BABYLON.PhysicsImpostor(wall5, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall5.checkCollisions = true;
			//Texture
			var matWall5 = new BABYLON.StandardMaterial("wall5", scene);
			matWall5.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall5.material = matWall5;

			var wall6 = new BABYLON.Mesh.CreateBox("wall6",3,scene);
			wall6.position.x = -60;
			wall6.scaling.z = 15;
			wall6.position.z = 20;
			wall6.position.y = 5;
			wall6.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall6.physicsImpostor = new BABYLON.PhysicsImpostor(wall6, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall6.checkCollisions = true;
			//Texture
			var matWall6 = new BABYLON.StandardMaterial("wall6", scene);
			matWall6.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall6.material = matWall6;

			var wall7 = new BABYLON.Mesh.CreateBox("wall7",3,scene);
			wall7.position.x = -60;
			wall7.scaling.z = 15;
			wall7.position.z = 78;
			wall7.position.y = 5;
			wall7.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall7.physicsImpostor = new BABYLON.PhysicsImpostor(wall7, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall7.checkCollisions = true;
			//Texture
			var matWall7 = new BABYLON.StandardMaterial("wall7", scene);
			matWall7.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall7.material = matWall7;

			var wall8 = new BABYLON.Mesh.CreateBox("wall7",3,scene);
			wall8.position.x = -30;
			wall8.scaling.z = 15;
			wall8.position.z = -60;
			wall8.position.y = 5;
			wall8.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall8.physicsImpostor = new BABYLON.PhysicsImpostor(wall8, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall8.checkCollisions = true;
			//Texture
			var matWall8 = new BABYLON.StandardMaterial("wall8", scene);
			matWall8.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall8.material = matWall8;

			var wall9 = new BABYLON.Mesh.CreateBox("wall9",3,scene);
			wall9.position.x = -45;
			wall9.scaling.z = 11;
			wall9.position.z = -1.2;
			wall9.rotation.y = 4.72;
			wall9.position.y = 5;
			wall9.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall9.physicsImpostor = new BABYLON.PhysicsImpostor(wall9, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall9.checkCollisions = true;
			//Texture
			var matWall9 = new BABYLON.StandardMaterial("wall9", scene);
			matWall9.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall9.material = matWall9;

			var wall10 = new BABYLON.Mesh.CreateBox("wall10",3,scene);
			wall10.position.x = -30;
			wall10.scaling.z = 5;
			wall10.position.z = 5;
			wall10.position.y = 5;
			wall10.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall10.physicsImpostor = new BABYLON.PhysicsImpostor(wall10, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall10.checkCollisions = true;
			//Texture
			var matWall10 = new BABYLON.StandardMaterial("wall10", scene);
			matWall10.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall10.material = matWall10;

			var wall11 = new BABYLON.Mesh.CreateBox("wall11",3,scene);
			wall11.position.x = -30;
			wall11.scaling.z = 20;
			wall11.position.z = 55;
			wall11.position.y = 5;
			wall11.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall11.physicsImpostor = new BABYLON.PhysicsImpostor(wall11, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall11.checkCollisions = true;
			//Texture
			var matWall11 = new BABYLON.StandardMaterial("wall11", scene);
			matWall11.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall11.material = matWall11;

			var wall12 = new BABYLON.Mesh.CreateBox("wall12",3,scene);
			wall12.position.x = -45;
			wall12.scaling.z = 11;
			wall12.position.z = 43;
			wall12.rotation.y = 4.72;
			wall12.position.y = 5;
			wall12.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall12.physicsImpostor = new BABYLON.PhysicsImpostor(wall12, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall12.checkCollisions = true;
			//Texture
			var matWall12 = new BABYLON.StandardMaterial("wall12", scene);
			matWall12.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall12.material = matWall1;

			var wall13 = new BABYLON.Mesh.CreateBox("wall13",3,scene);
			wall13.position.x = -10;
			wall13.scaling.z = 5; 
			wall13.position.z = -92;
			wall13.position.y = 5;
			wall13.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall13.physicsImpostor = new BABYLON.PhysicsImpostor(wall13, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall13.checkCollisions = true;
			//Texture
			var matWall13 = new BABYLON.StandardMaterial("wall13", scene);
			matWall13.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall13.material = matWall13;

			var wall14 = new BABYLON.Mesh.CreateBox("wall14",3,scene);
			wall14.position.x = -10;
			wall14.scaling.z = 10; 
			wall14.position.z = -70;
			wall14.position.y = 1.5;
			wall14.position.y = 5;
			wall14.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall14.physicsImpostor = new BABYLON.PhysicsImpostor(wall14, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall14.checkCollisions = true;
			//Texture
			var matWall14 = new BABYLON.StandardMaterial("wall14", scene);
			matWall14.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall14.material = matWall14;

			var wall15 = new BABYLON.Mesh.CreateBox("wall15",3,scene);
			wall15.position.x = -19;
			wall15.scaling.z = 7; 
			wall15.position.z = -55;
			wall15.position.y = 5;
			wall15.scaling.y = 4;
			wall15.rotation.y = 4.7;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall15.physicsImpostor = new BABYLON.PhysicsImpostor(wall15, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall15.checkCollisions = true;
			//Texture
			var matWall15 = new BABYLON.StandardMaterial("wall15", scene);
			matWall15.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall15.material = matWall15;

			var wall16 = new BABYLON.Mesh.CreateBox("wall16",3,scene);
			wall16.position.x = -10;
			wall16.scaling.z = 5; 
			wall16.position.z = -30;
			wall16.position.y = 5;
			wall16.scaling.y = 4; 
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall16.physicsImpostor = new BABYLON.PhysicsImpostor(wall16, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall16.checkCollisions = true;
			//Texture
			var matWall16 = new BABYLON.StandardMaterial("wall16", scene);
			matWall16.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall16.material = matWall16;


			var wall17 = new BABYLON.Mesh.CreateBox("wall17",3,scene);
			wall17.position.x = -19;
			wall17.scaling.z = 7; 
			wall17.position.z = -21.2;
			wall17.position.y = 5;
			wall17.scaling.y = 4;
			wall17.rotation.y = 4.7;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall17.physicsImpostor = new BABYLON.PhysicsImpostor(wall17, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall17.checkCollisions = true;
			//Texture
			var matWall17 = new BABYLON.StandardMaterial("wall17", scene);
			matWall17.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall17.material = matWall17;

			var wall18 = new BABYLON.Mesh.CreateBox("wall18",3,scene);
			wall18.position.x = -10;
			wall18.scaling.z = 15; 
			wall18.position.z = 19;
			wall18.position.y = 5;
			wall18.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall18.physicsImpostor = new BABYLON.PhysicsImpostor(wall18, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall18.checkCollisions = true;
			//Texture
			var matWall18 = new BABYLON.StandardMaterial("wall18", scene);
			matWall18.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall18.material = matWall18;

			var wall19 = new BABYLON.Mesh.CreateBox("wall19",3,scene);
			wall19.position.x = 10;
			wall19.scaling.z = 20; 
			wall19.position.z = -50;
			wall19.position.y = 5;
			wall19.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall19.physicsImpostor = new BABYLON.PhysicsImpostor(wall19, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall19.checkCollisions = true;
			//Texture
			var matWall19 = new BABYLON.StandardMaterial("wall19", scene);
			matWall19.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall19.material = matWall19;

			var wall20 = new BABYLON.Mesh.CreateBox("wall20",3,scene);
			wall20.position.x = 10;
			wall20.scaling.z = 20; 
			wall20.position.z = 55.4;
			wall20.position.y = 5;
			wall20.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall20.physicsImpostor = new BABYLON.PhysicsImpostor(wall20, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall20.checkCollisions = true;
			//Texture
			var matWall20 = new BABYLON.StandardMaterial("wall20", scene);
			matWall20.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall20.material = matWall20;

			var wall21 = new BABYLON.Mesh.CreateBox("wall21",3,scene);
			wall21.position.x = -10;
			wall21.scaling.z = 14; 
			wall21.position.z = 83.7;
			wall21.rotation.y = 4.7;
			wall21.position.y = 5;
			wall21.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall21.physicsImpostor = new BABYLON.PhysicsImpostor(wall21, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall21.checkCollisions = true;
			//Texture
			var matWall21 = new BABYLON.StandardMaterial("wall21", scene);
			matWall21.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall21.material = matWall21;

			var wall22 = new BABYLON.Mesh.CreateBox("wall22",3,scene);
			wall22.position.x = 70;
			wall22.scaling.z = 18; 
			wall22.position.z = -73;
			wall22.position.y = 5;
			wall22.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall22.physicsImpostor = new BABYLON.PhysicsImpostor(wall22, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall22.checkCollisions = true;
			//Texture
			var matWall22 = new BABYLON.StandardMaterial("wall22", scene);
			matWall22.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall22.material = matWall22;

			var wall23 = new BABYLON.Mesh.CreateBox("wall23",3,scene);
			wall23.position.x = 25;
			wall23.scaling.z = 10; 
			wall23.position.z = -78.3;
			wall23.rotation.y = 4.7;
			wall23.position.y = 5;
			wall23.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall23.physicsImpostor = new BABYLON.PhysicsImpostor(wall23, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall23.checkCollisions = true;
			//Texture
			var matWall23 = new BABYLON.StandardMaterial("wall23", scene);
			matWall23.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall23.material = matWall23;

			var wall24 = new BABYLON.Mesh.CreateBox("wall24",3,scene);
			wall24.position.x = 40;
			wall24.scaling.z = 20; 
			wall24.position.z = -47.9;
			wall24.rotation.y = 4.7;
			wall24.position.y = 5;
			wall24.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall24.physicsImpostor = new BABYLON.PhysicsImpostor(wall24, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall24.checkCollisions = true;
			//Texture
			var matWall24 = new BABYLON.StandardMaterial("wall24", scene);
			matWall24.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall24.material = matWall24;

			var wall25 = new BABYLON.Mesh.CreateBox("wall25",3,scene);
			wall25.position.x = 40;
			wall25.scaling.z = 10; 
			wall25.position.z = -30;
			wall25.rotation.y = 4.7;
			wall25.position.y = 5;
			wall25.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall25.physicsImpostor = new BABYLON.PhysicsImpostor(wall25, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall25.checkCollisions = true;
			//Texture
			var matWall25 = new BABYLON.StandardMaterial("wall25", scene);
			matWall25.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall25.material = matWall25;

			var wall26 = new BABYLON.Mesh.CreateBox("wall26",3,scene);
			wall26.position.x = 40;
			wall26.scaling.z = 5; 
			wall26.position.z = -23;
			wall26.position.y = 5;
			wall26.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall26.physicsImpostor = new BABYLON.PhysicsImpostor(wall26, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall26.checkCollisions = true;
			//Texture
			var matWall26 = new BABYLON.StandardMaterial("wall26", scene);
			matWall26.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall26.material = matWall26;

			var wall27 = new BABYLON.Mesh.CreateBox("wall27",3,scene);
			wall27.position.x = 65.5;
			wall27.scaling.z = 23; 
			wall27.position.z = 40;
			wall27.rotation.y = 4.7;
			wall27.position.y = 5;
			wall27.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall27.physicsImpostor = new BABYLON.PhysicsImpostor(wall27, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall27.checkCollisions = true;
			//Texture
			var matWall27 = new BABYLON.StandardMaterial("wall27", scene);
			matWall27.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall27.material = matWall27;


			var wall28 = new BABYLON.Mesh.CreateBox("wall28",3,scene);
			wall28.position.x = 40;
			wall28.scaling.z = 13; 
			wall28.position.z = 80.5;
			wall28.position.y = 5;
			wall28.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall28.physicsImpostor = new BABYLON.PhysicsImpostor(wall28, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall28.checkCollisions = true;
			//Texture
			var matWall28 = new BABYLON.StandardMaterial("wall28", scene);
			matWall28.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall28.material = matWall28;

			var wall29 = new BABYLON.Mesh.CreateBox("wall29",3,scene);
			wall29.position.x = 58;
			wall29.scaling.z = 13; 
			wall29.position.z = 60;
			wall29.rotation.y = 4.7;
			wall29.position.y = 5;
			wall29.scaling.y = 4;
			// Enable physic impostor for wall, and enable camera collisions for specific wall
			wall29.physicsImpostor = new BABYLON.PhysicsImpostor(wall29, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0, friction: 10000}, scene);
			wall29.checkCollisions = true;
			//Texture
			var matWall29 = new BABYLON.StandardMaterial("wall29", scene);
			matWall29.diffuseTexture = new BABYLON.Texture("block.jpg", scene);
			wall29.material = matWall29;

			// Enable lights in the world, and setting its intesity
			var light = new BABYLON.HemisphericLight("light1", new BABYLON.Vector3(0,1,0), scene);
			light.intesity = 0.5;

			// Setting skybox in our game to create beautiful background
			var skybox = BABYLON.Mesh.CreateBox("skyBox", 1000.0, scene);
			var skyboxMaterial = new BABYLON.StandardMaterial("skyBox", scene);
			skyboxMaterial.backFaceCulling = false; // So that skybox can be viewed both outside and inside the box
			skyboxMaterial.reflectionTexture = new BABYLON.CubeTexture("skybox/skybox", scene);
			skyboxMaterial.reflectionTexture.coordinatesMode = BABYLON.Texture.SKYBOX_MODE;
			skyboxMaterial.diffuseColor = new BABYLON.Color3(0, 0, 0);
			skyboxMaterial.specularColor = new BABYLON.Color3(0, 0, 0);
			skybox.material = skyboxMaterial;

			// Creation of Character
			var snake ;
			var snakeSkeleton;
			BABYLON.SceneLoader.ImportMesh("","Finalproject/", "char.babylon", scene, function (newMeshes, particleSystems, skeletons) {

          	snake = newMeshes[0];
          	snakeSkeleton = skeletons[0];
          	scene.beginAnimation(snakeSkeleton, 0, 0, false, 1.0); // Beginning animation for the character
          	snake.physicsImpostor = new BABYLON.PhysicsImpostor(snake, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 1, restitution: 1000, friction: 1000000}, scene); // Enable physic impostor for the character
          	camera.target = snake; // Making camera follow the snake

            });  

			// Creation of Apple
	            var apple2;
				BABYLON.SceneLoader.ImportMesh("","Finalproject/", "apple.obj", scene, function (newMeshes, particleSystems, skeletons) {
					// Making apple appear random in the maze 
					var x = Math.floor(Math.random() * 145)-99;		
					var z = Math.floor(Math.random() * 145)-99;

	   				apple2 = newMeshes[0];
	   				apple2.position.x = x;
	   				apple2.position.z = z;
				});    

			// Declaring ground with the size of 200x200x200, and enable physic for it
			var ground = new BABYLON.Mesh.CreateGround("ground",200,200,200,scene);
			ground.physicsImpostor = new BABYLON.PhysicsImpostor(ground, BABYLON.PhysicsImpostor.BoxImpostor, { mass: 0, restitution: 0}, scene);
			var matGround = new BABYLON.StandardMaterial("ground", scene);
			matGround.diffuseTexture = new BABYLON.Texture("groundtex.jpg", scene);
			ground.material = matGround;

			// Boolean Expression for moving
            var up=false, down=false, left=false, right=false;
            var moving=false;

            // Declaring function start animation
            var animationState = false;
    		function startAnimation() {
        		if(!animationState){
            		animationState = true;
            		scene.beginAnimation(snakeSkeleton, 1, 30, true, 1.0);
        		}
    		};

    		var keyCode = {}
            	// Movement 
            		// Onkeydown is when holding the key
				window.onkeydown = function(e){
        		e = e || window.e;
        		keyCode[e.keyCode || e.which ] = true;
        		
        		// A Key
        		if(keyCode[65]){
           			left = true;
           			camera.rotation.z = Math.PI/2;
           			snake.position.x += 0.5;
					moving = true;
            		startAnimation();
        		}

        		// W Key
        		if(keyCode[87]){
            		up = true;
            		camera.rotation.z = -Math.PI;
            		snake.position.z -= 0.5;
					moving = true;
            		startAnimation();
        		}

        		// S Key
        		if(keyCode[83]){
            		down = true;											
					camera.rotation.z = Math.PI/2;
					snake.position.z += 0.5;
					moving = true;
            		startAnimation();
        		}

        		// D Key
        		if(keyCode[68]){
            		right = true;											
					camera.rotation.z = Math.PI/2;
					snake.position.x -= 0.5;
					moving = true;
            		startAnimation();
        		}

        	}

        		// Movement when we click the key
				window.onkeyup = function(e){
        			delete keyCode[e.keyCode];
        			if(!keyCode[65]&&!keyCode[87]&&!keyCode[83]&&!keyCode[68]) {
            			scene.stopAnimation(snakeSkeleton);
            			scene.beginAnimation(snakeSkeleton, scene.currentFrame, 0, false, 1.0);
            			animationState = false;
        				}
    				}
		
		// Function to loop every 1 frame
		engine.runRenderLoop(function() {
			//Locking the camera for Z axis
			if (camera.radius > 20){
			 	camera.radius = 20;
			}
			if(camera.radius < 20){
				camera.radius = 20;
			}

			// Locking the camera for Y axis
			if(camera.beta > 43){
				camera.beta = 43;
			}
			if(camera.beta < 43){
				camera.beta = 43;
			}

			if(moving){
				// If the snake collide with the apple, it will : 
				if (snake.intersectsMesh(apple2, false)){
					camera.setTarget(ground);
					camera.setPosition(new BABYLON.Vector3(0,240,220));

					// 1. Play clap sound music
					var clap = new BABYLON.Sound("clap", "clap.mp3", scene, null, { loop: false, autoplay: true });
					// 2. Dispose / Delete the apple
  					apple2.dispose();
  					// Display a new canvas and Congratulations message in medallion form
  					canvas2 = new BABYLON.ScreenSpaceCanvas2D(scene, {
			        	id: "mycanvas",
			        	size: new BABYLON.Size(250, 250),
			        	backgroundFill: "#4040408F",
			        	backgroundRoundRadius: 200,
			        	x : 100,
			        	y : 400,
			        	children: [
				            new BABYLON.Text2D("Congratulations", {
				                id: "text",
				                marginAlignment: "h: center, v:center",
				                fontName: "20pt Arial",
				            })
			        	]
	    			})
  								  							
				}

				// If the apple intersect with any way, it will re-random the position
					// Therefore its impossible for apple to be stuck inside the wall
				if (apple2.intersectsMesh(southwall, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(northwall, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(eastwall, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(westwall, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall1, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall2, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall3, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall4, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall5, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall6, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall7, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall8, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall9, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall10, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall11, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall12, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall13, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall14, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall15, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall16, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall17, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall18, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall19, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall20, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall21, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall22, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall23, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall24, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall25, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall26, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall27, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall28, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}
  				if (apple2.intersectsMesh(wall29, false)) {
  					var x = Math.floor(Math.random() * 150)-99;		
					var z = Math.floor(Math.random() * 150)-99;
  					apple2.position.x = x;
  					apple2.position.z = z;
  				}


			}
				//Rendering the scene
			scene.render();

		});
		

		window.addEventListener("resize",function(){
			engine.resize();
		});

	</script>

</body>
</html>
	-style.css
	html, body{
	width: 100%;
	height: 100%;
	overflow: hidden;
	margin: 0;
	padding: 0;
}

#mycanvas{
	width: 100%;
	height: 100%;
	margin: 0;
	padding: 0;
	touch-action: none;
}

Screenshot of the Game
<put images of your game>

