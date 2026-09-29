# A6 – Bracket Design (Drawings Part 1)

## Objective 
This week we were assigned to use our stress analysis and stiffness analysis of our brackets from last week to create a parametric bracket design and drawing in CAD.

## Parametric Design
The first step was to use the values of my features from last week to put in the equations to match my design. 

<img width="1007" height="712" alt="Screenshot 2026-09-28 234145" src="https://github.com/user-attachments/assets/1383e421-5d6a-422a-8409-db99c7f8e150" />

I started my design by creating a rectangle that is 0.6 in x 1.5 in. After that, I added two rectangles on the top left and top right corners of the rectangle. These rectangles were 0.245 in x 0.5 in, which created the T structure of features C, D and E. I then used a power trim to make the sketch of the shapes one shape and then I extruded sketch by 3 inches to create the T structure. 

<img width="2560" height="1552" alt="Screenshot 2026-09-26 215440" src="https://github.com/user-attachments/assets/bcd0dcdb-a72f-40e1-8581-033ea0a2aa7a" />

Next, I added Feature B under the T structure by centering a rectangle that was 0.12 in x 1 in. This was then extruded by 1.5 in to match my values for feature B. Once Feature B was extruded the bracket now looked like this.

<img width="2560" height="1552" alt="Screenshot 2026-09-26 222150" src="https://github.com/user-attachments/assets/2a6d607d-2cfe-4ac0-b68f-2d1a02e294de" />

The last features to add to the bracket design was feature A and the fillets. I started by centering a circle with a diameter of 1.07 inches in the on the back of the t structure and feature B. The circle was extruded by 3 inches to add the feature to the bracket. After this I added fillets with a thickness of 0.04 in to the edges of feature A that would connect with the other features. Once those were all added, the bracket design was completed and it was time to create the engineering drawing of the design.

<img width="2560" height="1552" alt="Screenshot 2026-09-28 214000" src="https://github.com/user-attachments/assets/9ac14292-ce49-4194-9494-002758d2e737" />

## Drawing 
The next step of the assignment was to create the engineering drawing using the standard sheet format ANSI B. Once the sheet was created, I added the front view, top view, right view and isometric view of the part in the sheet. I added each of the dimensions based on each views and made sure that there were no repeating or unnecessary dimensions. Once all the dimensions were added I noticed that I needed tolerances for some of my dimensions for the assignment, so I decided to add tolerances to the fillet, the diameter, and a tolerance of middle length of the T structure. I also added centerlines and center marks to symbolize the hidden sections in each view. Once I added all information in the title block, the drawing was completed.

<img width="1632" height="1051" alt="Screenshot 2026-09-28 224527" src="https://github.com/user-attachments/assets/29a881c6-7e9b-47dd-be3d-708291df7ceb" />

## Reflection
I used the maximum bending stress equation and rearranging the variables to find the diameter of 1.07 in for feature A. I expressed this equation in SolidWorbs by typing the equation of 2*( ( 4 * 0.12 ) / ( pi ) ) ^ ( 1 / 3 ) to obtain my value of 1.07 in. The moment of 0.12 in^3 was calculated using the length of 2 in and the load W equaling my chosen force of 600 lbf which was doubled during the analysis. 

I applied a tight tolerance to the diameter of feature A and the fillets while I applied a looser tolerance to the length 0.5 in that is between the T structure. The tolerance for the t structure length was added for smooth movements along for the structure. The tight tolerance was applied the feature of the diameter because this surfaces forms a critical sliding fit where clearance is required to permit linear movement to prevent binding. If the tightest tolerance was applied to the dimension of the diameter, the manufacturing costs would scale exponentially. It would force designers to perform secondary operations and increase the amount of inspections to verify the measurements of the design. The tolerance would also increase production without providing a benefit to its functional performance. This assignment took me roughly 7 hours to complete if factor out any brakes that I took while completing the assignment. 

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A06/bracket%20drawing.SLDPRT

https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A06/bracket%20drawing.SLDDRW
