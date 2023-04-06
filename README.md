# Assignment 7.4: Interactive 3D Environment

 At this point in the course, you should have a good understanding of all elements that come together to create a visually appealing interactive user experience. Use what you have learned about interaction, materials, UIs, and animation in Unity to create your own interactive 3D environment.

At a minimum, your assignment should include the following:

A set of assets arranged in a cohesive way which makes sense for your environment—you can browse the asset store for asset packs, create them yourself, or collaborate with someone from your workplace to create them together
A first-person camera that responds to mouse motion, along with WASD movement, so that users can navigate through and look around in the environment you have created
A set of boundaries that prevent the user from going outside of the bounds of your environment
A set of other entities that respond to the user's presence or input via animation—your environment should feel “alive” in some way and should respond to the user
The environment should include a functioning UI
Tertiary cosmetic elements like sounds and lights

# my project

I made a low res mostly-to-scale model of my NYC apartment using Probuilder
There is a main menu that explains the controls and has PLAY and QUIT buttons and a pause menu that has RESUME and QUIT buttons
The main gameplay is just a first person character that can move through the apartment
The bathroom door, closet door, oven door, and drawers of two nightstands open and close with onTrigger events
There is ambient sound that plays at a low volume until you move to one of the windows, which opens with an onTrigger event, and the volume of the sound fades up (and down once the window closes)
I also put some creepy dolls behind all of the interactions, just to add some color to the scene