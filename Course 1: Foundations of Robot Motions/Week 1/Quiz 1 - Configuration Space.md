1. Using the methods for determining the number of degrees of freedom of a rigid body in 3-dimensional space from the book and the video, find the number of degrees of freedom of a rigid body in a conceptual 4-dimensional space.  Your answer should be an integer.
    ```
    10
    ```
    
2. Referring back to Question 1, indicate how many of the total degrees of freedom are angular (rotational).  Your answer should be an integer.
    ```
    6
    ```
    Notes: The 4 coordinates to place the first point on the rigid body are translational (linear).  All other points are subject to distance constraints, which make them angular degrees of freedom
    
3. Assume your arm, from your shoulder to your palm, has 7 degrees of freedom.  You are carrying a tray like a waiter, and you must keep the tray horizontal to avoid spilling drinks on the tray.  How many degrees of freedom does your arm have while satisfying the constraint that the tray stays horizontal?  Your answer should be an integer.
    ```
    5
    ```
    Notes: The requirement that the tray be horizontal places two constraints on its orientation:  the rotation of the tray about two axes defining the horizontal plane of the tray must be zero.  (In other words, the roll and the pitch of the tray are zero.)

4. Four identical SRS arms are grasping a common object as shown below.
    ![SRS Arms](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/igjSFNLKEeeacxI__l487A_8b43caa2ac1db5043cfc8ddafec054e4_ex03-01.jpg?expiry=1679961600000&hmac=32NvuNrAHfFkdcaIpMIeNdm0_mDfhiTP6g9fQlVJJng)
   Find the number of degrees of freedom of this system while the grippers hold the object rigidly (no relative motion between the object and the last links of the SRS arms).  Your answer should be an integer
   ```
   10
   ```

5. Referring back to Question 4, suppose there are now a total of $n$ such arms grasping the object. What is the number of degrees of freedom of this system?  Your answer should be a mathematical expression including $n$. Examples of mathematical expressions including $n$ are $4 ∗ n - 7$ or $n - 3$
    ```
    n + 6
    ```
    
6. Referring back to Question 4 and 5, suppose the revolute joint in each of the $n$ arms is now replaced by a universal joint. What is the number of degrees of freedom of the overall system? Your answer should be a mathematical expression including $n$. Examples of mathematical expressions including $n$ are $4 ∗ n - 7$ or $n - 3$
    ```
    2n + 6
    ```
    
7. Use the planar version of Grubler's formula to determine the number of degrees of freedom of the mechanism shown below.  Your answer should be an integer.  (Remember that a single joint can only connect two rigid bodies, so if you see more than two connecting at a single point, there must be more than one joint there.  Also, the two blocks in the channels are only allowed to move prismatically in those channels, and one of the joints is labeled "P" for prismatic.  You will need to identify all the other joints, and links.)
    ![Mechanism](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/gdq0LePPEemELQpo9cj5Ig_03e1971841af30d3d56c63614629b30c_ex04_1-new.jpg?expiry=1679961600000&hmac=GpAT0ObhDEfzBoWXO2970cj-Zmo0FxcI46YL_U_9xgg)
    ```
    3
    ```
