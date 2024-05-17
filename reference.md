# Introduction

This document will serve as reference material for instructors to make the best of KSP as an educational tool. As such, it will cover "technical" topics that are not relevant to a student's learning - e.g. creating objects and vehicles, editing orbits, etc. While it will highlight certain gameplay tricks or advanced mechanics to better your instruction, it is **not** intended to serve as a base tutorial on how to play the game. For that, I suggest either working through the game's built-in tutorials (found under Start Game > Training from the main menu), and/or taking time to actually play through the game yourself. This document will work under the assumption that you will be using the game's Sandbox mode, and that you will be using the plugin HyperEdit, unless otherwise specified. This document will also work under the assumption that you have enough working knowledge of spacecraft engineering and orbital mechanics to teach a middle or high school class on the topic.

# Setup

Before beginning to use KSP for educational purposes, there is a small amount of initial setup to do.

1. Install KSP to your disk from the distribution platform of your choice.
2. From the game's main menu, go to Settings and enable "Advanced Tweakables". This is a setting that allows for more granular control over gameplay elements both in flight and in vehicle construction via the right-click context menu. ![20240516202434_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/eb3608a1-1136-4a68-b52e-ab83b6a4735c)
3. Begin creating the save file you intend to use for instruction, under Start Game > Start New. If it is relevant to you, before you click "Start!", enable Plasma Blackout under Difficulty Options > Advanced. This setting makes robotic cores lose connection to ground control when flying through atmospheric plasma (i.e. upon planetary entry). If it is relevant to you, this is also where you can enable "Require Signal for Control", which requires a relay network to be set up between robotic spacecraft and ground control in order to maintain any sort of control over the spacecraft. These settings can also be enabled/disabled in-game. ![20240516202626_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/8bbe832b-ce3c-4771-ad6b-f7b3a3ea2b24)

4. Finish creating your save file and click "Start!".
5. Install [HyperEdit, by Kerbaltek](https://www.kerbaltek.com/hyperedit). Follow their installation instructions.




# How-to

## Editing orbits with HyperEdit

The ability to place an object in a particular orbit without having to take the time to launch it is a significant boon to educational effciciency. By being able to directly edit orbits, you will be able to build spacecraft without being concerned with the delivery method. Furthermore, this allows you to put any object in space, including structures that would otherwise be impractical. For this section, I will use "spacecraft" to mean "any object you can build in the VAB". Note that while this includes traditional definitions of spacecraft, it also includes anything that KSP allows you to launch from its launchpads.

To edit the orbital parameters of a spacecraft without launching:

1. Build a spacecraft in the VAB. Give the spacecraft a unique name. Click "Launch" to have KSP put the vehicle on the launchpad.
2. Open the HyperEdit menu, either by clicking the appropriate button, or using the keyboard shortcut (alt + H by default). ![20240516202809_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/ee78856f-9a26-4dd8-8e34-8a91cd31ac01)

3. Click "Orbit Editor".
4. Select the spacecraft whose orbit you would like to adjust. ![20240516203335_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/24467173-48d9-4a65-b7e0-326955471a97)

5. Ensure you are under the "Simple" tab. Altitude is in m. Set Altitude to 100,000. This clears Kerbin's atmosphere (which ends at 70,000 m altitude), while still remaining in low orbit. Notice how the Simple editor automatically places the spacecraft in an equatorial, circular orbit. ![20240516203927_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/705154ed-18e6-43a6-925b-e13d297166ea)

6. Use the Complex and/or Graphical tabs to adjust the remainder of your orbital parameters. If you are adjusting your spacecraft's velocity under the Velocity tab, note that directions are not "doubled up". For instance, if you wish to add 200 m/s in the retrograde direction, you must instead add -200 m/s in the prograde direction.

![20240516204009_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/2e7b1d35-d256-4d44-a0cc-5b9bf893c310)

![20240516205720_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/efea43d9-699d-45c2-98a6-d96db95b9449)


Note that the Orbit Editor function of HyperEdit allows you to adjust the orbits of any active bodies, including active spacecraft and celestial bodies. 

## Information on maneuvers SCREENSHOTS NEEDED

KSP has real-time information on maneuvers, including thrust-to-weight ratio (TWR), delta-V, and remaining firing time. If your spacecraft has engines and the required type of fuel, and if the spacecraft is configured correctly such that the engine is able to access the fuel reserves, then the game will be able to present this information to you. This information can be found in the bottom left while flying a spacecraft. The total delta-V remaining in the spacecraft, when combining all stages and taking into account stage separation, is the orange and white number in the bottom left, while blue delta-V numbers are the delta-V remaining for individual stages. Clicking any individual stage shows the Isp, thrust, TWR, and total burn time, for that stage. Clicking the bottommost, orange, total delta-V number expands this information for all stages.

![20240516204420_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/7504a368-d6b6-44b5-8f78-2058da79be8c)

![20240516204424_1](https://github.com/maxluo97/KerbalEDU-redux/assets/169619314/6abf5b57-a088-49b0-9825-95670c48b510)



Note that these values dynamcially change depending on flight conditions. For example, while an engine is active, a visual yellow/green indicator for remaining fuel will appear. Furthermore, the numbers shown for inactive engines, or for active engines whose throttle is at 0, assume full throttle; manually setting the throttle will dynamically change all of these values.

Some subtle knowledge must be developed to utilize this function to its fullest, especially regarding the flow of fuel and resources, and knowing which in-game items prevent or enable cross-flow.
