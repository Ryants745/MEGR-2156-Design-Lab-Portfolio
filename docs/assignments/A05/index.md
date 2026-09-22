
# A5 – Bracket Design

## Objective
This week I was tasked with designing a bracket that holds a force applied symmetrically by a strap. This design was assigned a minimum safety factor of 4, an applied load between 500 lbf and 800 lbf and a material choice between aluminum, steel or titanium. It was also assigned a maximum deformation of 0.005 in for each of its features. 

## Stress Analysis
The first step was to analyze the stress and make assumptions of each of the five features. Feature A is a cantilever beam subjected to a distributed strap load where shear failure is neglected. I chose a length of 2 in, a force of 600 lbf and aluminum 6061 T6 material. This gave the features an elasticity of 68.9 GPa with a yield strength of 276 MPa. For feature A, I had to calculate the cylinder radius and the section modulus which ended up being 0.535 in and 0.12 in^3. 

<img width="1278" height="1414" alt="0" src="https://github.com/user-attachments/assets/0fc4c39c-7815-4f6b-aa4e-32e4ddf99eee" />

Feature B is an axially loaded bar in tension with the bending moments from features A and C are neglected. Feature B was given the width of 1 in leaving the area and thickness to have the calculated values of 0.12 in^2 and 0.12 in. Feature C is a simply supported beam with a concentrated point load at its center. It has a length of 3 in and a base of 1.5 and a max bending moment of 900 lb in. The section modulus was calculated to be 0.09 in^3 which gave it a height of 0.6 in. 

<img width="1103" height="1430" alt="0" src="https://github.com/user-attachments/assets/d0dad39f-a60f-4b46-9d9f-5efd89971d8f" />

Feature D has a tensile load distributed evenly along its side walls. It has a width of 1.5 in giving it an area of 0.6 in^2 and a thickness of 0.04 in. Feature E is a short cantilever overhang that overhangs a bearing load against the fixed rigid T beam. It was given a length of 0.5 in and a depth of 1.5 in to give the values of the max root moment, the section modulus and the flange thickness. These were calculated to be 150 lb in, 0.015 in^3 and 0.245 in. 

<img width="1158" height="1430" alt="0" src="https://github.com/user-attachments/assets/0d2cf058-7c25-4575-8525-9710ca09499b" />

## Stiffness Analysis
The next step of this assignment was determining the dimensions of the stiffness analysis. Each of these features had to have a minimum deflection of 0.005 in and shear deflections are negligible. Feature A is now a cantilever beam under a uniform distributed load. Keeping the length of 2 in, the moment of inertia was calculated to be 0.024 in^4 with a radius of 0.418 in. Feature B has pure tensile deformation along it axis with the bending effects from the off center load are ignored. Feature B was given a length of 1.5 in and kept the depth of 1 in. The cross sectional are of feature B was calculated to be 0.036 in^2 with a thickness of 0.036 in. 

<img width="3520" height="4837" alt="IMG_7322" src="https://github.com/user-attachments/assets/9f6f7594-069d-4705-8797-bb9053f62787" />

Feature C is a simply supported beam with a center load where shear deflection is negligible. Keeping the length of 3 in gave me the calculated moment of inertia pf 0.0135 in^4 with a height of 0.476 in. Feature D had a uniform tensile stretch along its length of 1 in. The cross sectional area was calculated to be 0.012 in^2 with a thickness of 0.008 in. 

<img width="3627" height="4537" alt="IMG_7323" src="https://github.com/user-attachments/assets/d2e3d0a2-8507-4b28-bba0-4df52594b754" />

Feature E is a cantilever overhang under a distributed load applied at the distance of 0.5 in. It has a base of 1.5 in which gives a moment of inertia of 0.0005 in with a thickness of 0.159 in. 

<img width="4284" height="2611" alt="IMG_7327" src="https://github.com/user-attachments/assets/ad44e3d5-3613-41af-b8cc-7ad62d913df1" />

## Mutlive Sketches
The next step of the assignment was to generate two separate multiview sketches on paper one for stress and one for stiffness.

<img width="3723" height="4725" alt="IMG_7329" src="https://github.com/user-attachments/assets/d1588957-f1c5-4ec3-a15c-30a7d42417d7" />

## Lessons Learned
Feature B had stiffness govern the final thickness, requiring a dimension of 0.036 in to satisfy the 0.005 inch maximum deflection constraint. The stress requirement only needed a thickness of 0.12 in to maintain the safety factor of 4 making the stiffness the more restrictive failure mode.

The baseline load position from the load bearing pin carried directly into the moment calculations used for features A and E. These calculations will decide the thickness of fillets that will be used in the CAD design process in the next assignment.

During the analysis I assumed a rigid, fixed boundary condition at the primary mounting face. If the mount possessed a failure the flexibility would increase the stress and deflection which would require to increase the thickness to bypass any failures. This assignment took me roughly 6 hours to complete.
