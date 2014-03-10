

#ECE_CE3: Elevator Controller


#Moore Simulation
The below picture is a simulation of the Moore Elevator Code.

![Pic2][pic2]

[pic2]: https://raw.github.com/AnthonyEcheverry/CE_3_Echeverry/master/use_this_one.PNG 

The above Moore testbench can be visually verified as correct by looking at the different states of the ISim.  As we can see, the elevator starts at floor one, like it should and then goes up one floor every two clock cycles (which is the rising edge of the clock).  After reaching the fourth floor, it will return to the first floor with no stops at the 3rd and 2nd floor.





#Mealy Simulation
The below picture is a simulation of the Mealy Elevator Code.

[picture_1]: https://raw.github.com/AnthonyEcheverry/CE_3_Echeverry/master/Mealy_new.PNG "Mealy"
![Picture_1][picture_1] 

The Mealy Simulation  is correct because we can see that like the Moore Elevator, the Mealy Elevator also starts at floor 1 and then goes up each floor one at a time and stays at each floor for 2 steps until if procedes.  It then goes back down from the fourth floor to the first floor without stopping at the 3rd or 2nd.  I also know that my ISim is correct for both because it matches what was given to us in the CE instructions.

In-code Questions: I answered most of these in the code, but here they are for easier viewing.
1. Reset is synchronous because it takes place "in real time," it changes at certain periods with the clock.
2. I am not really sure if the Mealy and Moore Machines were different. The act the same and get the same result except the Mealy Machine had a "next_floor" option built in.


