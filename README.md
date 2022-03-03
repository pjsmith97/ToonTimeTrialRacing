# Toon Time Trial Racing Game
My coursework for my Computer Graphics course (INM376) at City, University of London. The game is a Time trial racer on rails. The main goal is for the player to complete their laps as quickly as possible by gathering speed-ups (blue rings) while avoiding obstacles (green spikes).

All game files and documentation are in the ToonRacingGame.zip file.

To play the game, run 'Source Code'/CourseworkDemo/OpenGLTemplate/bin/OpenGLTemplate.exe

To read the full documentation, open Documentation/'INM376 Coursework Report.pdf'

The project was meant to build upon my graphical skills, so seperate from the main gameplay are options to change between multiple camera angles (including a 'free roam' camera view) and a dark/greyscale filter option. There are a total of four camera view options in the game. The third person view is the default, as the camera travels behind the player along the track. The second view is first person, positioning the camera on the hood of the car. The third view is a top down view. This follows the car from a bird’s eye view of the scene (ignoring the car's orientation) as it goes along the track. The final view is the already mentioned 'free roam', which allows the player to wander freely about the scene. The camera mode also activates when the player pauses the game.

The main artistic drive for the game was the style. I was aiming for a classic cartoon aesthetic, with black outlines and almost everything having an elastic feel to it (ala. Cuphead (2017) or Sly Cooper (2002)). To achieve this I utilized techniques shown in the class and beyond regarding shaders. While the wobble animation of the palm trees were a simple utilization of what was taught to me, the car's animation required a bit more work as I fixed specific vertices to move along different axes at different points in time. And while the black outline was easier to achieve on the palm tree and rocks using the class technique, I had to adopt a whole different method to get an outline around the car using a trick with the stencil mask.

Controls:

1 - Left

2 - Right

6 - Pause

9 - Change Lighting (Toggle Dark Mode)

0 - Change Camera Mode

Mouse - (In Free View) Change Camera angle

W - (In Free View) Forward

S - (In Free View) Back

A - (In Free View) Left

D - (In Free View) Right

‘ESC’ - Close Game

