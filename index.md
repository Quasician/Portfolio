## Projects

### UR5E Robotic Arm

#### GIF
[Robot arm drawing my initials in space](https://github.com/Quasician/porfolioSite/blob/gh-pages/midterm.gif)

#### Code
Here is my code for my [robot arm](https://gitlab.oit.duke.edu/tpc14/tpc14_rosintro/-/blob/main/ur5e_robot/scripts/planning.py) writing my initials (TPC) in 3d space.
It uses poses and cartesian motion planning in ROS.

#### Description
The problem was to write my initials (TPC) in space using the UR5e’s end effector. 
My approach was to have the robot move to three unique starting locations using pose goals and once at a starting location, execute a letter using waypoints (cartesian interpolation). 
I made sure the starting locations were close enough so that the robot would not throw any errors saying that it could not find a solution. 
Another important note was to make sure that the robot would be able to reach the starting position for the letter T from the finished execution position for C so that I could debug without any issues after running the code multiple times.
