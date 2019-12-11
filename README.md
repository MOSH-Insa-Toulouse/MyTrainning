# My Trainning

My first project with KiCad...

## Here is my schema

![my_first_shield_sensor_board.png](docs\images\kicad_schematic.png)

## Here is my Arduino shield for my gas sensor

![my_first_shield_sensor_board.png](docs\images\my_first_shield_sensor_board.png)

## And a part of importante code

```c
/* on Arduino Uno */
#define T_REGENERATION_MS 2500 // 2.5 sec for regeneration delay
...
// somewhere in the state machine
if ( isRgazSensorSaturated() ) {
    setRregeneration(ON);
    delay(T_REGENERATION_MS) // wait for the necessary time, see https://www.arduino.cc/reference/en/#functions
}
...

```

## MIT license

![CC BY-SA 3.0 ](OSS-OSHW-logo.jpg)
