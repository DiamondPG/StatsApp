---
layout: default
title: Getting Started
nav_order: 1
parent: Basketball
---

# Getting Started

In order to get started you must have StatsApp installed to your computer. You can install the program using instructions from [here](https://diamondpg.github.io/StatsApp/docs/Installation.html).

## File Setup
When the program is installed it creates a folder named `StatsApp` in your documents folder. This folder contains all of the teams added to the Player Repo. For information on creating your own team files, please refer here.

> To add to the player repo, please open a ticket here. 

> For instructions on creating your own team files, see here.

To get started, open the shortcut that was created on your desktop or open `Launcher.exe`.

Click on the first button, labeled "Away Team". This will prompt the user to select a team file in the `Away Team` directory. Currently, files are saved as `.csv` files. Once selected, the file name will appear above the button. 

In the `Sport` dropdown box, select basketball.
(Image here)


{: .opaque }
<div markdown="block">
{: .note }
This is currently the only option.
</div>

In the Home Team dropdown box, select a home team file that was either bundled with the application or one you created.

Click launch. 

If prompted, the user may need to enter a product key. Currently, this is only reserved for pre-release versions.

## Setting up the overlay

{: .note }
The following is the hardware required for the recommended method to set up the overlay:
- Streaming computer (Desktop/Laptop, Any OS)
- Separate Stat-keeping computer (Laptop Recommended, Windows)
- HDMI cable to link Stat-keeping overlay to stream computer. 
- Capture card (Elgato Cam-Link Recommended)
- Video Output on Stat-keeping computer (USB -> HDMI, USB Hub, Built-in HDMI, Etc.)


1. The recommended way to set up the overlay to show on stream begins with installing Open Broadcaster Software on the stat-keeping laptop. 

{: .note }
OBS will not be used as a streaming source, but rather an intuitive way to layout the overlay. 

2. In OBS, create a new window capture. 

3. Select the overlay window and center it in the frame. 

4. Plug in your HDMI cable into the output of the statkeeping laptop into the cam-link plugged into the streaming computer.

5. Right-Click the program frame on the Stat-keeping computer, click `Fullscreen Program` and select the second screen.

6. On the streaming computer, add a video capture device, 

7. Under filters, add a new chroma key. The green background of the overlay should go away.

8. Place the overlay over top of the main source or use a plugin called "Downstream Keyer" so that the source can go on top of every other scene
