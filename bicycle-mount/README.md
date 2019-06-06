### Jetson Nano Bicyle Mount
The Jetson Nano is lightweight and power-efficient, which means you can easily take it on the go. This Bicyle Mount assembly allows you to hang a Jetson Nano Developer Kit and Portable Battery from the horizontal crossbar of your bike. It also lets you attach sensors, cameras, or projectors to your handlebars using a standard 1/4-20 screw. Combine the two, and you'll have a number of ways to creatively enhance your daily commute.

Here's a few project ideas to get started:
- Detect potholes and other hazards at night using an IR camera.
- Change the colors of LED lights on your bike based on proximity.
- Create a 3D map of your commute.
- Attach a pico projector to add dynamic visuals to your night ride.

> The Jetson Nano is not waterproof, so use on a sunny day :)

<img src="" width="600">

## Parts List

| Item        | Qty           | Reference  |
| ------------- |:-------------:| -----:|
| Board Back | 1 | [jetson_nano_board.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/bicycle-mount/jetson_nano_board.stl) |
| Nano Clip  | 2 | [jetson_nano_clip.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/bicycle-mount/jetson_nano_clip.stl) |
| Bicyle Clip | 2 | [jetson_nano_clip_bicycle.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/car-mount/jetson_nano_bicycle.stl) |
| Bicyle Sensor Clip | 1 | [jetson_nano_clip_bicycle_sensor.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/car-mount/jetson_nano_bicycle_sensor.stl) |
| M3x8 screw | 2 | [Assorted Screw Set](https://www.amazon.com/VIGRUE-1080pcs-Assortment-Kit-Wrenches/dp/B07FCDL2SY/) |
| M3 nut | 2 | [Assorted Screw Set](https://www.amazon.com/VIGRUE-1080pcs-Assortment-Kit-Wrenches/dp/B07FCDL2SY/) |
| 1/4-20 x 1" screw | 1 | [1/4-20 Screw Assortment](https://www.amazon.com/iExcell-4-20UNC-Stainless-Internal-Drives/dp/B07C9MWCSP/) |
| Portable Battery | 1 | [INUI Power Bank](https://www.amazon.com/INIU-Portable-External-Powerbank-Compatible/dp/B07H6LB4J4/) |


## Assembly Instructions

1. Print the [jetson_nano_board.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/tripod-mount/jetson_nano_board.stl), two [jetson_nano_clip.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/garden-utility/jetson_nano_clip.stl), and two [jetson_nano_clip_bicycle.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/car-mount/jetson_nano_bicycle.stl) at 20% infill. Print one [jetson_nano_clip_bicycle_sensor.stl](https://github.com/madelinegannon/jetson-nano-builds/blob/master/car-mount/jetson_nano_bicycle_sensor.stl) at 10% infill.
2. Slide the two Jetson Nano Clips into the front of the printed board (this should be a tight fiction fit). 
    - _Note: The front of the board has centered slots and a rougher finish._
3. Snap your Jetson Nano into the Clips — you should hear a nice click sound.
4. Slide each of the Bicylce Clips into the back of the printed board (this should be a tight fiction fit). 
    - _Note: The back of the board has off-centered slots and a smoother finish._
5. Snap your Portable Battery into the back of the Bicycle Clips, and plug in the Nano and other peripherals.
6. Use the hooks of the Bicyle clips to hang the whole assembly from the horizontal crossbar of your bike.
    - The hooks were designed for a 1" diameter crossbar.
    - If you find your Nano assembly is sliding forwards and backwards, add a zip tie before the first clip and after the last clip on your crossbar — these zip ties will act as stoppers. 
7. Snap the Bicyle Sensor Clip around a handlebar of your bike.
    - Push the clip around the handlebar, with the hexagonal holes facing up and towards the bike seat. It should take some force to it on; but once on, the clip should be slightly loose around the handle bars.
    - The intrerior diameter of the Sensor Clip is just under 1" (23mm). However, the clips will fit larger diameter handlebars — you'll just need longer M3 screws.
8. Push two M3 nuts into the hexagonal holes on the Sensor Clip (these should be a tight fiction fit).
9. Screw two M3x8 screws from the bottom of the clip, through the M3 nuts. Tighten the two screws until the clip no longer slides or rotates.
10. Use the 1/4-20 x 1" screw to attach any number of sensors, cameras, or projectors to your handlebars.
11. Start pedalling and go!

#### Printer Settings
Each of these parts were printed on a [Prusa i3 MK3S](https://www.prusa3d.com/original-prusa-i3-mk3/) printer using the MK3S_MK3_0.2_Fast profile (0.2mm layer height) with PLA. 

## Credits
1. The [Nano Clip](https://github.com/madelinegannon/jetson-nano-builds/blob/master/garden-utility/jetson_nano_clip.stl) was derived from this [8020 Rail ATMega2560 Clip](https://www.thingiverse.com/thing:155130) by [the_digital_dentist](https://www.thingiverse.com/the_digital_dentist/about).
