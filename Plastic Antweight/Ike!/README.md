# Ike!

This is a toob-style robot designed for plastic antweight competitions.  Movement is caused via torque reactions of the wheels, which also drives the full-body drum.

## Materials:
- Overture TPU (wheels/tire)
- Overture Super PLA+ (everything else)

## Electronics:
- RR 2822 V2 1100KV (2x)  
- 35A ESCs (2x)
- Fingertech Switch
- 300 mAh 4s LiHV Lipo
- RR PDB
- RR 5V BEC

## Recommendations:
### Printing:
- Drum and wheels should be printed solid.
- For wheel hub attachment, reference this [video](https://youtu.be/Sbjdw8U07D4) for the slicer setup process.
- Tolerances are built-in, but may need adjustment for your printer if it is not well-tuned.
### Electronics:
- Enable bidirectional control and breaking on ESCs (should not have to worry about overheating, will allow for reduced throttle saturation).
- Use SHCS screws to mount motors to increase available thermal mass.
- Ensure wiring length for one motor is enough to slide entire core our without desoldering motor.
### Maintenance:
- Using an extended bit, you should be able to remove a motor/mount/wheel assembly directly to access the core without additional disassembly (changing a battery should take 8 screws.
- Treat screws as disposable. A stripped screw in the drum is a very bad day.
- All screw locations are designed to be M3, with the exception of the wheel hubs as the 2822 does not use M3 face mounts.
