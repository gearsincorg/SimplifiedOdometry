## Phil's Simplified FTC Odometry Tutorial.  

This tutorial presents an alternative approach to FTC odometry, one that combines the ability to accurately measure how the robot is moving, with simple straight-line motions.

Lots of FTC teams (especially rookies, or teams without strong software mentorship) struggle with autonomous programming.  As more teams adopt Omni (holonomic) drive trains like Mecanum and X drive, the problem has only grown.  These drives don�t act predictably, often drifting off course, so it�s hard to tell exactly where a robot is going in autonomous just by watching what the driven wheels are doing.

Non-powered �follower� wheels were added to robots to measure the actual motion across the field, and so FTC Odometry was born.   But now teams have to figure out how to use this new Odometry input.

If teams have access to one or more adventurous programmers, they can try using some of the more advanced Odometry tools like RoadRunner and MeepMeep.  These tools treat the field as an X/Y coordinate grid, and can plan and execute complex curved motions.  But these tools have steep learning curves, and rely on some sophisticated testing, so they don�t always lead to success.  

I think something simpler is needed, so this tutorial is going to take a different approach.  

To try this code, simply copy the three files into your lowest level teamcode folder and build your project.


### This tutorial consists of four YouTube videos.

Part 1: Overview. https://youtu.be/lpVG2Pl6RGY 
An introduction to the purpose of this FTC tutorial, and some of the caveats that are assumed in it's application.

Part 2: Autonomous. https://youtu.be/EV7n9rGcxF4  
A walk-through of a sample Autonomous OpMode.

Part 3: Teleoperation.  https://youtu.be/X7RyAMbP240 
A walk-through of a sample Telop. OpMode.

Part 4: Robot Class. https://youtu.be/eWzGW7ZcPh8 
A walk-through of the hardware classthe Java code istelf, explaing the robot hardware class and the sample teleop and autonomous opmodes.

I hope you find this helpful.

Mr. Phil.