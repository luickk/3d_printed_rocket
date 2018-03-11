
# 3D Printed self stabilizing rocket

This rocket is built to start and land all by itself. The landing manouver is done by tilting the fins on the upper part of the rocket, in order to slowly tilt the rocket till it's horizontal to decrease the fall speed .

![complete rocket](http://mrgrimod.de/FILES/1.png)

![rocket main parts ](http://mrgrimod.de/FILES/2.png)

![rocket scheme](http://mrgrimod.de/FILES/3.png)

![rocket sim](http://mrgrimod.de/FILES/4.png)

# Data


weights

----------
| weights_rocket_body | weights_rocket_parts|
|----------------|-------------------------------|
|rckt_stage_1	`60g`| rckt_wings  `26*4g`        |
|rckt_stage_2	`60g`| rckt_fins  `15*4g`       	|
|rckt_nosecone	`22g`| rckt_tech_holder `20g`|
|sum	`142g`| rckt_battery `20g`|
|| rckt_servo `4*10g`|
|| sum  `244g`| |

rocket stats

----------

> **motor**:               D9, 20 Ns
> **diameter**:          5 cm
> **inner diameter**: 4.7 cm
> **flight height**:     180 m
> **weight**: 512 g
> **parachute size**: 100 cm with 3.5 mps


# Idea

The goal is to start and land a rocket while not using a parachute ejection system to land the rocket. To acomplish that, the rocket has wings mounted to it s center of gravity. When it launches and reaches its point of max altitude it will eject the nosecone to lower the point of gravity. Then it will fall with the center of the gravity (wings) downwards so the rocket can be brought in the horizontal by tilting the rocket fins.

# Files

> .stl standard files used for 3D printing and 3D modeling <br>
> .ork Files for the [rocket simulation program](http://openrocket.info/)
