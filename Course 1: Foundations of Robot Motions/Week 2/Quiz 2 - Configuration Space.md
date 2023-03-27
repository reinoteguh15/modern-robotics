1. The tip coordinates for the two-link planar 2R robot of figure below are given by
    $$x = cos θ_1 + 2 cos(θ_1 + θ_2)$$
    $$y = sin θ_1 + 2 sin(θ_1 + θ_2)$$
    (In other words, link 1 has length 1 and link 2 has length 2.)  The joint angles have no limits. \
    ![ ](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Kd9_WNicEeebHwrXRRPVgA_36facc5fc846d72ea5487187a9e64679_ex01-01.jpg?expiry=1680048000000&hmac=TLmFPrH14Kop7MmvqpdPcddrjbrggxd3g6tg5hTWV6Q)
    Which of the following best describes the shape of the robot's workspace (the set of locations the endpoint can reach)?
    - [ ] A circle and its interior
    - [ ] A circle only (not including the interior)
    - [x] Annulus or ring (the area between two concentric bounding circles)

2.  The chassis of a mobile robot moving on a flat surface can be considered as a planar rigid body.  Assume that the chassis is circular, and the mobile robot moves in a square room.  Which of the following could be a mathematical description of the C-space of the chassis while it is confined to the room? (See Chapter 2.3.1 for related discussion.)
    - [x] $[a,b] × [a,b] × S^1$
    - [ ] $[a,b] × ℝ^1 × S^1$
    - [ ] $[a,b] × [a,b] × ℝ^1$
    - [ ] $ℝ^2 × S^1$

3. Which of the following is a possible mathematical description of the C-space of a rigid body in 3-dimensional space? 
    - [ ] $ℝ^3 × S^3$
    - [ ] $ℝ^3 × T^3$
    - [ ] $ℝ^3 × T^2 × S^1$
    - [x] $ℝ^3 × S^2 × S^1$

4. A spacecraft is a free-flying rigid body with a 7R arm mounted on it.  The joints have no joint limits. Give a mathematical description of the C-space of this system.  (See Chapter 2.3.1 for related discussion.)
    - [ ] $ℝ^3 × T^10$
    - [x] $ℝ^3 × S^2 × T^8$
    - [ ] $ℝ^3 × S^3 × T^7$
    - [ ] $ℝ^4 × S^2 × T^7$

5. A mobile robot is moving on an infinite plane with an RPR robot arm mounted on it. The prismatic joint has joint limits, but the revolute joints do not. Give a mathematical description of the C-space of the chassis (which can rotate and translate in the plane) plus the robot arm.  (See Chapter 2.3.1 for related discussion.)
    - [ ] $ℝ^2 × S^2 × S^1 × [a,b]$
    - [ ] $ℝ^2 × S^3 × [a,b]$
    - [x] $ℝ^2 × T^3 × [a,b]$
    - [ ] $ℝ^3 × T^3$

6. Determine whether the following differential constraint is holonomic or not (nonholonomic).  See the example in Chapter 2.4.
    $$(1 + cos q_1)\dot{q_1} + (2 + sin q_2)\dot{q-2} + (cos q_1 + sin q_2 + 3)\dot{q_3} = 0$$
    - [ ] Holonomic
    - [x] Nonholonomic

7. The task is to carry a waiter's tray so that it is always horizontal (orthogonal to the gravity vector), but otherwise free to move in any other direction. How many degrees of freedom does the task space (the C-space of a horizontal tray) have?  (Enter an integer number.)
    ```
    4
    ```
    - Explanation: The horizontal constraint eliminates 2 of the degrees of freedom (roll and pitch) of the tray (a spatial rigid body).
