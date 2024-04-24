---
layout: default
title: L04LF-A
nav_order: 1
parent: Error Codes
grand_parent: Technical Documentation
---

# L04LF-A - Error Setting Home Path
> Accompanied by an exception

Error occurs in the first section of the `Launch()` function. Error occurs when an invalid home team is selected. 

## Probable Causes

- Invalid File Name in `Home Team` dropdown box.

Can occur if the filename initially pulled for the dropdown box is not the same as the file in the `{Documents Folder}\StatsApp\Home Teams\` folder.

- File not found

Can occur if the selected home team file is no longer in the `{Documents Folder}\StatsApp\Home Teams\` folder.
