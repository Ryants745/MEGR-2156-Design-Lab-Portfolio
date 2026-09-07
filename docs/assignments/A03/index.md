# A3 – Parametric and FEA

## Objective
The purpose of this assignment was to design a circular bar parametrically in cad with a load between 300 lbf and 500 lbf. The max axial deflection is 0.009 inches. The bar was also to be designed from Aluminum with a range of Young's Modulus between 8.5 and 11.5 x 10^6 psi. For my cross sectional design I decided to use the load of 400 lbf, the length of the diameter be 0.5 in, and for the material modulus to be 10 x 10^6. This part also required a yield strength of 40 ksi. I calculated the cross sectional area as 0.19645 in^2 and the length was calculated as 44.1788 in. After calculating the stress to be 2037.18 psi, I used the density of aluminum (p = 0.0975 lb/in^3) to calculate the weight of the bar being 0.846 lbs. 

<img width="3652" height="2519" alt="IMG_7246" src="https://github.com/user-attachments/assets/2e8e233f-4c77-44a4-ae30-8bce01a0a52f" />

## CAD

The next of the design process was to design the bar in CAD using Solidworks. I opened up a new part and entered my paramets in the equation chart.

<img width="1007" height="712" alt="Screenshot 2026-09-06 234711" src="https://github.com/user-attachments/assets/d14d5149-5e15-454f-9a50-b6f7d1a2c08b" />

Next, I used the value to create my bar and originally I chose the material of 6061 Aluminum Alloy.

<img width="1280" height="1552" alt="Screenshot 2026-09-06 232646" src="https://github.com/user-attachments/assets/5af99346-8ac0-402b-b54f-b998d7a6b60d" />

## FEA Simulation
For the FEA simulation I used the fixed geometry on the left face of my bar and applied the direct load of 400 lbf to the right face of the bar. After running the simulation I noticed that my results were incorrect and so I checked the properties of the material and changed it to the 6061 T6 (SS) which had an elastic modulus of 10007604 psi and gave the bar the weight of 0.85 lbs which is roughly the same as the calculated weight. After running a new study my results were much closer to what was given and calculated. The bar had a yield strength of 39885.378 psi, a normal stress of 2038.271 psi and a maximum stress of 2205.611 psi.

<img width="2560" height="1552" alt="Screenshot 2026-09-07 001902" src="https://github.com/user-attachments/assets/3b0b4523-60c7-49c3-837f-eabe8016a51f" />

The simulation also caused the same max deflection of 0.009 inches as the one that was required for the assignment. Next I added a chart for the safety factor and found the minimum safety factor to be 18.064.

<img width="2560" height="1552" alt="Screenshot 2026-09-07 001912" src="https://github.com/user-attachments/assets/c629b017-ed35-4e3e-bd33-caa31334acea" />

<img width="2560" height="1552" alt="Screenshot 2026-09-07 001919" src="https://github.com/user-attachments/assets/625183cc-ba1e-4074-a6bf-3e2d8f8534c2" />

## Reflection
There was no need to calculate the percent difference of the axial deflections because they were exactly the same. I expected them to agree for this geometry and loading because the values of the Modulus and the weight of the bar were roughly the same. I would trust the hand calculations more for the design because it is more credible to the geometry and load as it prevents constraints and any meshing issues that may exist when using Solidworks. 

For the pin hole I used the stress concentration factor of 3.0 to calculate the estimated peak stress of 6114.813 psi. Using the yield strength of 39885.378 psi, I calculated the estimated safety factor of roughly 6.523 which would pass the design failure threshold as it is greater than 1.0. 

<img width="2453" height="1712" alt="IMG_7248" src="https://github.com/user-attachments/assets/9358b89a-50a7-4d84-bc4d-ae51f9466f20" />

As I previously stated, a mistake was created when choosing the 6061 Alloy rather than the 6061 T6 but this mistake was resolved when using the 6061 T6 (SS) material on the bar. I also learned how to use parametric values in Solidworks to create designs. This assignment took me roughly 5 hours to complete when taking out any breaks I took while completing the assignment.

