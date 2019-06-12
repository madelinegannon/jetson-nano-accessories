### Jetson Nano Tripod Mount
This Jetson Nano Tripod Mount lets you attach the Jetson Nano developer kit to any leg of a [Manfrotto 028B Tripod](https://www.manfrotto.us/black-triman-camera-tripod). Attaching the Nano to the tripod leg keeps the tripod head clear for cameras and other sensors, while keeping the computer close and mobile. This design takes advantage of the 028B's tapered, twin shanked leg — so you can easily snap on the printed tripod clips, and slide the assembly up the leg until you have a snug connection.

|  Tripod Mount (Overall) | Tripod Mount (Detail) |
| :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/images/jetson_nano_tripod-mount_overall.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/images/jetson_nano_tripod-mount_detail.png) |

## Components

| Nano Clip | Board Backer | Tripod Clips |
| :---: | :---: | :---: |
| ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clip_dimensions.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_board_backer_dimensions.png) | ![](https://github.com/madelinegannon/jetson-nano-builds/blob/master/images/jetson_nano_clips_tripod.png) |

## Parts List

| Item        | Qty           | Reference  |
| ------------- |:-------------:| -----:|
| Board Back | 1 | [jetson_nano_board.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_board.stl) |
| Nano Clip  | 2 | [jetson_nano_clip.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_clip.stl) |
| Nano Tripod Clips | 1 | [jetson_nano_clips_tripod.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_clips_tripod.stl) |


## Assembly Instructions

1. Print the [jetson_nano_board.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_board.stl),  [jetson_nano_clips_tripod.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_clips_tripod.stl), and two [jetson_nano_clip.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/garden-utility/jetson_nano_clip.stl) at 20% infill.
2. Slide the two Jetson Nano Clips into the front of the printed board (this should be a tight fiction fit). 
    - _Note: The front of the board has centered slots and a rougher finish._
3. Snap your Jetson Nano into the Clips — you should hear a nice click sound.
4. Slide the two Tripod Clips into the back of the printed board (this should be a tight fiction fit). 
    - The two Tripod Clips are slightly different widths to account for the taper of the tripod leg.
        - The wider clip goes in the top slot on the back of the board.
        - The narrower clip goes in the bottom slot on the back of the board.
    -  _Note: The back of the board has off-centered slots and a smoother finish._
5. Once the tripod clips are attached, position the clips over the middle of the leg, and then slide the assembly up the leg until you feel a snug fit. This should be around 2"- 3" from the top of the leg.
6. Plug in power, sensors and peripherals, and get going.

#### Printer Settings
Each of these parts were printed on a [Prusa i3 MK3S](https://www.prusa3d.com/original-prusa-i3-mk3/) printer using the MK3S_MK3_0.2_Fast profile (0.2mm layer height) with PLA. 

## Credits
1. The [Nano Clip](https://github.com/madelinegannon/jetson-nano-builds/blob/master/garden-utility/jetson_nano_clip.stl) was derived from this [8020 Rail ATMega2560 Clip](https://www.thingiverse.com/thing:155130) by [the_digital_dentist](https://www.thingiverse.com/the_digital_dentist/about).
