---
layout: default
title: L01IS
nav_order: 1
parent: Error Codes
grand_parent: Technical Documentation
---

# L01IS

This error code occurs during the `InitializeSettings()` function in the launcher. An exception is accompanied with this error.

## Probable Causes

- **File permissions insufficient**

The application cannot access the settings file due to a lack of permission.

- **File Not Found**

The application cannot find the file in the filepath: `%appdata%\DiamondPG\StatsApp\settings.json`.
