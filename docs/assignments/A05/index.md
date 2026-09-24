# A5 – Bracket Design

## Objective
- Conduct stress analysis to determine appropriate dime
- Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.nsions for structural features.
- Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.
- Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.
- Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.
- Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.
- Reflect on and document key engineering lessons learned throughout the process.

## Analyze
### Stress
#### Feature A
I chose Aluminum 6061-T6 for my material and listed the yield strength of that in my knowns. I need to find the diameter of the feature A using stress analyzation. I assumed that the length of A was 1.5 inch, since there needs to be sufficient room to dangle a strap.
<img width="4278" height="3020" alt="IMG_1868" src="https://github.com/user-attachments/assets/787d6bf8-1169-48f4-8173-8475b77152ee" />
#### Feature B
I need to find the thickness of feature B, and I assumed that the width of feature B was the same as the diameter found in feature A, 0.972 in.
<img width="4283" height="2358" alt="IMG_1869" src="https://github.com/user-attachments/assets/06e9d8d8-9152-48a7-8a08-dc7ea6793e9b" />
#### Feature C
I need to find height, and I assumed the width of feature C was the same as the length of feature A and the length is the combined length of the given picture in the project, which was 2.4964 in.

<img width="392" height="251" alt="image" src="https://github.com/user-attachments/assets/ed0889c1-824c-412a-8059-5193ffe0225c" />
<img width="3924" height="2216" alt="IMG_1873" src="https://github.com/user-attachments/assets/ec970431-41cf-43bd-8302-26d6350b8728" />

#### Feature D 
I need to find height, and I assumed that the length of feature D was half the length of b in the provided image from the project instructions. 
<img width="4283" height="2242" alt="IMG_1874 (1)" src="https://github.com/user-attachments/assets/78d92a75-d6f7-45e7-9323-d8cf4ad6b5fd" />

#### Feature E
I need to find height, and I assumed that the length of feature E was the same length as b in the given image in instructions. 
<img width="4278" height="3027" alt="IMG_1875" src="https://github.com/user-attachments/assets/00d796bb-d313-4681-9300-f5ca8c82a3eb" />

### Stiffness
#### Feature A
I need to find diameter, and I chose the same length as the stress feature A.
<img width="4283" height="2153" alt="IMG_1876" src="https://github.com/user-attachments/assets/1810b0df-3f44-4407-97db-a2ae1ac882ca" />

#### Feature B
I need to find thickness, and I assumed that width is same as stiffness feature A diameter.
<img width="4283" height="1723" alt="IMG_1877 (1)" src="https://github.com/user-attachments/assets/467b506e-0791-4a38-913e-55f65ffe6b55" />

#### Feature C
I need to find height, and I assumed that the length is the same as in the stress feature C length. 
<img width="4283" height="2239" alt="IMG_1877" src="https://github.com/user-attachments/assets/fd721435-d0f2-4236-b4b5-4401fcd2341d" />
#### Feature D
I need to find height, and I assume that the length is the same as stress feature D length. 
<img width="4283" height="1843" alt="IMG_1878 (1)" src="https://github.com/user-attachments/assets/6d201ce9-bfa5-4be4-897c-789fdacb9825" />
#### Feature E
I need to find height, and I assume that the length is the same as stress feature E length.
<img width="4283" height="2085" alt="IMG_1878 (2)" src="https://github.com/user-attachments/assets/cbc3b94d-832a-4de7-9261-7dde9aea446d" />

### Sketches
#### Stress Multiview Sketch
There is a top, front, right, and isometric view and it is fully dimensioned out. 
<img width="4283" height="3375" alt="IMG_1882" src="https://github.com/user-attachments/assets/fd5ac863-bbbd-4a1d-af09-108d189c9899" />

#### Stiffness Multiview Sketch
There is a top, front, right, and isometric view and it is fully dimensioned out. 
<img width="4283" height="3053" alt="IMG_1883" src="https://github.com/user-attachments/assets/9ea65d7f-dd64-4887-8a5e-ef0f411bfe57" />

## Lessons Learned
- Governing Failure Mode: I learned that both stress and stiffness can govern the final dimensions of a uniform design, not just one or the other. For example, in feature A, stiffness governed the final dimension since 1.024 in was bigger than the stresses 0.972 in. However, in feature C, stress governed the final dimension with 0.387 in. Though these values are very close to each other, it is still crucial to insure you choose the right dimensions to avoid failure.
- Error Propagation: I found myself needing dimensions that I had solved for in the features prior, just like in feature A where I used the diameter that I found as the length of feature B. Throughout my calculations, I didn't mix up or misplace any values, to my knowledge, and this is most likely due to me always organizing my knowns and unknowns.
- Assumption Sensitivity: One assumption that I made that can change every value that I got was the material selection. I chose to use aluminum 6061 T6, but if I chose steel or titanium instead, the yield strengths and modules of elasticity would be drastically different. This would undoubtably change every calculation I have made throughout this entire project. 
