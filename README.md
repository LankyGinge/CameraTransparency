# CameraTransparency

*Made for Unreal Engine 5.4*

## What Is CameraTransparency?
Most people who have tried to make any third person game in Unreal Engine have probably noticed two problems with the camera:

**1.** The camera collides with objects in the game world meaning that in tight situations, the player is unable to be seen.

*well that seems simple enough just disable collisions on the camera right?*

**2.** When collisions are disabled, if the object is thin enough, the player can be hidden behind objects making it hard to move the player around a playspace or to dodge projectiles.

CameraTransparency aims to provide a solution to these issues by making every object that comes in between the player camera and the player transparent.

## How To Set Up
Firstly, download the Camera_System file from this page and drop it into the "Plugins" folder of the Unreal Engine project you want to add it to. If there is no file called "Plugins", right click and make a new folder called Plugins.

Once in your project, navigate to any player character that would need this functionality and double click to edit the character's blueprint.

Now navigate to the "Components" window and press the Add button. Search for an actor component called AC_Camera_System.

Once that has all been done, navigate to the "SpringArm" and turn off "Do Collision Test" to disable the camera collision enabling the plugin to work.

And that is all the set up required to use CameraTransparency!
