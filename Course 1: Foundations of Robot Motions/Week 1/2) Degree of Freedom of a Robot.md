1. Consider a joint between two rigid bodies. Each rigid body has `m` degrees of freedom (`m = 3` for a planar rigid body and `m = 6` for a spatial rigid body) in the absence of any constraints. The joint has `f` degrees of freedom (e.g., `f = 1` for a revolute joint or `f=3` for a spherical joint). How many constraints does the joint place on the motion of one rigid body relative to the other?  Write your answer as a mathematical expression in terms of m and f. \
    ```
    m-f
    ``` 
          
2. Consider a mechanism consisting of three spatial rigid bodies (including ground, `N=4`) and four joints: one revolute, one prismatic, one universal, and one spherical. According to Grubler's formula, how many degrees of freedom does the mechanism have?\
    ```
    1
    ```
    Notes:
    - According to Grubler's formula, can be determined that `N = 4, m = 6, J = 4`
    - $dof = m(N-J-1) + \sum_{i=1}^J f_i$
    - Sum of joint freedoms is $1 + 1 + 2 + 3 = 7$
    - so, $dof = 6(4 - 4 - 1) + 7 = 1$  
   
3. A mechanism that is incapable of motion has zero degrees of freedom. In some circumstances, Grubler's formula indicates that the number of degrees of freedom of a mechanism is negative. How should that result be interpreted?
- [x] The constraints implied by the joints must not be independent
- [ ] The number of joints, the degrees of freedom of those joints, or the number of rigid bodies must have been counted incorrectly
