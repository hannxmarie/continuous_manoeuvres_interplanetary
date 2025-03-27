## Continuous Manoeuvres: Interplanetary Trajectory from Earth to Mars

Code for NASA's General Mission Analysis Tool (GMAT)

Spacecraft: Human Mars Lander (HML)
Transfer method: Orbit Raising

## Design Requirements
• The HML shall undergo an interplanetary transfer from Earth to Mars.

• The HML shall arrive in the Martian orbit before MAVERIC does on the 19th of June 2040.

## Assumptions
• Once the HML-SM leaves the sphere of influence of Earth, it is considered to be in a heliocentric orbit.

• The time of transfer to get to Mars orbit, would be comparable to time of transfer to the MAVERIC orbit from Earth.

## Mathematical Models, Implementation and Software

For the mission sequence, the HML-SM propagates to orbit perigee, where the first finite burn
starts, with a varied burn time, and stops when the HML-SM achieves an apogee raise equal to the
Earths sphere of influence. The HML-SM then propagates to Earth orbit
perihelion, where the second finite burn starts with varied start time and burn time, and stops when
the HML-SM achieves an aphelion raise equal to the orbit of Mars around the Sun. 

Further logic will to either calculate the launch date by working out the lead angle of Mars compared
to Earth around the Sun. Or, by using the vary date capability within GMAT and targeting the sphere
of influence around Mars. From here, the HML-SM will undergo another finite burn at the sphere of
influence Mars boarder to then capture into a Mars orbit and reduce the apoapsis to match the
MAVERIC orbit apoapsis or use aerobreaking around Mars.

## GMAT Script Results

![image](https://github.com/user-attachments/assets/73de4115-1a9b-46da-b6ca-af6b251e2830)

Figure 1. GMAT Results of Apogee Raise for Electrical Solution
