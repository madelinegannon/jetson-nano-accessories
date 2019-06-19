### Jetson Nano Accessories
A variety of 3D printed mounts, adapters, and kits for NVIDIA's Jetson Nano.

<img src="https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_stand_battery.gif" width=400 align=left>

## Overview

NVIDIA sent me a few of their new Jetson Nanos to play around and see what I might want to make. On first impression — the Nano is a solid Ubuntu computer, but I was really impressed with its portablity: if you look at their [Jetbot](https://github.com/NVIDIA-AI-IOT/jetbot) project, you can see that you can power the Nano plus a few motors with just a mobile phone charger. So that got me thinking about all the different — _and weird_ — places I could take a Nano ... and that led to me daydreaming about possible projects with this portable, powerful embedded computer.

To jumpstart my creativity, I decided to make a series of mounts, adapters, and kits for taking the Nano, a battery, and a camera into a bunch of different places. Some of them are pragmatic and useful — like the [Tripod Mount Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/). Others are a bit more odd and fun — like the [Utility Belt](https://github.com/madelinegannon/jetson-nano-builds/blob/master/utility-belt/) or [Gardening](https://github.com/madelinegannon/jetson-nano-builds/blob/master/gardening/) Kits.

I've included all the files to make and modify these 3D printable accessories in this repo. These kits let you attach the Nano to things like:
- Glass, with the [Suction Cup Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/suction-cup-mount/)
- Metal, with the [Magnet Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/magnetic-mount/)
- Tripods, with the [Tripod Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/)
- The Body, with the [Utility Belt Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/utility-belt/)
- A Bike, with the [Bicycle Mount Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/bicycle-mount/)
- The Ground, with the [Gardening Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/gardening/)

| Suction Cup Kit | Magnet Kit | Tripod Kit | 
| :---: | :---: | :---: | 
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/suction-cup-mount/images/jetson_nano_suction-cup-mount_detail.png) |  ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/magnetic-mount/images/jetson_nano_magnetic-mount_detail.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/images/jetson_nano_tripod-mount_overall.png) |

| Utility Belt | Bicycle Mount | Gardening Kit |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/utility-belt/images/jetson_nano_utility-belt_detail.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/bicycle-mount/images/jetson_nano_bicycle-mount_overall.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/gardening/images/jetson_nano_outdoors_stake.png) |


Plus I made a few stands for holding, displaying, or extending the Nano:

- [Nano Stand](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/)
- [Nano Stand with Battery Clip](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/)
- [Nano Stand with Battery Clip and Extruded Aluminium Extensions](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/)

| Nano Stand | Nano Stand with Battery | Nano Stand with Battery and Extruded Aluminum |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/images/jetson_nano_clip-feet_cropped.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_stand_battery.gif) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/images/jetson_nano_sketch-recognition-rig.png) | 

## Modular Clip System
<img src="https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_assembly.gif" width="600" align=right>

My goal for these accessories was to have a kit of swapple, quick-to-print parts, so I could mix-and-match different clips, adapters, and mounts on the fly.

So, for example, over the course of my day, I could snap a Nano into the [Bicycle Mount Kit](https://github.com/madelinegannon/jetson-nano-builds/tree/master/bicycle-mount) for my commute to work, then snap it into a [Stand](https://github.com/madelinegannon/jetson-nano-builds/tree/master/stands) that's sitting on your workstation, and then maybe put my Nano on my [Refrigerator](https://github.com/madelinegannon/jetson-nano-builds/tree/master/magnetic-mount) or in my [Garden](https://github.com/madelinegannon/jetson-nano-builds/tree/master/garden-stake) when I got back home.  

### Components
The three basic components are a _Nano Clip_, that the Jetson Nano Developer Kit snaps into, a _Board Backer_, that protects the back of the Nano and has slots for the Nano and Battery Clips, and a _Battery Clip_, that a portable battery pack snaps into. Based on your scenario, you may or may need battery power — so there are other connection options for the rear slots in the Board Backer (e.g., [Suction Cups](https://github.com/madelinegannon/jetson-nano-builds/tree/master/suction-cup-mount)).

| Nano Clip | Board Backer | Battery Clip |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clip_dimensions.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_board_backer_dimensions.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clip_battery_dimensions.png) |
| [jetson_nano_clip.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/suction-cup-mount/jetson_nano_clip.stl) | [nano_board_backer.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/suction-cup-mount/jetson_nano_board.stl) | [jetson_nano_clip_battery.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/magnetic-mount/jetson_nano_clip_battery.stl) |

### Board Backer
The _Board Backer_ features slots for attaching the _Nano Clip_ and _Battery Clip_, as well as a series of holes for tip ties.

<p float="center">
<img src="https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_board_backer_details.png" width="425" align=center>
<img src="https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_assembly_side.png" width="425" align=center>
</p>

### Additional Clips
Here are a few more clips for the rear of the Board Backer that connect your Nano to different things:

| Bicycle Clips | Suction Cup Clips | Tripod Clips |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clip_bicycle.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clip_suction-cup.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clips_tripod.png) |
| See the [Bicycle Mount Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/bicycle-mount/) | See the [Suction Cup Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/suction-cup-mount/) | See the [Tripod Mount Kit](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/) |

### Stands
If you just want to show off your Nano in your workspace, I also made a few self-supporting stands that you can print.

| Jetson Nano Stand | Stand with Battery Clip | Stand with Battery Clip and Extruded Aluminium |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_stand.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_stand_battery.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_stand_battery_rail.png) |
| [jetson_nano_clip-feet.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/jetson_nano_clip-feet.stl) | [jetson_nano_clip-feet-battery.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/jetson_nano_clip-feet-battery.stl) | [jetson_nano_clip-feet-battery-rail.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/stands/jetson_nano_clip-feet-battery-rail.stl) |


#### Build Settings
Each of included models were printed on a [Prusa i3 MK3S](https://www.prusa3d.com/original-prusa-i3-mk3/) printer. All my build settings are detail in the instructions for each assembly, but keep in mind that your settings and tolerances may vary based on the printer and printing method you use.
