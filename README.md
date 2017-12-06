# cghernandez_fxie
Robocode robot
Carlos Hernandez
Feng Xie
CS141
Robocode Report
	Our initial outline for our robot involved moving in predetermined patterns based on our own robots health. So our first robot design would circle around the arena shooting the robot nearest to it, this also meant that we were one of the targets that would stand at the most and since we were always moving in a certain pattern we would eventually be far from the target and would miss consistently. After several runs we decided it be best to abandon the pattern based movement and try to focus on our enemy's position instead. We kept the circular movement and made the center of the circle the enemy's position. We then made it so our robot would circle inwards and set it so that our robot would have to be within a certain distance in order to shoot, therefore saving energy and reducing the chances of a disable.
Overall our robot performed as desired, one of the major improvements and an error we overlooked was that  if an enemy was not directly in front of the radar our robot would not attempt to locate another target so it would continuously move from wall to wall. A code segment that causes the radar to spin 180 degrees to scan the other side should fix this issue. Another issue is that our robot moves in a very predictable pattern so it would be susceptible to robots that can employ predictive shooting. We could add a random interval that makes our robot switch direction while still moving inwards towards a target. (Zigzag pattern)
