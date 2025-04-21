Janus XR
1. VR ART GALLERY-
A VR Art Gallery is a fully virtual interactive environment through which the user navigates to visit and view the artwork in a computer-simulated 3D environment. Within the gallery, users can navigate via VR controllers so they are free to walk, touch,       manipulate objects in the scene, and touch or observe artwork closely. 

2. GAME ROOM ZONE-
The Game Room Zone is an active VR center with strategy, reflex, and sports-themed mini-games that demonstrate the complete potential of immersive interaction.
-3D Chess-
A contemporary take on the traditional strategy game, 3D Chess enables users to pick up, move, and set down chess pieces by hand or through VR controllers. The pieces are animated and the game played on a three-dimensional board to which users can walk, providing alternative views and more immersive experience. The spatial gameplay and intuitive controls make the experience feel natural and immersive.
-Gun Shoot-
Gun Shoot is a VR shooting game that requires reflexes, in which players shoot targets using natural gestures or controllers. It comes with several levels of difficulty and various types of targets including stationary, moving, and timed targets. The game is meant to improve hand-eye coordination, accuracy, and reaction speed and provide a challenging and enjoyable experience with visual and auditory feedback.
-Volleyball-
VR Volleyball provides an extremely interactive and physics-based multiplayer sports experience. Players can serve, pass, and spike the ball with motion-based controls mimicking real-world movements. The court is laid out for dynamic gameplay with precise ball physics so the experience feels realistic and competitive whether playing alone or with friends.

3. AR BOOK FOR KIDS: A TO Z INTERACTIVE LEARNING-
Kids' AR Book is an immersive learning experience where every letter of the alphabet causes a corresponding 3D object to appear when looked at through the app's camera, which makes learning fun and interactive for kids.

4. Features-
-Controller-Based Movement & Interaction
Consumers navigate the gallery using handheld VR controllers to walk around, teleport from one room to another, zoom in on paintings, spin sculptures, or grab information cards on the artists and pieces.
-Voice Interaction-
Voice commands offer a hands-free experience. When a person approaches an object, the audio guide plays automatically, creating a seamless and hands-free experience without the need for voice commands.

5. Unreal Engine VR Project Setup:
   a. Install Necessary Tools ~
-Unreal Engine: Install through the Epic Games Launcher.

-Visual Studio: Required for C++ projects and compiling. During installation, include the “Game Development with C++” and “Desktop Development with C++” workloads.

-Git: Needed to manage your project’s version control.

-(Optional) GitHub Desktop: A GUI for Git, useful if you prefer visual management over command line.

b. Create Your VR Project in Unreal ~
-Launch Unreal Engine and create a new project.

-Choose "Games" category and select either a Blank project or the VR Template.

-Choose Blueprint or C++, depending on your project needs.

-Enable Starter Content if needed.

-Name your project and choose a directory.

-Once inside, go to Edit > Plugins and enable your VR plugin (like SteamVR or OpenXR depending on your headset).

-Save and close the project.

c. Set Up .gitignore~
-Before you initialize Git, create a .gitignore file in your root project folder. This prevents large or unnecessary files from being tracked by Git.

Exclude folders like:

-Binaries/ – compiled files.

-DerivedDataCache/ – temporary assets.

-Intermediate/ – build intermediates.

-Saved/ – autosaves, logs, and backups.

Also ignore Visual Studio files like:

*.sln, *.vcxproj, *.sdf, and database files.

6. Introductory Steps for VR in Unreal Engine-
a. Understand VR Basics
Before jumping into Unreal, understand how VR works—head tracking, hand controllers, input systems, and interaction design are essential concepts.

b. Install Unreal Engine
Download and install Unreal Engine via the Epic Games Launcher. Make sure you have the latest version that supports VR development.

c. Prepare Your System for VR
Ensure your VR headset (like Oculus, HTC Vive, or others) is properly set up and working on your system. Install necessary drivers and companion software (like SteamVR or Oculus app).

d. Start a New VR Project
Launch Unreal Engine and create a new project. Use the VR Template which comes with basic motion controls, teleportation, and interaction features already set up.

e. Enable VR Plugins
-Go to Edit > Plugins and make sure relevant VR plugins are enabled, such as:

-OpenXR (recommended for cross-platform)

-Oculus VR or SteamVR (based on your hardware)

-XR Input

-Restart Unreal after enabling plugins if needed.

f. Set Up VR Preview
In Unreal, click the drop-down beside the "Play" button and select VR Preview. This lets you test your experience directly in the headset.

g. Begin Building VR Interactions
Use the Blueprint or C++ system to build interactions like grabbing objects, teleporting, triggering events with hand gestures, etc.




