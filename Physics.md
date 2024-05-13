# Physics

Merely the name of it strikes fear in the hearts of students. Despite how bad it may seem, 
physics is still extremely important in understanding the laws that govern how your robot moves.
Whether you want to do physics simulation for a subsystem or get an idea of what the optimal performance 
for your robot looks like, physics is essential to know and get at least a tiny grasp on. 

## Fundamental Units
Doesn't cover everything possible, but this is most of what will be useful in FRC.

Please standardize on SI.
### The ones you already know
You should know most of these already, but a refresher is always helpful.
#### Time ($s$)
Also: $ms$
#### Distance ($m$)
Also: $in$, $cm$, $ft$
#### Mass ($kg$)
Also: $lb$
#### Velocity ($m/s$)
Also: $ft/s$
#### Acceleration ($m/s^2$)
Also: $ft/s^2$
#### Angle
This isn't really a unit? SI is weird. Pick one and stick with it.
Units: rotations, radians, degrees

## Why does this matter?

motors use current to output torque, which makes stuff move

elevators are torque on a pulley

having gearing on your mechanism multiplies torque and divides free speed by gear reduction 

having multiple motors driving a mechanism multiplies your available torque by the motor count 
at the expense of increased current draw, but doesn't affect free speed
