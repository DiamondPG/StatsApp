---
layout: default
title: Using The Dashboard
nav_order: 2
parent: Basketball
---

# Using the Dashboard

When you first look at the dashboard, it may look very confusing. Let's break it down.

## The Players

On the left and right side of the dashboard window are the lists of players. These contain all of the players from the teams selected in the launcher window. These players are displayed alongside their statistics in the current game. These statistics will be updated as you use the dashboard. 

## The Best Players

In the middle of the screen is a wall of text containing the best players in that respective stat. The top row being the highest scorers (People who score the most points) for each team. Each cell updates as you keep score and statistics. 

## The Score and Team Names

At the top of the middle section is the cumulative score of both teams. This score can be used to easily check if you have missed something on the court or just as a reference for how bad the other team is losing (knock on wood). The team names are associated with their half of the screen and can be edited in the `Edit` menu.

## Show Animation Checkbox and Refresh Stats Button

The Show Animation checkbox is for enabling or disabling the dropdown animation on the overlay window. The primary use case for this function is for fixing stats when you accidentally put in the wrong stat.

The Refresh Stats button is there for the rare occasion when the application doesn't update the UI. When this button is clicked, it will not trigger a dropdown on the overlay menu, it is ONLY for refreshing the dashboard.

## Keeping Stats

It is now time to do what the application was designed for. Let's keep some stats! 

{: .warning }
There is currently a bug where an item has to be selected in one of the player lists in order to use a keybind. A [patch](https://github.com/DiamondPG/StatsApp/issues/8) is planned to be rolled out with the next update.

Stats are kept using a keybind system. this allows for fast entry and a relatively low amount of stress for the stat-keeper. Keybinds can be edited in the `Edit` menu.

When one of the keybinds is pressed, a window will pop-up where you can enter the player identifier. The player identifier is a combination of the player's team and the player's number. 

{: .note }
The player identifier must be written in the following format: `a12` OR `h34`. These identifiers mean "Away Team #12" and "Home Team #34" respectively.

Once the player identifier is entered, the stat will be entered into the player's stats. As long as the `Show Animation` checkbox is checked, an animation will show on the overlay window.

## Default Keybinds

`F1`: Add a Point

`F2`: Add 2 Points

`F3`: Add 3 Points

`F4`: Add Foul
