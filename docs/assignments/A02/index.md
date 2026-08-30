# A2 – Truss Stress Analysis

## Objective

For this assignment I was tasked with designing a weight planar truss using A500 structural steel with parameters assigned by this image.

<img width="1656" height="1008" alt="IMG_7208" src="https://github.com/user-attachments/assets/ded21438-99a4-4727-bc14-d7ac04eef366" />

The force P value had to be between 20 and 30 kilonewtons and I chose 25 kilonewtons. The distance of a is 0.4 meters and the distance of b is 0.3 meters. Point A is a pin and point B is roller and each element needed to have the same cross sectional area. The pins are to be identical to each other and each element needed to have the same cross sectional geometry. 

## Analyze

The first thing I did was design the 2D truss by drawing out the free body diagram of the truss. I connected a beam from point A to point B, a beam from point B to point C, a beam from point C to point D and a beam from point D to point A. The truss design now looked like this. 

<img width="2233" height="2135" alt="IMG_7209" src="https://github.com/user-attachments/assets/02e0069e-6e11-441e-abc0-0bf4095f2610" />

The next part was finding the lengths  of each element, the reactions and the forces. The length of element BC and AD were equal based on the square root of a = 0.4 and b = 0.3. The length from B to D was also needed when calculating the weight of the truss. I set my reaction of Ay at A and Bx and By at B. Bx = 0 due to having 0 forces on the x axis while Ay = 25 kN and By = -25 kN. To find the forces of the truss I used the method of joints. I started out with Joint C to find the forces of BC and CD and used trig identities to calculate the forces to BC = 41.67 kN Compression and and CD = 33.3 kN Tension. I used Joint D to find the force of AD which was calculated to be 41.67 kN Tension. Lastly, I used Joint A to find the force of AB which would be 33.3 kN Compression.

<img width="4284" height="5712" alt="IMG_7210" src="https://github.com/user-attachments/assets/efc2d8a4-8960-48c8-ba10-c1f4c181d533" />

I was then tasked with the largest internal being 41.67 kN to calculate a cross sectional area for the truss with the safety factor of 3.5. I researched to find the normal yield strength of steel to be 317.16 MPa with a density of p = 7850 kg/m^3. Using the force multiplied by the safety factor and divided by the yield strength, my cross sectional area was calculated to be 4.598 x 10^-4 m ^2. After adding all my lengths up to get my total length of 3.454 m, I calculated the shear force using the area to be 1.588x10^-3 m^3 and then used that to calculate the mass of truss which would 12.466 kg. The weight of the truss was then calculated to be 122.29 N. 

The next step of this project was to find the cross sectional area of connecting pins made of hardened steel tool. The given yield strength is 170 ksi or 1172.11 MPa, the density is 0.278 lb/in^3 or 7695 kg/m^3 and the safety factor of the pins is 4. I used this information to calculate the cross sectional area which would be 1.422 x 10^-4 m^2 and diameter which is 13.456 mm. I was not given a length for the pins so I gave it a length of 0.025 m. Since the truss has 4 elements that means we need 4 pins to connect the truss. The shear force of the 4 pins was calculated to be 3.555 x 10^-6 m^3 and the mass would be 0.0274 kg causing the weight to be 0.268 Newtons.

<img width="4284" height="5712" alt="IMG_7211" src="https://github.com/user-attachments/assets/6c3e0115-7df0-4e0d-9f08-345dbc753bd1" />.

## Decide

_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

## Communicate

