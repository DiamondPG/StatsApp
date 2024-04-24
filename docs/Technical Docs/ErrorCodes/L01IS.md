---
layout: default
title: L01IS - Error during settings initialization
nav_order: 1
parent: Error Codes
---

# L01IS

This error code shows up during the `InitializeSettings()` function in the launcher. An exception is accompanied with this error.

## Probable Causes

- File permissions insufficient
The application cannot access the settings file due to a lack of permission.

- File Not Found
The application cannot find the file inthe filepath: `%appdata%\DiamondPG\StatsApp\settings.json`.
