# Physics

Merely the name of it strikes fear in the hearts of students. Despite how bad it may seem, 
physics is still extremely important in understanding the laws that govern how your robot moves.
Whether you want to do physics simulation for a subsystem or get an idea of what the optimal performance 
for your robot looks like, physics is essential to know and get at least a tiny grasp on. 

## Basic Units
The fundamental units to everything, including FRC.
### Length ($m$)
Length is in essence a measurement of an "amount" of distance. Many attributes in robots rely on
the unit of length, such as velocity, force, etc.

Please standardize on meters.

Other common units: $in$, $cm$

### Mass ($kg$)
It's not the same as weight.

Mass is a measure of an object's inertia, or its *resistance to acceleration* when a force is applied. 
On Earth, mass and weight measurements are generally one and the same, but it's important to recognize
the differences in the meaning of each unit.

Other common units: $lb$

### Time ($s$)
The quantity of duration. This is everywhere in robot programs, from loop times to defining
velocity and acceleration. 

Other common units: $ms$

### Angle
Traditionally unitless. The easiest way to think about it is the proportion of a rotation. Lots
of mechanisms in robots are angular in nature, since motors output angular motion. Any unit is
fine, but standardize on one and *stick to it*.

Common units: degrees ($\degree$), radians, rotations

## WIP
categorize and explain and write in better terms later. add pics?
### Voltage ($V$)

### Current ($A$)

### Resistance ($\Omega$)

### Force ($N$)

### Moment of Inertia ($kg \cdot m^{2}$)

### Torque ($N \cdot m$)

## Why does this matter?

motors use current to output torque, which makes stuff move

elevators are torque on a pulley

having gearing on your mechanism multiplies torque and divides free speed by gear reduction 

having multiple motors driving a mechanism multiplies your available torque by the motor count 
at the expense of increased current draw, but doesn't affect free speed
