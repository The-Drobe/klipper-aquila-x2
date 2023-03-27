# ReadMe
## Prusa Slicer Config:
```
# start gcode
M109 S0
M190 S0
start_print EXTRUDER_TEMP={first_layer_temperature[initial_extruder]} BED_TEMP={first_layer_bed_temperature[initial_extruder]}
```

```
# end gcode
END_PRINT
```

Followed this guide to setup klipper:
[guide](https://www.youtube.com/watch?v=a6ru0mH3F8M)

additional applications: 

[mooncord](https://github.com/eliteSchwein/mooncord)
