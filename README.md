# Python-WaterJug-Problem

Production System in Artificial Intelligence-:
 A production system is based on a set of rules about behavior. These rules are a basic representation found helpful in expert systems, automated planning, and action selection. It also provides some form of artificial intelligence. It is a computer program typically used to provide some form of artificial intelligence, which consists primarily of a set of rules about behavior but it also includes the mechanism necessary to follow those rules as the system responds to states of the world.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Problem Statement: 
You have an 8 litre jug full of water and two smaller jugs, one that contains 5 litres and the other 3 litres. None of the jugs have markings on them, nor do you have any additional measuring device. You have to divide the 8 litres of water equally between your two best friends, so that each gets 4 litres of water. How can you do this?
First, water is poured from the 8 litre jug into the 5 litre jug, leaving 3 litres of water in the original 8 litre jug.
Next, water is poured from the 5 litre jug into the 3 litre jug, so we now have 3 litres of water in the 8 litre jug, 2 litres of water in the 5 litre jug and 3 litres of water in the 3 litre jug.
The 3 litre jug is emptied into the 8 litre jug, so the 8 litre jug now contains 6 litres of water.
The 2 litres of water in the 5 litre jug are now poured into the empty 3 litre jug.
Water is poured from the 8 litre jug (which at this stage contains 6 litres) into the empty 5 litre jug. We now have 5 litres of water in the 5 litre jug, 2 litres of water in the 3 litre jug and 1 litre of water in the 8 litre jug.
Water is poured from the 5 litre jug to fill the 3 litre jug which already contains at this stage 2 litres of water.
We are left with 4 litres of water in the 5 litre jug which is given to one friend, and 3 litres of water in the 3 litre jug that is poured back into the 8 litre jug that already contains 1 litre of water. This gives 4 litres of water which are given to the second friend.
The whole scenario can be summarized using numbers in brackets to denote the litres of water at each stage in each of the 8 litre, 5 litre and 3 litre jugs, respectively:
[[8,0,0] right arrow [3,5,0] right arrow [3,2,3] right arrow [6,2,0] right arrow [6,0,2] right arrow [1,5,2] right arrow [1,4,3] right arrow [4,4,0]]
