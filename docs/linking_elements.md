---
title: Linking elements
layout: default
nav_order: 4
---

## Linking elements

### Links to content

This section is about creating links to content.

#### External

Example: https://www.meteo.pl/
 
[Weather forecast](https://www.meteo.pl/ "click here")

#### Internal

Link to file example: [additional information](reference.md "click here")

### Images

#### External

![random image](https://picsum.photos/100 "random picture")

#### Internal

Note: There can be no spaces in file paths and names.
 
 
![bread](Easy_white_bread.jpg "jpg directly in repository")

Bad practice:
 
when trying to add picture from outside the repository:  
\!\[jpg_with_path_outside_repository](../../../Desktop/Z_pulpitu/swans.jpg)  
picture can't be shown:  
![jpg_with_path_outside_repository](../../../Desktop/Z_pulpitu/swans.jpg)  

Good practice:
![path_within_repository](../images/swans.jpg "jpg inside repository folder")