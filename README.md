
# Godot 3D Character LookAt Controller and Gameworld Objects
Example project made with Godot 3.2
… still working on a release. This is just here for linking and as a reminder for myself to not forget about it.

![look_at_me](https://user-images.githubusercontent.com/52464204/73600862-0cf3d880-4557-11ea-860f-9bb1a4124abb.gif)
![look_at_controller](https://user-images.githubusercontent.com/52464204/71305410-cd709300-23d3-11ea-8b10-9dd4ff7778c7.gif)

## Features | Examples:
- Template for a 3D LookAt Controller to drop on your actors skeleton to make them more believable
- Example how to control a characters head and eye movement to look e.g. at the player or interesting objects in the gameworld
- Example for Point of Interest placement in the gameworld that will be viewed by actors with LookAt Controller
- Example controls for forced look position, focus time and sandbox behaviour with search in the surrounding area
- Example for Searchradius to pick closest available or random position and avoid picking objects behind walls
- Example how to use export variables to adjust a characters interest in certain targets
- Examples how to fix common pitfalls with wonky imported skeletons or engine madness
- Ruby colors!

## NOT included:
- The demo characters are not included, bring your own 3d character actors.
- I personally use blender and rigify skeleton bones but any decent skeleton will do. You will only have to find out what are the correct bone names for your head and each eye and play around with rotations to get them into a somehow decent starting position.

## Setup | Usage

### Step 1 - Wait until finished
... still working on it. This is just here as a reminder for myself to not forget about it.


## License
MIT or my personal 'Don't care' license, do whatever you want with this example and create something "to look at" (haha) in Godot.

## Known Issues
Since the last few updates Godot has small problems with skeleton bone overrides and inverse kinematic resulting in some glitches.
