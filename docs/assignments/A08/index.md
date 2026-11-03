# A8 – Gear Box Design

## Objective
This week I was tasked with creating a gear box design based on 24:9 gear ratio, a totque of 1.25 in lbf and speed of 1100 rpm. The gears also had shaft that have a length of 1 inch each and the input shaft is diameter is 0;125 in while the diameter of the output is 0.25 inches.

## Shaft Calculations
I started by calculating the input gears speed which would be 2933.33 rpm and its torque to be 0.46875 in lbf. Using the torsion formula I found the stress to be 1222.3 psi and since this lower than the standard shaft stress the diameter was sufficient. The torsion of the output shaft was calculated to 407.4 psi which was also sufficient. 

<img width="4284" height="5712" alt="unnamed" src="https://github.com/user-attachments/assets/40ef4ab5-5e6d-42b5-ad4d-6da56740a760" />

## Journal bearings
In order to choose the right journal bearings for each shaft I had to calculate the force, area, pressure, surface velocity and pv rating of each shaft. The input shaft has a tangential force of 1.25 lbf, radial force of 1.33 lbf, bearing force of 0.665 lbf, an area of 0.3125 in ^2, pressure of 21.28 psi, surface velocity of 96 ft/min and a pv rating of 2042.88 psi ft/min. The output shaft has an area of 0.0625 in^2, pressure of 10.64 psi, surface velocity of 72 ft/min and a pv rating of 766.08 psi ft/min. The thickness of the input shaft was calculated to be 0.00036 in with a stress of 35.47 psi and the output shaft had a thickness of 1/16 inch and a stress og 27.66 psi. Using this information I selected the 841 bronze sleeve bearings.

<img width="4284" height="5712" alt="IMG_7566" src="https://github.com/user-attachments/assets/5d290c66-728d-4101-b195-39f12e8b2b2e" />

<img width="2560" height="1552" alt="Screenshot 2026-11-02 212238" src="https://github.com/user-attachments/assets/0667bcd3-3403-4bdb-8348-7e3717ac2805" />

<img width="2560" height="1552" alt="image" src="https://github.com/user-attachments/assets/a56ec4ea-5bc1-409a-b635-92a2e5593c02" />

## Sketch and CAD
The next part of the assignment was to sketch two component gearbox housing fitted together. I chose one that fit together by 4 m4 socket head cap screws and 4 m4 hex nuts. 

<img width="4188" height="2791" alt="IMG_7567" src="https://github.com/user-attachments/assets/050700d6-41a7-4f32-a4de-26d62b96e004" />

Once I sketched a design it was time to create the housings in CAD and assemble the parts. I started by creating the bottom housing by sketch a rectangle with length of 120 mm, a width of 75 mm and a height of 15 mm. Then I created 2 extrude cylinder cuts on the one for the gear shafts. After that I sketched 1 hole on each corner with a pocket at the bottom for the screws and nuts. I also added one dowel pin holes on each side for dowel pins. I then copied this housing create my top housing but change so that the top of the top housing would fit the screws not the nuts. After that I created both of the shafts for the 2 gears and then it was time to assemble the gear box.

<img width="2560" height="1552" alt="image" src="https://github.com/user-attachments/assets/33ef7746-ee02-44d2-9050-3d82ad486c6c" />

<img width="2560" height="1552" alt="Screenshot 2026-11-02 214738" src="https://github.com/user-attachments/assets/7f444dba-10ab-46c9-b457-b07809f28ecd" />

I started by creating a new file and placing all my part out and trying to assemble each of the parts. Due to the amount of parts the assembly required a lot of mating so I mated the shafts, gears and bearings together. I mated the housing together by connecting their faces and then began working om the screws and nuts. This was very tedious as I had to mate each of the screws 3 or 4 times due the design of the threads I had a hard time selecting the right faces and/or edges to mate screws with the housing and I am not sure if I did it right but I was running out of time and patience with the screws and this assignment so I left it as it is now. I also mated the gear shaft assemblies with their with the cylinder side cuts. 

<img width="2560" height="1552" alt="image" src="https://github.com/user-attachments/assets/e10b6e61-7ff8-450b-af7d-6db95fd9c97b" />

# Lesson Learned
I originally misread the link for the gears so I thought I had to make them in solid works so I tried creating a gear in solidworks however it was not cooperating correctly and I realized the link was for the specific gears so I erased the custom gear and continued to create the shafts. This wasted so much of my time which is why I rushed the assembly process. While I was unable to finish the full assembly according to the file if I had more time I believe I could have discovered what was causing all the issues or find easier way to mate certain parts. I also could have started this assignment earlier but I tried to space out my time with completing my other class assignments that I knew would take less time. This assignment took up most of my time between Sunday and Monday when I was not in classes or taking breaks. 

Links

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/6391K111_Oil-Embedded%20841%20Bronze%20Sleeve%20Bearing.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/6391K131_Oil-Embedded%20841%20Bronze%20Sleeve%20Bearing.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/7880K19_Metal%20Gear%20-%2020%20Degree%20Pressure%20Angle.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/7880K24_Metal%20Gear%20-%2020%20Degree%20Pressure%20Angle.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/90592A085_Steel%20Hex%20Nut.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/91290A176_Black-Oxide%20Alloy%20Steel%20Socket%20Head%20Screw.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/91595A134_Dowel%20Pin.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A08/Gear%20Assembly.SLDASM 
