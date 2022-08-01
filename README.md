# Water tank monitor system

## Motivation
For homes dependent on tank water it is crucial to be aware water consumption and remaining supply.

## Requirements
- At minimum monitor available water supply to improve water planning
- Installation should be as easy and non-invasive as possible
- Software integration preferably should include existing solution to avoid the need to develop custom solution
- Optionally monitor water flow and other metrics

## Research

### Possible options
**Sonic sensor**
The idea is to measure distance between water and top of the tank and thus calculate available water supply based on the tank dimensions. Widely used, cheap and realiable sensor with wide SW support. Requires mounting inside the water tank or through a hole. Data and power cable has to be ran from the controller to the sensor.

**Submersible pressure transmitter**
The idea is to use hydrostatic pressure to calculate water column height and thus calculate available water supply. Similar advantages like the sonic sensor, additional disadvantage is that the cable needs to be run to the bottom of the tank through the water. Calculation would need to be offset for the distance between the pipe outlet and bottom of the tank (unusable water).

**Threaded pressure transmitter**
Like submersible pressure transmitter it can be used to measure hydrostatic pressure. The main advantage is the it doesn't have to be mounted on or in the tank itself but anywhere on the pipe between the tank and the pump (obviously considering levels). Unless the pump is below the tank bottom no offset needs to be applied.

