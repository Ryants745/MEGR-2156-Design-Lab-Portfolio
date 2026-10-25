# A7 – FEA on Bracket

## Objective
After long break, this week I was tasked with doing a FEA simulation on the bracket that was created for the previous 2 assignments.

## Design 1
The constraints for this bracket included that it needed to meet a safety factor of 3 or higher, a maximum deflection under 0.005 in and assigned a load between 500 and 800 lbf. In my initial design I used 600 lbf force on the bracket and doubled it on the pin or Feature A. This ultimately gave me the diameter of the pin which was 1.07 in. So I applied a load of 1200 lbf to the pin and applied fixed geometry to the face of the T structure that connects to the pin as well as the inside faces of the T sturcture. The mass for design 1 was 0.53 lbs or 240.4 grams and the material is Aluminum T6 6061 which was the original material that I assigned to the bracket during my analysis. For the first simulation attempt I chose the maximum coarse mesh on the bracket. The results of the first attempt showed that the bracket had a max stress of 3.542 MPA, a deflection of 3.308 x 10^-5 in and a safety factor of 77.64. The second attempt was the same design with default mesh setting. This resulted the design having a max stress of 3.502 MPA, a deflection of 3.242 x 10^-5 in, and a safety factor of 78.53. In order for the 2nd attempt to be accepted the results had to be within a 7% difference to converge. The convergence for design 1 was 1.1 % for both the safety factor and stress while the deflection was 2% so convergence was achieved with the 2nd attempt. The max stress was located on the left middle side of the fillets and the max deflection occurred at the bottom middle of the pin. The number of elements for this design during attempt 2 was 9705.

<img width="2560" height="1552" alt="Screenshot 2026-10-24 151222" src="https://github.com/user-attachments/assets/32252e65-94de-42b0-962d-95568d49e11d" />

## Design 2
The next task was to change the design and then run the process of the simulation again. Looking at my results I noticed that my safety factor was well over 3. Using the yield stress of 275 MPA, I divided the yield stress by 3 to give me a target of max stress which would be 91.67 MPa for the design to still meet the safety factor. I calculated a new diameter for the pin based on this target stress and the new diameter would be 0.36 in. As for all my other dimensions, I decided to reduce them by half of what their original measurements were to fit with the new pin diameter. I also decided to increase the fillets to 0.08 in to see how my results would change. Also due to the new diameter the pin was shorter than the base of the arm when it was originally larger so I added fillets on both middle ends of the pin to fit this new diameter. The new mass of the design was 0.05 lbs or 22.68 grams and the load, material and fixtures were to be applied the same as design 1. 

<img width="2560" height="1552" alt="Screenshot 2026-10-23 203056" src="https://github.com/user-attachments/assets/99432771-150d-40a6-95b9-12dd36d94487" />

<img width="2560" height="1552" alt="Screenshot 2026-10-23 203614" src="https://github.com/user-attachments/assets/5b1f7297-dcc9-4f4f-a1d6-f0b29fc620eb" />

<img width="2560" height="1552" alt="Screenshot 2026-10-23 204655" src="https://github.com/user-attachments/assets/8667e654-e0d7-4d59-9526-5e043c23aca7" />

For the first attempt of the second design, I once again chose the maximum coarse mesh and my results looked successful. The design tested a max stress of 13.17 MPa, a deflection of 7.775 x 10^-5 in, and a safety factor of 20.88. The 2nd attempt under the default mesh had a max stress of 13.32 MPa, a deflection of 7.613 x 10^-5 in and a safety factor of 20.65. The convergence for design 2 was once again 1.1% for the safety factor and the stress and now a 2.1% for the deflection so it was once again achieved in the 2nd attempt. The max stress was located at the middle right side the new middle fillet and the max deflection occurred at the same spot as design 1. The number elements for design 2 after the second attempt was 9107.

<img width="2560" height="1552" alt="Screenshot 2026-10-23 211622" src="https://github.com/user-attachments/assets/3396564a-99c0-49fc-afff-f537d900f1c3" />

<img width="4115" height="4347" alt="IMG_7522" src="https://github.com/user-attachments/assets/cdc6d86e-330c-4fe5-bbf5-31fb876fb2e5" />

## Design 3
For my third design I questioned why my targeted stress was not met. My safety factor was successfully lowered, but still significantly higher than 3. I decided to keep my diameter of 0.36 in for the pin and calculated a 66.35 % change from the original 1.07 in measurement. Using this information I reduced all design 1 dimensions by 66.35 % rather than half. I also reduced the fillet by this factor rather than increasing them and since the pin was larger than the base, the  fillets were applied in the same form as design 1 so I decided that middle fillets were not necessary. The mass of design 3 was now 0.02 lbs or 9.07 grams. Once again, I did not change the material nor the load of this design.

<img width="2560" height="1552" alt="Screenshot 2026-10-24 155049" src="https://github.com/user-attachments/assets/1eebb99b-7ac9-4782-bf3b-de891bcbb65b" />

For the first attempt of design 3, I once again chose the maximum coarse mesh which gave this design a max stress of 12.53 MPa, a deflection of 8.526 x 10 ^-5 in and a safety factor of 21.95. For Attempt 2, I used the default mesh which gave me a stress of 16.24 MPa, a deflection of 8.667 x 10^-5 in, and a safety factor of 16.93. Once again, my safety factor was still high but it was lowered from its original and my deflection also met the required constraint of 0.005 in. However, the convergence results were a 26% difference for the safety factor and the stress but the deflection was a 1.6% difference. Convergence was only achieved through the deflection of design 3. Since convergence was achieved through the deflection, a 3rd attempt was not needed. The amount of elements in design 3 after attempt 2 was 6596. The max stress occurred were left side of the arm meets the T structure and the max deflection occurred in the middle of the bottom of the pin. 

<img width="2560" height="1552" alt="Screenshot 2026-10-24 151249" src="https://github.com/user-attachments/assets/c1e24813-74ae-4cc8-b28c-3873a28576a5" />

<img width="3852" height="2978" alt="IMG_7524" src="https://github.com/user-attachments/assets/5c3e6bc7-3f70-4110-bf3a-c2b849e625f0" />

| Parameter / Metric | Design 1 | Design II | Design III |
| :--- | :--- | :--- | :--- |
| **Max Stress** | 3.502 MPa | 13.32 MPa | 16.24 MPa |
| **Max deflection** | 3.242 x 10^-5 in | 7.613 x 10^-5 in | 8.667 x 10^-5 in |
| **Mass** | 0.53 lbs | 0.05 lbs | 0.02 lbs |
| **Safety Factor** | 78.53 | 20.65 | 16.93 |
| **Number of elements** | 9705 | 9107 | 6596 |

# Lessons Learned
I learned how to create different meshes of my CAD Designs in SolidWorks and how the results change during each of my simulation attempts. The different results contributed to my ideas of what to change when modifying the mesh and the design. If I had done a 4th design I would try once again to lower my safety factor by reducing my diameter. If I reduced the new diameter the same way I did before it is likely that my safety factor would be much closer to 3. Thinking it over, I probably should have used the dimensions for design III as my 2nd design rather than reducing by 1/2, because it of how much it affected my results. I also could have changed the design based on the deflection rather than just focusing on the safety factor. I also learned how to create a table in github for this assignment since we had to store our values in a table. If I take out the breaks I took, it took me roughly 5 hours to complete this assignment.

CAD Design
https://github.com/Ryants745/MEGR-2156-Design-Lab-Portfolio/blob/main/docs/assignments/A07/bracket%20drawing.SLDPRT
