This repository shows how to detect Game's Menus during play.

It uses the differences between consecutive frames to detect if a large difference occurred.

For Star Craft, the following Menu Frames have been detected in the video attached:

<p align="center">
<img src="large_img_differences/large_img_diff_600.png" width=800 />
</p>

<p align="center">
<img src="large_img_differences/large_img_diff_358.png" width=800 />
</p>

To make the system more reliable, possible next steps would be:

- try it on other games
- when multiple menu frames have been detected, compare them with each other to see if they cluster together
- once the menus have been successfully validated, use the menus' template only