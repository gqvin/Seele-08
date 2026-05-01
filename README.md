# Seele-08
Upgraded 2WD Gantry for the Sovol SV08 (AWD coming soon!)

<img width="1664" height="603" alt="image" src="https://github.com/user-attachments/assets/09fbb4e4-c03b-444d-ad4d-3880cc7348ba" />

Uses a modified [Monolith](https://github.com/Monolith3D/Monolith_Gantry/tree/main) belt path by CloakedWayne.

## Benefits:
* Shorter belt path compared to stock (Higher Accelerations!)
* Lighter Gantry Parts
* Entirely pinned
* Double Shear (With Long Shaft Motors)
* Better Tensioner Design
* Only 3mm X loss and 2mm Y loss with stock toolhead (Reaches stock nozzle brush!)
* No new rails, extrusions, or belts needed!
* Better compatability with toolheads that mount probe under the X extrusion
* No need for dehubbed pulleys

## BOM:
| **Part** | **Qty** | **Store/Notes** | 
| :--- | :--- | :--- |
| Pin M5x30mm | 10 | | 
| Pin M5x22mm | 2 | | 
| GT2 20T 6mm Idler | 6 | At least 2 have to be genuine gates (the two in AB mounts) | 
| F695 Bearing | 18 | Can also harvest 8 smooth idlers off of stock gantry and only buy 2 |
| 10x5x1mm Shim | 10 | | 
| 10x5x0.5mm Shim | 12 | | 
| GT2 20T 6mm Pulley | 2 | | 
| Long Shaft Motors | 2 | Recommended LDO 42STH48 - 2504 | 
| M3 Hardware | n/a | Heat Sets, SHCS | 
| M4 Hardware | n/a | BHCS/SHCS, Nuts | 

## Printing:
Standard Voron Settings (4 Walls, 5 Top/Bottom Layers, 40% Gyroid/TMPS-D) <br/>
Front Idlers need supports. <br/>
Reaming for the pins may be needed. <br/>
It is recommended to print [Z-Belt Helpers](https://www.printables.com/model/927729-sovol-sv08-z-belt-helper) by Nadir as you will be swapping out the Z joints. <br/>
If you are reusing the stock toolhead, print the belt clips from this repository. <br/>
You need to print some sort of Z-Chain Relocation mod. I recommend and used [these](https://www.printables.com/model/1320159-sv08-under-gantry-cable-chain-mount-for-sovol-cabl). <br/>


## Acknowledgement: 
**CloakedWayne** for designing the original belt path that this gantry uses.

## Future Goals:
* 9mm Belt Support
* AWD Support
* Support for 2wd with stock motors

## Changes:
* 2wd 6mm release
* Stronger 2WD Idlers
* Changed tolerances significantly and allowed for more standard screw lengths
* I have a [printables project](https://www.printables.com/model/1706696-seele-08-sovol-sv08-gantry) too if one prefers 
<br/><br/><br/><br/>
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
