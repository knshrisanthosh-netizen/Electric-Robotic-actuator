# Electric-Robotic-actuator

# Actuator 0.1

A compact BLDC motor actuator with an integrated planetary gearbox.

## Project Overview

Actuator 0.1 combines a BLDC motor and a planetary reduction gearbox into a compact mechanical assembly. The design is intended for robotic applications that require controlled rotation, torque multiplication, and a compact drive unit.

## Motor Specifications

| Parameter | Specification |
|---|---|
| Motor type | BLDC |
| Motor KV rating | 100 KV |
| Maximum phase current | 58 A |
| Gear reduction ratio | 6:1 |

 ## Material Specifications

| Component | Material |
|---|---|
| Rotor | Aluminium 7075 (Al7075) |
| Shaft | Steel |
| Planetary gears | Steel |
| Outer frame / Housing | Aluminium 7075 (Al7075) |

## Surface Finish

| Component | Surface Treatment |
|---|---|
| Aluminium components | Black anodising |
| Steel components | Blackening |

The aluminium components feature a black anodised finish, while the steel components use a blackened surface finish.

## Manufacturing and Assembly

- Aluminium 7075 is used for the rotor and outer frame.
- Steel is used for the shaft and planetary gears.
- Aluminium parts receive black anodising.
- Steel parts receive blackening.


## Gearbox Specifications

| Parameter | Specification |
|---|---|
| Gearbox type | Planetary |
| Reduction ratio | 6:1 | backlash 0.07mm |

The planetary gearbox reduces motor speed and increases output torque. Actual output torque and speed depend on motor operating conditions and gearbox efficiency.

## Theoretical Speed Calculation

Motor speed is estimated using:

`Motor RPM = KV × Supply Voltage`

Gearbox output speed:

`Output RPM = Motor RPM / 6`

, at 24 V:

- Theoretical motor no-load speed: 2,400 RPM
- Theoretical gearbox output speed: 400 RPM

Actual speed will vary with load, voltage, and losses.

## Mechanical Assembly

The STEP assembly contains the following named components:

| Component | Description |
|---|---|
| Assembly | Complete actuator assembly |
| 8115 FL Stator | Motor stator |
| 8115 FL Magnet Ring | Motor magnet ring |
| planet | Planetary gear component |


## CAD Files

- `Actuator0.1-Assembly.step` — 3D mechanical assembly.
 

## Project Status

**Version:** 0.1  
**Status:** under development

## Disclaimer

The specifications listed here are the currently provided design values. Continuous current, torque, efficiency, thermal limits, and rated operating speed have not yet been established through testing.
