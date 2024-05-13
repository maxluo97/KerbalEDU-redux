# Introduction

This document will serve as reference material for instructors to make the best of KSP as an educational tool. As such, it will cover "technical" topics that are not relevant to a student's learning - e.g. creating objects and vehicles, editing orbits, etc. While it will highlight certain gameplay tricks or advanced mechanics to better your instruction, it is **not** intended to serve as a base tutorial on how to play the game. For that, I suggest either working through the game's built-in tutorials (found under Start Game > Training from the main menu), and/or taking time to actually play through the game yourself. This document will work under the assumption that you will be using the game's Sandbox mode, and that you will be using the plugin HyperEdit, unless otherwise specified. This document will also work under the assumption that you have enough working knowledge of spacecraft engineering and orbital mechanics to teach a middle or high school class on the topic.

# Setup

Before beginning to use KSP for educational purposes, there is a small amount of initial setup to do.

1. Install KSP to your disk from the distribution platform of your choice.
2. From the game's main menu, go to Settings and enable "Advanced Tweakables". This is a setting that allows for more granular control over gameplay elements both in flight and in vehicle construction via the right-click context menu.
3. Begin creating the save file you intend to use for instruction, under Start Game > Start New. If it is relevant to you, before you click "Start!", enable Plasma Blackout under Difficulty Options > Advanced. This setting makes robotic cores lose connection to ground control when flying through atmospheric plasma (i.e. upon planetary entry). If it is relevant to you, this is also where you can enable "Require Signal for Control", which requires a relay network to be set up between robotic spacecraft and ground control in order to maintain any sort of control over the spacecraft. These settings can also be enabled/disabled in-game.
4. Finish creating your save file and click "Start!".
5. Install [HyperEdit, by Kerbaltek](https://www.kerbaltek.com/hyperedit). Follow their installation instructions.

# How-to

## Editing orbits with HyperEdit

The ability to place an object in a particular orbit without having to take the time to launch it is a significant boon to educational effciciency. By being able to directly edit orbits, you will be able to build spacecraft without being concerned with the delivery method. Furthermore, this allows you to put any object in space, including structures that would otherwise be impractical. For this section, I will use "spacecraft" to mean "any object you can build in the VAB". Note that while this includes traditional definitions of spacecraft, it also includes anything that KSP allows you to launch from its launchpads.

To edit the orbital parameters of a spacecraft without launching:

1. Build a spacecraft in the VAB. Give the spacecraft a unique name. Click "Launch" to have KSP put the vehicle on the launchpad.
2. Open the HyperEdit menu, either by clicking the appropriate button, or using the keyboard shortcut (alt + H by default).
3. Click "Orbit Editor".
4. Select the spacecraft whose orbit you would like to adjust.
5. Ensure you are under the "Simple" tab. Altitude is in m. Set Altitude to 100,000. This clears Kerbin's atmosphere (which ends at 70,000 m altitude), while still remaining in low orbit. Notice how the Simple editor automatically places the spacecraft in an equatorial, circular orbit.
6. Use the Complex and/or Graphical tabs to adjust the remainder of your orbital parameters.

Note that the Orbit Editor function of HyperEdit allows you to adjust the orbits of any active bodies, including active spacecraft and celestial bodies. 
