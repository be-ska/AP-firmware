# AP-firmware
ArduPilot firmwares for Align AP3 and AP5 Autopilots

## Release notes - Copter and Plane
### Version 0.2.4
1. Add hwdef for AP3 installed in MT622 and default parameter file
1. Add Sprayer soft stop functionality to comply with M6T22 hardware
1. Add Tools for parameter manipulation

### Version 0.2.3
1. Add hwdef for AP5 (3 IMUs)
1. Add hwdef for embedding parameters and scripts to M460 AP3/AP5
1. Change waf script to build ArduPlane (Support PCU protocol)

### Version 0.2.1
1. Add 360 LiDAR N10P driver

### Version 0.2.0
1. Port to ArduPilot 4.4.0

## Release notes - Rover
### Version 1.0.0 - RELEASE
1. add GA22 hardware definition and embedded scripts
1. fix failsafe parameters: HOLD mode

### Version 0.1.7
1. Improve navigation controller to achieve smoother pivot turn
1. Update GA22 default parameters

### Version 0.1.6
1. Bug fix: can't configure GPS if rover startup armed, add script `gps_config` to configure GPS at first boot

### Version 0.1.5
1. Change default parameters for GA22
1. Don't require arming
1. Add `set_home` script to use RC channel change to set home

### Version 0.1.4
1. Fix `GA22_engine` script

### Version 0.1.3
1. Change GA22 default parameter: FS_ACTION 1
1. Update script `blade_distance`

### Version 0.1.2
1. Implementation of CRUISE mode (cruise control)

### Version 0.1.1
1. Add support for AP3 and AP5
1. Add script and parameters for GA22
1. add different WPNAV parameters based on next WP distance 
