---
layout: essay
type: essay
title: "Unity Game Project Final"
# All dates must be YYYY-MM-DD format!
date: 2021-09-5
published: true
labels:
  - Art
  - Design Theory
---

<img width="100px" class="rounded float-start pe-4" src="../img/Monongok Patch WIP.jpg">
Unity Game Proof Of Concept

Some formatting may be lost due to conversion from .docx to plaintext.


                                          Anthony L Deddens
                              Principles of Technology, Sullivan University
                                    CSC 200: Principles of Technology
                                            Scott Cordle
                                              9/5/2021

	Information Technology is the exact type of field I desire to work in. I love the idea of fixing computers, technology related issues, software problems, and setting up new software and hardware. I have always had a passion for computers, technology, AI, hardware, software, and similar subject matter. To work in an office and set up equipment, troubleshoot user issues, and repair damaged machines is a dream. One of my other dreams is to use my computer knowledge and artistic creativity to create a game. This project would not be possible if it were not for my years of extensive love and research of computers and technology as a whole.
The project I have made is a result of years of creativity, ambition, and a love of computers. It is a small-scale proof-of-concept as my circumstances during the ten weeks leading up to the final project have not been ideal. However, I have made a rough conceptual design of a game, utilizing my years of computer and programming experience. This intertwined with my lifelong artistic skills and storytelling has created; Attack on the Planet Ink! Or at least, a predecessor to a potential full game, sometime in my future.
	The scope of my complete game is vast. I imagine a linear based 3D third-person platformer. A game with an emphasis on smart and problem-solving AI who use the environment to their advantage, and trick the player at any chance they get. The game would span dozens of hours, and have enough content to justify several distinct chapters of the game. The premise would be aliens invading another alien world. And the players goal is to follow the commanders’ objectives, survive, and eventually defeat the alien leader to return home.
	For a ten-week project, my game cannot be this fleshed out. With no experience in any real game engine, I need to account for the time of learning the engine. Depending on my success, I see two objectives. Objective one would be to create a room with a playable character, and enemies. Have the enemies be able to attack, and be killed by the player. My secondary objective would be to create a boss. A larger enemy that would appear only when the others are defeated, and would have special attacks, alongside a larger health pool. If my progress goes faster than anticipated, I plan on adding complex platforming, then more enemy types, and potentially additional levels.
	This will demonstrate my creative skills and passions, and practical ways I can apply them to the real world with my computer experience. Between my knowledge of user interfaces, my ability to pick up and learn new programs, and my knowledge of programming and problem solving to accomplish goals in desired ways. I will be using this creative thinking and problem-solving skills on a daily basis in an Information Technology job. When it comes to fixing computers, diagnosing problems, or setting up new hardware in innovative ways to maximize performance.
	My visuals for a final product of a complete game would be stylized realism. Something inspired from Pixar’s approach on cartoony visuals in realistic environments. For this proof-of-concept project on the other hand. My visuals will be stylized low poly versions of my existing characters. Simple textures will be used for assets like the ground or sky, along with placeholder checkerboard textures for environmental objects. Such as platforms or walls. 
	The game engine of choice for this project is Unity 2021. Unity is a commonly used and widely available game development platform that is praised for its ease of access to new game developers. It is effective on several platforms. From Windows, to Mac, to Linux, and consoles. Even capable of building games for IOS and Android. It has the versatility to create any genre of game, from a puzzle game to a Virtual Reality one. Games can be rendered in real-time 3D, or with sprites, and in 2D.
	When it came to choosing my platform, I had five options. Unity, Unreal Engine, Godot, Blender, and Code.org. Three of these are realistic options for a finished game. Code.org is what I used to create my first game, and is an invaluable learning tool for programming. However, it is far too limited to create anything I aspire of, and utilizes Java as a coding language, which is outdated. 
	Blender is one of my favorite programs. As an artist, I use it to digitally model and produce 3D renders, but it is capable of many features. Previous versions of Blender had a built-in game engine. A unique quirk of Blender is the reliance on nodes. Instead of programming syntax, components are abstracted into node groups. These nodes can plug into other nodes to produce sophisticated effects. It is commonly used in producing shaders for the raytracing to use during render. These nodes act like a visual programming language, and are a key component in the game creation process. However, Blender games are known for instability and limited platform support, so it must be ruled out.
	Godot is a newcomer in the world of game design. It is a versatile, free, open-source game development engine. It is the preferred choice of many independent game designers, right next to Unreal and Unity. It has the benefits of Unreal, without any of its drawbacks. Disappointingly, it has its own unique drawbacks. While it is a capable tool, it is not one designed for beginners. The intricacies of the engine and navigating the user interface proved too difficult for the time crunch for this project.
	Unreal Engine is perhaps the best engine available. It is built for beautiful and powerful graphics. Cinematic games with powerful shaders can depend on this engine. This would be a perfect choice for a finished game. But my game has not even been prototyped. And while Unity could not handle the graphics I desire of an end product, my scope does not encompass the power Unreal provides quite yet.
	Unity was my final decision for three important factors. Unity is built for introducing new people into game design. While I have a good understanding on the artistic responsibilities of designing a game, I am fairly inexperienced when it comes to assembling one. Unity has a simple UI compared to other game engines, with a self-explanatory object-oriented interface. The design choices with Unity’s UI are reminiscent of Blender, which often goes hand-in-hand with Unity.
	The second reason I chose Unity was for its visuals. Its default visuals are a simple real time shader, unlike the complex raytracing Unreal provides. When exporting my game models as FBX for Unity to use, it preserved the original shaders and kept the simple colors I was aiming for. Letting the visuals stay simple complements the low-poly art style while keeping computing resources at a minimum. This frees up resources for the game to run smoothly even with inexperienced and tangled code that is inevitable with trying to create a game without prior experience.
	The final, and most important reason I chose Unity is the coding. I enjoy coding, but I am awful with syntax, it’s a struggle to click in my head. The reason I even considered Code.org was because the visual coding feels limitless to me, I could code endlessly with that toolbox. But the restrictions on Code.org are far too tight to make a game I desire. However, Unity 2021 has brand new native integration of Bolt, a visual scripting language for C++. Much like Blender, it uses nodes to describe mathematical and logical operations, and represent objects and parts of the game world. Bolt is what makes this coding challenge possible for me, helping me code the way I imagine it in my head.
	Now that the scope is decided, and engine chosen, I can move onto actually making progress on a build of the game. My first step is to model the characters. Unless I progress further than my initial scope, I only need three. The player character, an enemy character, and a boss character. In addition to being low poly, they will be segmented. This will make the rigging process easier, as the bones of a skeleton can have full control over segments of the body, instead of partial control with flexing in-between limbs. This will add to the artistic aesthetic while in conjunction speeding up the overall modelling and implementation time needed.
	The second obstacle I need to overcome is exporting the models. In Blender, the native file type is a Blend file. This is useful for working within Blender, but works poorly straight into Unity. Exporting it to FBX works great for Unity, but leaves strange axis artifacts. In Unity, the Y axis is up, while in Blender, the Z axis is up. This can be undone by rotating the model in Blender by -90 degrees. The FBX file type should automatically handle this, but for some reason did not.
	Once my models are exported, I need to give the movement. The player needs to move according to user input, and the enemies need to navigate to the player. The boss enemy will be handled after the player and enemy are functional, but will behave significantly differently than the standard enemy type. The player and enemy need a collision hull to bump into each other and into the walls and floor. Using WASD to control the player, and the space bar to jump is the end goal for player movement.
	Like any other coding exercise, errors will arise during the first time around. Troubleshooting was used to fix issues with inverted movement, and incredibly fast movement. After some trial and error, the code works fine and allows for simple movement. A camera is parented to the collision hull to stay behind the player at all times for the third-person platforming effect. The camera will utilize Unitys Cinemachine built-in addon for simple tracking to allow convenient and easy to use movement.
	The enemy AI is trickier to program. I am familiar with neural networks and have a fascination for AI in games, television, and products. I create well thought out diagrams and concepts of how AI should behave, but my struggle is implementing it into code. For a final game, the AI will flank, predict player movements, work in packs, and use the environment to their advantage to defeat the player. In this game, I am simply looking for the AI to follow the player, attempt to attack, and retreat if attacked. I researched an AI starter pack on Unity’s asset store, and reverse engineered the code. The code is made by Zero Logics, its premise is simple and clever, and in a way has no AI at all. 
The pseudo-AI works by assigning the player a LastPosition script. This creates invisible breadcrumbs that instantiate themselves at a player’s current location every few seconds, before deleting themselves. The enemy then proceeds to ray trace every game tick. If the rays hit a LastPosition breadcrumb, it will then move the enemy towards it. With the way the breadcrumbs linger, the enemies can track the players movements around corners if they are close enough. This makes a fairly competent enemy in an arena or maze-like setup without complex AI.
To attack the player, we first need health. The health is measured as an integer with a max of five health. Each attack the player takes deals one damage. When the enemy collision hull collides with the player hull, it begins an animation and ray traces. If the player is still in range, determined by the ray trace, damage is applied by negating one health point. Otherwise, the animation finishes and the enemy resumes pathfinding.
For the player to attack, there are two attacks. The player can swing a sword, which briefly activates a large collision hull that represents its range. If an enemy is in the hull, they take a damage point. There is a second ranged attack, which throws a frisbee shaped bomb forward. Once thrown, an animation begins. When the animation ends, a bomb object will be created in front of the player with a trajectory determined by the player direction when the animation ends. The bomb will fly forward a predetermined number of units and explode. If it hits a wall or enemy, it explodes early. The explosion destroys the bomb object, and flashes a collision hull to check for enemies and players, applying damage if they are in the range. 
This is the core of the game so far. Functional enemies, players, damage, and attacks. All within a carefully crafted arena that challenges the player without making it overwhelmingly difficult. Once the enemies are defeated, the boss reveals itself. The boss is large, and doesn’t path find. Instead, the boss teleports to random, predetermined, invisible, boxes and stays stationary within them, but will rotate to face the player. The boss has unique properties that make it distinct from regular enemies, and a challenge to the player.
The boss has three attacks, unlike the one attack the standard enemies had. The boss can melee attack the player with his tentacles. The boss can use his crown to shoot three laser beams. These beams will flash cones as collision hulls, and apply damage to players within the beam. The final attack is ink, which is special and deals two damage. Ink behaves like the players bomb, where the boss will perform an animation, and deploy an object at the end of it. The object will fire forward at its current rotation, and stop once it hits an object or the player. If it hits an object, like the wall or floor, it will create a small sphere that stays and deals damage if the player touches it.
	Once dealing enough damage, the player wins, and a victory window is displayed. More content was not added due to the lack of time available to me. Plans to add a new enemy, the Ink Wizard, who could teleport and shoot ink, similar to the boss, was in the works. However, there was not enough time for me to fit them in. Moving platforms would have been added as well, but this presented problems with the simple AI the standard enemies have.
	The process of me building the game was documented and recorded during several steps. Alongside a rough draft of a tutorial describing the creative and practical processes of turning a concept into reality. It has an emphasis on both creativity and artistic design. While keeping a realistic mindset and introducing basic concepts to new programmers. Including a demonstration with Bolt visual code, instead of C++ coding.
	I spend the first half of the tutorial discussing character design, and conceptual design in regards to art. Talking about realism, stylization, tone, and color. I then shift the discussion to practicality in a game setting and altering artistic vision to meet with realistic computing power. And correlate examples, such as renders of my game characters compared to their low-poly Unity variants.
	Further discussion leads into design elements in movement. Such as rigging, gaits, walk cycles, and procedural animation. I encourage artists to focus on designs with effective but simple walk cycles, and if at all possible, ways to let math and computers automate those cycles. Using examples from my own work to demonstrate my point as well. Like the segmentation of my models for easier rigging and more fluid movements.
	I focus on unusual aspects of design in the tutorial. I struggled translating aspects of other tutorials into my own. Tutorials used health bars instead of wheels. Or movement was 2D and first-person only. Converting these tutorials that get halfway to the desired goal was a challenge. But reverse engineering code is easier than expected, and enough trial and error can fix many problems.
	Overall, my project may have a small scope, but it achieves much as the first step into full on game development and as a proof-of-concept. It not only demonstrates my ideas, but also my ability to effectively use technology. To troubleshoot problems and errors within a computer’s logic, and my own. To describe problems to people with lesser understanding in an easy to digest and understandable way. And finally, to adapt to new situations and find solutions to problems that do not have obvious answers. These qualities are why I have a passion in art, and excel with computers and technology.
	
 
References
Logics, Z. (2014, May 22). Starter Kit | Movement Camera & AI. Retrieved from Youtube: https://www.youtube.com/watch?v=9UaMk712HAo

