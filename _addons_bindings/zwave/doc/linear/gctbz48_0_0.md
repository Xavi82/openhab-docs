---
layout: documentation
title: GoControl GC-TBZ48 - ZWave
---

{% include base.html %}

# GoControl GC-TBZ48 Z-Wave Plus Thermostat
This describes the Z-Wave device *GoControl GC-TBZ48*, manufactured by *Linear Corp* with the thing type UID of ```linear_gctbz48_00_000```.

The device is in the category of *HVAC*, defining Air condition devices, Fans.

![GoControl GC-TBZ48 product image](https://www.cd-jackson.com/zwave_device_uploads/622/622_default.jpg)


The GoControl GC-TBZ48 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

## Overview

The Z-Wave Thermostat (GC-TBZ48) is a programmable, Z-Wave communications thermostat. It can be powered using 24VAC (if both “R”&”C”wires are available at the thermostat), or using four (4) AA batteries. Using Z-Wave technology, end users have the ability to use the 2GIG Go!Control panel to control the thermostat, configure programming settings, as well as to display current conditions in the home or office.

### Inclusion Information

  1. Set your primary controller to Include, add or Install mode, to add the thermostat as a node on your network (see your controller’s user manual for detailed instructions).
  2. Press any button to take thermostat out of sleep mode.
  3. Press and hold FAN button for 5 seconds. SETUP will be displayed in the status display line.
  4. Scroll to “Z-Wave” using up/down buttons. Press SELECT.
  5. When prompted by your Z-Wave controller, Press the YES button in the Z-Wave Install screen.
  6. Press SELECT (mode button) to add thermostat to network.
  7. Display line should flash WAIT then SUCCESS if Z-Wave connection is made.
  8. If Z-Wave does not connect to controller, WAIT, then FAIL will flash in status display line.
  9. If thermostat fails to connect, repeat Steps three (3) through (7) to re-try connecting.

### Exclusion Information

  1. Set your primary controller to Include, add or Install mode, to add the thermostat as a node on your network (see your controller’s user manual for detailed instructions).
  2. Press any button to take thermostat out of sleep mode.
  3. Press and hold FAN button for 5 seconds. SETUP will be displayed in the status display line.
  4. Scroll to “Z-Wave” using up/down buttons. Press SELECT.
  5. When prompted by your Z-Wave controller, Press the YES button in the Z-Wave Install screen.
  6. Press SELECT (mode button) to add thermostat to network.
  7. Display line should fl ash WAIT then SUCCESS if Z-Wave connection is made.
  8. If Z-Wave does not connect to controller, WAIT, then FAIL will flash in status display line. 

## Channels

The following table summarises the channels available for the GoControl GC-TBZ48 -:

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|
| Scene Number | scene_number |  | Number | 
| Sensor (temperature) | sensor_temperature | Temperature | Number:Temperature | 
| Thermostat mode | thermostat_mode | Temperature | Number | 
| Operating State | thermostat_state | Temperature | Number | 
| Setpoint (cooling) | thermostat_setpoint | Temperature | Number:Temperature | 
| Setpoint (heating) | thermostat_setpoint | Temperature | Number:Temperature | 
| Thermostat fan mode | thermostat_fanmode |  |  | 
| Thermostat fan state | thermostat_fanstate |  |  | 
| Battery Level | battery-level | Battery | Number |
| Clock Time Offset | time_offset | Temperature | Number | 

### Scene Number
Triggers when a scene button is pressed.

The ```scene_number``` channel supports the ```Number``` item.

### Sensor (temperature)
Indicates the current temperature.

The ```sensor_temperature``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Thermostat mode
Sets the thermostat.

The ```thermostat_mode``` channel supports the ```Number``` item and is in the ```Temperature``` category.
The following state translation is provided for this channel to the ```Number``` item type -:

| Value | Label     |
|-------|-----------|
| 0 | Off |
| 1 | Heat |
| 2 | Cool |
| 3 | Auto |
| 4 | Aux Heat |
| 5 | Resume |
| 6 | Fan Only |
| 7 | Furnace |
| 8 | Dry Air |
| 9 | Moist Air |
| 10 | Auto Changeover |
| 11 | Heat Economy |
| 12 | Cool Economy |
| 13 | Away |

### Operating State
Sets the thermostat operating state.

The ```thermostat_state``` channel supports the ```Number``` item and is in the ```Temperature``` category.
The following state translation is provided for this channel to the ```Number``` item type -:

| Value | Label     |
|-------|-----------|
| 0 | Idle |
| 1 | Heating |
| 2 | Cooling |
| 3 | Fan Only |
| 4 | Pending Heat |
| 5 | Pending Cool |
| 6 | Vent / Economiser |

### Setpoint (cooling)
Sets the thermostat setpoint.

The ```thermostat_setpoint``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Setpoint (heating)
Sets the thermostat setpoint.

The ```thermostat_setpoint``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Thermostat fan mode
Channel type information on this channel is not found.

### Thermostat fan state
Channel type information on this channel is not found.

### Battery Level
Represents the battery level as a percentage (0-100%). Bindings for things supporting battery level in a different format (e.g. 4 levels) should convert to a percentage to provide a consistent battery level reading.

The ```battery-level``` channel supports the ```Number``` item and is in the ```Battery``` category.

### Clock Time Offset
Provides the current time difference for the devices time.

The ```time_offset``` channel supports the ```Number``` item and is in the ```Temperature``` category.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The GoControl GC-TBZ48 supports 3 association groups.

### Group 1: Group 1

Lifeline

Association group 1 supports 5 nodes.

### Group 2: Group 2


Association group 2 supports 5 nodes.

### Group 3: Group 3


Association group 3 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SCENE_ACTIVATION_V1| |
| COMMAND_CLASS_SCENE_ACTUATOR_CONF_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_THERMOSTAT_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_OPERATING_STATE_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_STATE_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_CLOCK_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_MULTI_CMD_V1| |

### Documentation Links

* [Product Manual](https://www.cd-jackson.com/zwave_device_uploads/622/GC-TBZ48-Install.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/622).