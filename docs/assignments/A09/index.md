# A9 – Pulley System Design

## Objective
This week we were given a task to design pully system to transfer power between two parallel axes separated by a center distance of 4-6 inches. This system must also have both of the pulley's diameters to be 3 inches, have a rotational speed between 1000-2000, belt tension between 4-6 lbf, a minimum safety factor of 3, and the pulley must be made of aluminum, ABS or steel.

## Belt Design
We are told that the belt is made from polyurethane rubber with a yield strength of 3.25 MPa or 471 psi at 20% strain. In order to select a suitable belt we need to find the forces of both sides, the diameter of the belt, the circumference and the cross sectional area. I chose a rotational speed of 1500 rpm. a belt tension if 5 lbf and a center distance of 5 inches. Assuming the initial force pulls equally on both the top and bottom belt spans, the shaft force would be double of the initial or 10 lbf.  Since there is no slippage F2 would equal zero while F1 equals 10 lbf. Using the yield strength and the safety factor, I found the normal allowed stress to be 157 psi. Using this value and the force of 10 lbf, I found the area to be 0.0637 in ^ 2. This would give me of minimum diameter of 0.285 in. As for the circumference, I used the formula giving me the value of 19.425 in. Once I had all the information I was told to look on McMaster for the belt that would best suit my design. The first one I found that met my circumference and diameter requirements was a 0.375 in diameter belt with 12.25 inch to 24 inch circumference. Using this diameter I verified it by calculating the actual area, stress and safety factor and it met all the requirements so it was time to solve for the shaft diameter. 

<img width="4284" height="5712" alt="IMG_7590" src="https://github.com/user-attachments/assets/48cdc4dd-7d0e-4c99-a09b-486e6cdcc599" />

## Minimum Shaft Diameter
This shaft is supposed to be made of 1060 hardened steel with an applied torque and it has to meet a minimum diameter and area. Using the force of 5 lbf and the radius of the pulley diameter, I calculated that the torque of the shaft would be 15 lb in. The material has a yield strength of 90000 psi and the shear strength is roughly 57 % of that or 51930 psi. Using this I calculated the allowable shear stress to be 17310 psi. Using this value would give me a diameter of 0.164 in and an area of 0.0211 in^2. Since this diameter is not a standard diameter that would normally find I would use the same diameter as the diameter of the belt and after calculating the actual values this diameter will work for my design.

<img width="4284" height="5712" alt="IMG_7591" src="https://github.com/user-attachments/assets/ecd6c1ea-ecbc-4e2e-ba93-fa87dda25808" />

## Journal Bearing and Frame Design
Since we have found a shaft, we need to design a journal bearing out of sintered metal or non metallic using this table.

<img width="580" height="433" alt="table" src="https://github.com/user-attachments/assets/b848db2f-f668-4fb6-a976-b06106ffa9da" />

To pick the right material we had to find the pressure, linear velocity and the PV rating. Using the diameter of the shaft and choosing the length of 0.375 in the area of the journal would be 0.1406 in^2. This would give me a pressure of 71.12 psi, a linear velocity of 147.26 fpm and a pv rating of 10,473 psi ft/min. Looking at the table above, I selected a material of porous bronze which met my values. Once this was all done we had to use engineering analysis to design a frame that would support the pulley system. I was not given any further outline instructions for this part, so I chose an aluminum plate with a yield strength of 15000 psi and dimensions of base being 0.125 in and the height being 1 in. Using this and other values necessary I calculated the max bending, section modulus and bending stress and the safety factor for this frame. Since I met the safety factor, I would say the frame would be suitable to support the pulley system. We were also not told to design a cad model of the pulley system so I assumed that I was finished. 

<img width="4284" height="5712" alt="IMG_7592" src="https://github.com/user-attachments/assets/02cb8631-d5f1-46c6-b224-a85727d6b8c3" />

## Lessons Learned
I learned that the friction of the rope and the pulley can be used to design the pulley system by suspending the load on one end of the rope and no load on the other end. I imagine that I could have learned more from this assignment if I were to test this design by creating a CAD model of it and running a test on the model rather than just calculating theoretical values. This assignment took me roughly 2 hours to complete plus writing out this documentation. 
