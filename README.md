# Control of a 3D Quadrotor Drone


## Scenario 1

- Goal: Keep at the same position, and not fall down to the ground
- Approach: Tuned the mass to actual mass (=0.5) and gave the same force as the gravity does

<p align="center">
<img src="./video/scenario1.gif" width=400>
</p>

```
PASS: ABS(Quad.PosFollowErr) was less than 0.500000 for at least 0.800000 seconds
```

## Scenario 2 

- Goal: Stop vehicle's rolling by 
    - controlling the veichle's rotation (omega.x) to be 0
    - controlling the vehicle's angle (roll) to be 0 
- Approach: set roll-pitch controller and body-rate controller
    

<p align="center">
<img src="./video/scenario2.gif" width=400>
</p>

```
PASS: ABS(Quad.Roll) was less than 0.025000 for at least 0.750000 seconds
PASS: ABS(Quad.Omega.X) was less than 2.500000 for at least 0.750000 seconds
```

## Scenario 3

<p align="center">
<img src="./video/scenario3.gif" width=400>
</p>

```
PASS: ABS(Quad1.Pos.X) was less than 0.100000 for at least 1.250000 seconds
PASS: ABS(Quad2.Pos.X) was less than 0.100000 for at least 1.250000 seconds
PASS: ABS(Quad2.Yaw) was less than 0.100000 for at least 1.000000 seconds
```

## Scenario 4



## Scenario 5






