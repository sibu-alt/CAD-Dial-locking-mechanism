# CAD-Dial-locking-mechanism

This project is based on a fully 3d modelled dial locking mechanism. it has been designed to explore how rotational inputs can encode a combination of digits through mechanical sequencing. I chose this project because i wanted to explore something with kinematic complexity. 

### How it works
the dial mechanism is comprised of 3 wheels with a drive cam at the end. the drive cam has a drive shaft attached that connects to the spinning dial. a spindle, through which the drive shaft runs, is attached to the housing, and keeps the entire mechanism in place. the 3 wheels have the spindle and drive shaft running through them. each wheel has a drive pin and wheel fly, the drive cam only has a drive pin. The dial works by turning 3 times, then 2 then 1. The way this works is that the wheel closest to the drive cam has to be picked up first and aligned to the spindle. the next 2 spins are for the next wheel, it has to be spun twice because the 3rd wheel will move as well but the wheel we need to align with the spindle is the 2nd one, hence the 2 spins. Once the 2nd wheel is aligned the 3rd wheel will be aligned by the final spin. This will allow a flat spring known as the fence that is attached to the drive cam and goes above all the wheels will snap into small groves (wheel notch) that all of the 3 wheels have. In a complete locking system this will allow the lock to open (identifiable by a small click sound)

### Design decisions and trade-offs
* The spindle and rotating drive shaft had to be separate entities due to the need for an anchoring point for the system, which is the spindle.
* The notch positions where kept different as this difference is what creates the dial pin/code that opens the safe.
* The fence was created as a leaf spring for the sake of design simplicity and the need for simplicity instead of overcomplicated parts
* The spindle, drive shaft and dial have a tolerance of mm, this is for more secure fit as there shouldnt be too much room for possible wobbling. the spindle and wheels have tolerances of mm.
* The subtle changes made, which include the change from a coil spring to a flat leaf spring, the coil spring made the design more complicated, which adds to assembly intricacy. The spindle was made an anchor point instead of the driving shaft for stability and mechanism anchoring to the housing. The number of wheels where reduced from 5 to 3, the housing thickness would be too large with 5 wheels.

### Visuals

### Challenges

### Specs
* Software: Solidworks 2026
* Target materials:
* Manufacturing method: 






