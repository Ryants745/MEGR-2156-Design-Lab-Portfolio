# A2 – Truss Stress Analysis

## Objective

For this assignment I was tasked with designing a weight planar truss using A500 structural steel with parameters assigned by this image.

<img width="1656" height="1008" alt="IMG_7208" src="https://github.com/user-attachments/assets/ded21438-99a4-4727-bc14-d7ac04eef366" />

The force P value had to be between 20 and 30 kilonewtons and I chose 25 kilonewtons. The distance of a is 0.4 meters and the distance of b is 0.3 meters. Point A is a pin and point B is roller and each element needed to have the same cross sectional area. The pins are to be identical to each other and each element needed to have the same cross sectional geometry. 

## Design

The first thing I did was design the 2D truss by drawing out the free body diagram of the truss. I connected a beam from point A to point B, a beam from point B to point C, a beam from point C to point D and a beam from point D to point A. The truss design now looked like this. 

<img width="2233" height="2135" alt="IMG_7209" src="https://github.com/user-attachments/assets/02e0069e-6e11-441e-abc0-0bf4095f2610" />

The next part was finding the lengths  of each element, the reactions and the forces. The length of element BC and AD were equal based on the square root of a = 0.4 and b = 0.3. The length from B to D was also needed when calculating the weight of the truss. I set my reaction of Ay at A and Bx and By at B. Bx = 0 due to having 0 forces on the x axis while Ay = 25 kN and By = -25 kN. To find the forces of the truss I used the method of joints. I started out with Joint C to find the forces of BC and CD and used trig identities to calculate the forces to BC = 41.67 kN Compression and and CD = 33.3 kN Tension. I used Joint D to find the force of AD which was calculated to be 41.67 kN Tension. Lastly, I used Joint A to find the force of AB which would be 33.3 kN Compression.

<img width="4284" height="5712" alt="IMG_7214" src="https://github.com/user-attachments/assets/2b67a285-1707-4e74-b52b-1259585f86ee" />

I was then tasked with the largest internal being 41.67 kN to calculate a cross sectional area for the truss with the safety factor of 3.5. I researched to find the normal yield strength of steel to be 317.16 MPa with a density of p = 7850 kg/m^3. Using the force multiplied by the safety factor and divided by the yield strength, my cross sectional area was calculated to be 4.598 x 10^-4 m ^2. After adding all my lengths up to get my total length of 3.454 m, I calculated the shear force using the area to be 1.588x10^-3 m^3 and then used that to calculate the mass of truss which would 12.466 kg. The weight of the truss was then calculated to be 122.29 N. 

The next step of this project was to find the cross sectional area of connecting pins made of hardened steel tool. The given yield strength is 170 ksi or 1172.11 MPa, the density is 0.278 lb/in^3 or 7695 kg/m^3 and the safety factor of the pins is 4. I used this information to calculate the cross sectional area which would be 1.422 x 10^-4 m^2 and diameter which is 13.456 mm. I was not given a length for the pins so I gave it a length of 0.025 m. Since the truss has 4 elements that means we need 4 pins to connect the truss. The shear force of the 4 pins was calculated to be 3.555 x 10^-6 m^3 and the mass would be 0.0274 kg causing the weight to be 0.268 Newtons.

<img width="4284" height="5712" alt="IMG_7211" src="https://github.com/user-attachments/assets/6c3e0115-7df0-4e0d-9f08-345dbc753bd1" />

## 3D CAD Modeling 

_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

The last step of this project was to use a CAD software to 3D model the truss. This step took a long time because I decided to use SolidWorks and I had to learn how to use everything in SolidWorks because I was told it was easier to use than Creo which is the software I had experience with before. The first thing I did was design the 2d truss drawing by drawing out the shape based on my diagram from my calculations. After that I went into the weldments tools to modify my truss to go from 2D to 3D. I made the truss 3D by setting the standard to ansi inch pipe with the size of 0.5 sch 40. I then added a new line connecting point B to point D to add the BD member. I also had to make sure my diameter of the truss was the correct length so that it would line up with my hand notes. 

<img width="944" height="1301" alt="Screenshot 2026-08-30 163029" src="https://github.com/user-attachments/assets/70440ed4-c43f-48ad-84e5-c785ef5f426c" />

After adding a sketch of a circle to each point I used the extrude cut to cut the holes for the pins. Next I checked the mass and I noticed it was no where near the target of 12.466 kg. So to fix this issue I made several adjustments to the truss first with selecting the material of alloy steel. I tried to change the type of the pipes but that did not help very much so I changed it back to what it was originally. After doing some research and watching some videos I decided to mess with length of the inner diameter of the truss. It got to a point where the mass was around half of what it is what supposed to tried using the mirror function to double it. This caused the mass to be more 13.300 kg so although it was a little big I was getting in the right direction. After setting the inner diameter to 16.46 mm my mass was finally at 12.466 kg. 

<img width="1707" height="1263" alt="Screenshot 2026-08-31 212055" src="https://github.com/user-attachments/assets/b3c6c4c9-f00f-403f-97ca-d72d876711c0" />

After saving the truss file, I created the pin part using the extrude feature and after applying the material of alloy steel I checked the mass and it lined up perfectly to my calculated mass.

<img width="2034" height="1263" alt="Screenshot 2026-08-31 212947" src="https://github.com/user-attachments/assets/859a495c-3d44-4602-9ea0-fb1ea479e7bf" />

The next day I was unsure if I had to create the assembly of the parts as it was not stated as a requirement but I figured I would learn for future assignments. So I opened an assembly file and placed my parts I began learning the process of how to assemble each part. After trying to figure it out at each corner I realized I was putting the pin in incorrectly and that the assembly would not read my holes the correct way. I then went back to the truss part and noticed that my holes for the pins were extremely off as I did not read the wrong measurement function when creating the holes. After fixing the diameter I changed the inner diameter to roughly 16.69 mm so that mass would line up correctly after fixing the holes. 

<img width="2034" height="1263" alt="Screenshot 2026-08-31 214318" src="https://github.com/user-attachments/assets/63b6dfcf-3848-4c31-a4a8-b3e180c6fea6" />

After fixing the holes, I went back to assembling the part which was much easier now that the holes were correct and knowing now to set it up correctly. However I had to connect them by linking the planes rather than the faces for the assembly to work. 

<img width="2034" height="1263" alt="Screenshot 2026-08-31 215026" src="https://github.com/user-attachments/assets/dc72af1c-254d-42ca-b66d-1f52ff98cd01" />

I also wanted to test the truss to see if it could hold the desired loads of the forces of 25 kN. To do this I went to the simulation feature. This would take a while to learn how to set up correctly as I had to change different settings of the forces so I could mesh and run the simulation. I kept trying to fix the forces but something was still preventing the simulation. I had to go to class so I saved the assembly without the simulation. Once I got back to the simulation I had to set it up so it was back where I needed it to be. After it finally went through the simulation it came out deformed as shown in the image below. The results of the the test showed that the truss had a maximum stress of 1047 MPa and a yield strength of 620.4 MPa. This caused my minimum safety factor to be 0.59 which caused the structural failure.

<img width="2560" height="1552" alt="Screenshot 2026-08-31 230546" src="https://github.com/user-attachments/assets/7fed0491-9fb6-48c4-ad27-c5637478eaed" />
Once I was done the simulation I noticed I forgot to compare the weight and the mass of the assembly from CAD to my calculations. The total calculated mass was 12.5756 kg and the weight was 123.367 N. The CAD total mass was 12.57647 kg and the total weight was 123.375 N. 

<img width="4284" height="5712" alt="IMG_7215" src="https://github.com/user-attachments/assets/768c8734-6793-4e8f-813b-cf6f526593da" />


## Engineering Lessons Learned

During this project I learned a lot about the different features of SolidWorks and how they were relevant to completing this assignment. I also learned that I should check all measurements before assembling parts as it took me a while to realize what was wrong. Now that I know some of the basic feature for example weldments, extrudes, simulations, assemblies and more, I think it will be easier to work on the next project that requires using a CAD software.

This assignment was extremely time consuming as I worked on it for 4 days. However if I take out all the breaks I took from going to classes, doing other work etc; the amount of actual time would be around 2 days. This was mainly due to me learning the features of SolidWorks as I went through issues that I had to work through to complete the project. I also did not start my documentation until I took a break from trying to assemble the truss. Once I began the assembly again, I began documenting as I worked through the assembly and the simulation.

