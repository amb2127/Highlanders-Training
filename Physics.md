# Physics

Merely the name of it strikes fear in the hearts of students. Despite how bad it may seem, 
physics is still extremely important in understanding the laws that govern how your robot moves.
Whether you want to do physics simulation for a subsystem or get an idea of what the optimal performance 
for your robot looks like, physics is essential to know and get at least a tiny grasp on. 

This document assumes you have basic understanding of SI prefixes and unit symbols.

# TODO: add pictures
## Fundamental Units
Doesn't cover everything possible, but this is most of what will be useful in FRC.

Please standardize on SI.
### The ones you already know
You should know most of these already, but a refresher is always helpful.
#### Time ($s$)
look at ur clock idk
<br>Also: $ms$
#### Distance ($m$)
Linear distance between two points of interest.
<br>Also: $in$, $cm$, $ft$
#### Mass ($kg$)
Not the same as weight! Technically measures resistance to force.
<br>Also: $lb$
#### Velocity ($m/s$)
Distance traveled over time.
<br>Also: $ft/s$
#### Acceleration ($m/s^2$)
Velocity's change over time. This is what motors directly control.
<br>Also: $ft/s^2$
#### Angle
This isn't really a unit? SI is weird. Pick one and stick with it.
Or use Rotation2d.
<br>Units: rotations, radians, degrees

### The other ones
#### Current ($A$)
Also called amperage, current is the flow of electrical charge through a space. 
If you imagine electricity as a bunch of tiny particles that move through a conductor, 
current measures their *rate of flow*. Currents create magnetic forces, which are 
used to drive motors.

#### Voltage ($V$)
Comes in many names, such as electric potential, electric pressure, or
electric tension, but it's most commonly called voltage. Voltage is an extremely
complicated topic, but for our purposes, picture it as a pressure that "pushes"
current through a conductor.

#### Resistance ($\Omega$)
Electrical resistance measures the opposition to current flow. Conceptually,
electric resistance is very similar to mechanical friction. Essentially all objects
have some level of electrical resistance, the difference between an electrical
conductor and an insulator is simply how *much* resistance there is. Nominally, the
resistance in an FRC battery is about $20 m\Omega$.

#### Ohm's Law
Unsurprisingly, the last 3 units are all directly related to each other. Essentially,
voltage induces current through a resistance. This is all neatly modelled via Ohm's law,
an equation that states:
$$I = V/R$$
where $I$ is current, $V$ is voltage, and $R$ is resistance. This equation can be represented
many other ways, such as $V = IR$. Use the one that best suits your needs.

#### Power ($W$)


## Understanding DC Motors
Electric motors convert **electrical energy** into **mechanical energy**.
