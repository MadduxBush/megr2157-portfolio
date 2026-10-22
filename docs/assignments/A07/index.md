# A7 – FEA on Bracket

## Objective
In this assignment I have to perform a finite element analysis (FEA) on the bracket I designed in A06. I must complete 3 different FEA and after each test I had to optimize to get a balance of lightweight, strength and stiffness. 

## Analyze
To complete a FEA on my bracket there is a specific list of loops that I have to follow. There is first an outer loop of getting my part into FEA processing and after there is an inner loop of running the FEA in both coarse mesh and medium mesh. This loop stops if the results of the coarse and medium mesh converge within 7 precent, or after running the FEA with the fine mesh setting. This inner loop will only loop a maximum of three times, and after the inner loop is done the outer loop can finish which is just optimizing the bracket and starting the outer loop again. This outer loop will only happen twice for this assignment. Below is the chart I referenced to complete my FEA. 
<img width="420" height="454" alt="image" src="https://github.com/user-attachments/assets/0de7d51c-5dc8-4730-9633-f2a30d6a99ad" />


## Decide
To start my FEA I first get my bracket ready for testing by fixing the inner part of my bracket since that was where it is going to sit and be stationary. I then applied downward force on the cylindrical overhand of the bracket since there is where the force will be when you hang a heavy rope over it. The force used was 600lbs and the material that the bracket is made of is aluminum 6061-T6, and this information came from assignment 5. 
### Design 1
<img width="1475" height="902" alt="image" src="https://github.com/user-attachments/assets/737ded90-7e1f-4fd2-88e2-101d1fd3ad0e" />
<img width="1461" height="856" alt="image" src="https://github.com/user-attachments/assets/b66ed1c3-abe6-4dd0-b6b9-e71aa35acca9" />
These are the results after the coarse mesh FEA.
<img width="1457" height="803" alt="image" src="https://github.com/user-attachments/assets/f003b8e5-d2b4-46e3-b839-dce5631d386e" />
<img width="1428" height="857" alt="image" src="https://github.com/user-attachments/assets/d34c2786-f422-476f-988b-5bd93e2e93da" />
These are the results after the medium mesh FEA. Both the coarse and medium mesh FEA's show that there is too much stress at feature B and too much displacement at the end of feature A. After solving for the convergence for these two FEA, I found that these two do not meet the 7% convergence requirement to end the inner loop, so a third test is needed at a fine mesh. 
<img width="1423" height="811" alt="image" src="https://github.com/user-attachments/assets/b8c7d03f-6818-4f8a-b234-8c5743b233ce" />
<img width="1416" height="865" alt="image" src="https://github.com/user-attachments/assets/4a03f60f-abff-421f-ad13-662d7e4e249d" />
After the third and final FEA, it is clear to see that the stresses and displacement are too high to have this be the final product the outer loop must run another time. This means I must redesign this to minimize the stress and displacement while also being mindful about the weight. 

### Design 2

<img width="977" height="724" alt="image" src="https://github.com/user-attachments/assets/15e1039e-7060-449d-84c1-3b3e8301fd32" />
For the new design I rounded the edges of the top part of the bracket, and I also cut two holes that go complete through both sides of the bracket mount. I did this since the FEA showed that there was no stress that was acting on the top part, so it is good to reduce the weight of the part by removing excess material that is not being used to help strengthen the part. I also added a triangle support that connects the bottom of feature C to the front face of feature B to help support feature B and reduce the stress on it.
<img width="1690" height="1146" alt="image" src="https://github.com/user-attachments/assets/5c0de9fe-7813-498f-bfaf-2e48296f9d80" />
<img width="1582" height="1130" alt="image" src="https://github.com/user-attachments/assets/5a700de0-7ca0-41c8-bc92-3ed7ac315558" />
These are the results of the coarse mesh FEA
<img width="1844" height="935" alt="image" src="https://github.com/user-attachments/assets/537d9f27-d1a8-4635-afc1-a9e8cccf2ce9" />
<img width="1854" height="908" alt="image" src="https://github.com/user-attachments/assets/0d578bdf-41a3-4e7c-8f54-0a9fe770130a" />


These are the results of the medium mesh FEA. After running the coarse and medium mesh FEA, I can already tell that these changes helped drastically improve strength of this bracket will also reducing the weight of it too. Even with these improvements to the design the convergence is still not below the 7% that is needed to end this inner loop, so a third FEA is required. 
<img width="1734" height="853" alt="image" src="https://github.com/user-attachments/assets/964994ae-8797-46cf-b0ca-bfa43b931639" />
<img width="1748" height="776" alt="image" src="https://github.com/user-attachments/assets/9727b49b-74a9-41d5-a826-eb5ac521e796" />
Though these results do surpass the first design they do still fall short of minimum required safety factor and the displacement is still too high. This means that a third outer loop is required to further the optimization.
### Design 3
<img width="1024" height="830" alt="image" src="https://github.com/user-attachments/assets/91655d97-d834-4804-9213-da1a633a2aea" />
For the new design I decided to add more support to feature A to negate the deflection and to help take some more load off of feature B. Though this design does increase the weight of the last design, the amount of stress and deflection negation is worth it. 
<img width="1524" height="914" alt="image" src="https://github.com/user-attachments/assets/b6f5e60d-3df9-46d3-96db-4823b0e7ee3e" />
<img width="1471" height="907" alt="image" src="https://github.com/user-attachments/assets/55ca7209-f3f0-4c27-8cbf-c5180b2a7607" />
These are the results of the coarse mesh FEA
<img width="1553" height="842" alt="image" src="https://github.com/user-attachments/assets/6c9337cc-ba1c-412f-8efb-aebb357d0f80" />
<img width="1403" height="825" alt="image" src="https://github.com/user-attachments/assets/342110d0-92a9-4a27-8bd0-2b9e2dc3b311" />
These are the results of the medium mesh FEA. After running the coarse and medium mesh FEA, there was a big decrease in max stress on feature B, and the deflection of A was reduced too. Though these improvements are great, they do not converge so a third FEA is needed. 
<img width="1585" height="1025" alt="image" src="https://github.com/user-attachments/assets/6edafd4c-85fb-4c54-a48a-5958f90be1a1" />
<img width="1472" height="961" alt="image" src="https://github.com/user-attachments/assets/88c6e48a-7157-4b17-91ea-8b6ddb2fb4ec" />
These results of the third FEA show that this is the best design of the bracket, since this is the only bracket design that is in the safety factor range, it has the lowest stress max, and lowest deflection. 

## Reflection
After completing the three outer loops of the FEA workflow, I have found that the hardest part is trying to optimize for a balance of strength, deflection, and weight. I know that my design is far from the best that there could be but it's important to know when to stop optimizing and that is something that this assignment has taught me. I have also learned how to change mesh sizing, and I have gotten to see how this affects the max stress and deflection that can be calculated in a FEA. 

### Link to Bracket Design: 
"C:\Users\maddu\OneDrive - University of North Carolina at Charlotte\SoDesign\A6 Part SoDesign.SLDPRT"
