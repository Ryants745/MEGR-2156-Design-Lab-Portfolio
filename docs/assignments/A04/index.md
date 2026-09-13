# A4 – Motor Mount

## Objective
This week I was tasked with designing a 3d Motor mount using a 24V DC Gear Motor Planetary Gearbox that would attach to a wall. The material I chose to use was Polylactic Acid or PLA. It needed to have a maximum deflection of 0.3mm with a minimum safety factor of 3 and it needed to hold a load of P equal to 300 N.

## Features
After choosing my material I listed what I was given and chose the length of L=50mm and a base length to be 60mm. The chosen material gave me the modulus of elasticity of 2350 MPa with a yield strength of 45.2 MPa. After drawing the FBD I calculated the moment to be 15 N m and the bending stress to be 15.07 MPa. Using this information I calculated the height to be 9.98 mm and when I calculated it with the deflection it would be 15.25 mm.

<img width="4284" height="5712" alt="IMG_7263" src="https://github.com/user-attachments/assets/808ac24a-2e50-4492-bc1f-d8868e417d60" />

To keep it consistent with feature 1 I chose to keep the base the same length of 60mm and chose a length of 65mm. After drawing my free body diagram it was time to calculate the thickness of the wall feature which would end up being 20.79 mm and for my design I decided to round it to 21 mm.

<img width="4284" height="5712" alt="IMG_7262" src="https://github.com/user-attachments/assets/4704d1c5-0a34-471f-b7c2-e1c8fd4d9992" />

## Isometric View
The next step of the assignment was to sketch the motor mount as an isometric view. I started by drawing feature 2 as the wall and feature 1 as the base of the mount. I added a clearance hole with a 3.4 diameter at each corner of the wall that would be used for shafts and bolts. I also added clearance holes that would mount the motor on the base as well a hole in the middle the base with a 6.5 diameter for the shaft in the middle of the motor. I then added a fillet at the connection of the base and the wall of the mount with a radius of 5mm to minimize the deflection. After creating the isometric view I calculated the volume to be 106934 mm^3 and the mass to be 156.42 grams.

<img width="4284" height="5712" alt="IMG_7264" src="https://github.com/user-attachments/assets/b196e14f-9719-4da7-8552-22d959d7e387" />

## CAD Model
The final part of the design process to create 3D design which I created using Solidworks. I opened up a new part before designing the mount I put all of values into the Equations to use for my parametric modeling. 

<img width="1007" height="712" alt="Screenshot 2026-09-12 151157" src="https://github.com/user-attachments/assets/5b61dfca-3cfd-4a59-b379-0554474ffb65" />

I started designing the motor mount by creating the wall on the front plane and then attaching the base to the bottom of the wall. After adding the base I added the fillet radius of 5 mm to the top edge of the base that was connected to the wall.

<img width="1280" height="1552" alt="Screenshot 2026-09-12 151638" src="https://github.com/user-attachments/assets/a5c79da5-2dee-4624-ac36-541da74743c8" />

The next step was to extrude cut the holes of the features and this took awhile because I had to create lines to make sure the holes were in the right spots. For the corner holes on the wall I put the center of the holes at 10 mm x 10 mm and once they were lined up correctly I deleted the lines. I added the hole in the middle of the base and created a construction circle sketch for the 22 mm diameter of the motor. This also helped me create the 4 clearance holes around the center hole as they were designed to be circled around center hole at the points of the 22 mm diameter. 

<img width="1280" height="1552" alt="Screenshot 2026-09-12 154035" src="https://github.com/user-attachments/assets/e22c26a4-4067-4331-b50f-bafb685b53f2" />

After creating the design I had to choose a material but since the PLA material was not on Solidworks I created a custom one. In order for this to be correct I gave it the values of 45.2 MPa for yield strength, elastic modulus of 2350 MPa, poison ratio of 0.36, shear modulus of 864 MPa and a mass density of 1240 kg/m^3. These values were based on the provided website of information on the material polylactic acid. Once that was applied I checked the mass and it was 156.43 grams which was almost the same as my calculated mass. 

<img width="815" height="601" alt="Screenshot 2026-09-12 155746" src="https://github.com/user-attachments/assets/b4ebbc00-ce65-476f-a806-383d3d1fcc32" />

Once the mass was checked it was time to test the mount against the applied load of 300 N. In order to set up the simulation, I applied the fixed geometry to the faces of the clearance holes on the wall and then applied the force of 300 N downward to the top face of the base. After applying the force it was time to run the simulation. The results show a maximum stress of 9.96 mm, a safety factor of 4.5 and a max deflection of 0.332 mm. The safety factor met the minimum stand of 3 but the deflection is slightly off from what I was designing before so I tried to make small adjustments like adding length to the base, deleting and adding the fillet radius and reducing the thickness of the wall to 20.79. Each of these adjustments added deflection so I decided to leave it with the original results. I also added the safety factor chart for more results.

Stress Graph

<img width="2560" height="1552" alt="Screenshot 2026-09-12 225516" src="https://github.com/user-attachments/assets/d4f4859a-e348-47d3-bfaa-a7f0c51e2ef6" />

Displacement Graph 

<img width="2560" height="1552" alt="Screenshot 2026-09-12 225510" src="https://github.com/user-attachments/assets/0866bd00-ee3a-456c-9e88-bc5178cb5ce1" />

Safety Factor 

<img width="2560" height="1552" alt="Screenshot 2026-09-12 225455" src="https://github.com/user-attachments/assets/ec3fd6bf-baff-4d08-92ab-e398689847cf" />

## Reflection
As I said earlier I learned how to make holes in designs by using line to line up the correct placements of each hole. My deflection being slightly off could be the result of a rounding error with some of my results but overall I was satisfied with my result as it was only off by 0.032 mm which is 10.67%. This assignment took me roughly 8 hours to complete if I took out breaks I took while completing it.

Motor Mount 3D Design Download Link
https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A04/Motor%20Mount.SLDPRT
