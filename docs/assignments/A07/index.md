# A7 – FEA on Bracket

## Objective

After a break a long break, this week I was tasked with doing a FEA simulation on the bracket that was created for the previous 2 assignments.

## Design 1
The constraints for this bracket included that it need to meet a safety factor of 3 or higher, a maximum deflection under 0.005 in and assigned a load between 500 and 800 lbf. In my initial design I used 600 lbf force on the bracket and doubled it on the pin or Feature A. This ultimately gave me the diameter of the pin which was 1.07 in. So I applied a load of 1200 lbf to the pin and applied fixed geometry to back face of the T structure as well as the inside faces of the T sturcture. The mass for design 1 was 0.53 lbs or 240.4 grams and the material is Aluminum T6 6061 which was the original material that I assigned to the bracket. For the first simulation attempt I chose the maximum coarse mesh on the bracket. The results of the first attempt showed that the bracket had max stress of 3.542 MPA, a deflection of 3.308 x 10^-5 in and a safety factor of 77.64. The second attempt was the same design with default mesh setting. This resulted the design having a max stress of 3.502 MPA, a deflection of 3.242 x 10^-5 in, and a safety factor of 78.53. In order for the 2nd attempt to be accepted the results had to be within a 7% difference to converge. The convergence for design 1 was 1.1 % for the safety factor and stress and a 2% for the deflection so convergence was achieved with the 2nd attempt. The max stress was located on the left middle side of the fillets and the max deflection occurred at the bottom middle of the pin. The number of elements for this design during attempt 2 was 9705.

<img width="2560" height="1552" alt="Screenshot 2026-10-24 151222" src="https://github.com/user-attachments/assets/32252e65-94de-42b0-962d-95568d49e11d" />

## Design 2
The next task was to change the design and then run the process of the simulation again. Looking at my results I noticed that my safety factor was well over 3. using the yield stress of 275 MPA I divided the yield stress by 3 to give me a target of max stress which would be 91.67 MPa for the design to still meet the safety factor. I calculated a new diameter for the pin based on this target stress and the new diameter would be 0.36 in. As for all my other dimension I decided to reduce them by half of what their original measurements were to fit with the new pin diameter. I also decided to increase the fillets to 0.08 in to see how my results would change. Also due to the new diameter the pin was shorter than the base of the arm when it was originally larger so I added fillets on both middle ends of the pin to fit this new diameter. The new mass of the design was 0.05 lbs or 22.68 grams and the load, material and fixtures were to be applied the same as design 1. 

<img width="2560" height="1552" alt="Screenshot 2026-10-23 203056" src="https://github.com/user-attachments/assets/99432771-150d-40a6-95b9-12dd36d94487" />

<img width="2560" height="1552" alt="Screenshot 2026-10-23 203614" src="https://github.com/user-attachments/assets/5b1f7297-dcc9-4f4f-a1d6-f0b29fc620eb" />

<img width="2560" height="1552" alt="Screenshot 2026-10-23 204655" src="https://github.com/user-attachments/assets/8667e654-e0d7-4d59-9526-5e043c23aca7" />

For the first attempt of the second design I once again chose the maximum coarse mesh and my results looked successful. The design tested a max stress of 13.17 MPa, a deflection of 7.775 x 10^-5 in, and a safety factor of 20.88. The 2nd attempt under the default mesh had a max stress of 13.32 MPa, a deflection of 7.613 x 10^-5 in and a safety factor of 20.65. The convergence for design 2 was once again 1.1% for the safety factor and the stress and now a 2.1% for the deflection so it was once again achieved in the 2nd attempt. The max stress was located at the middle right side the new middle fillet and the max deflection occurred at the same spot as design 1. The number elements for design 2 after the second attempt was 9107.

## Design 3


# Lessons Learned

