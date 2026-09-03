# A2 – Truss Stress Analysis

## Objective
I was tasked to design, 3-D model, and calculate internal forces of a truss. This is what I had to base my truss on. 

<img width="355" height="239" alt="image" src="https://github.com/user-attachments/assets/c4bd457b-b334-4978-aecd-1ee156f1c622" />


## Analyze
The first step for this project is to draw the truss that I want to build with the diagram that was offered in the instructions. I decided to make two symmetrical triangles with a new joint at point E to achieve the symmetry. Then I made a key to associate the letters in my truss drawing to numbers, and since P could be between 20-30, per the instructions given, I chose to go in the middle with 25kN. The next step was to draw free body diagrams of all the joints and to solve for the internal forces of the truss. To solve the internal forces, I first found the unknown forces of A and B by taking the moments of A and B. It is worth noting that point A is a pin, so it has two unknowns, while point B is a roller and only has one unknown. After all the unknown forces where found, I found the internal forces of the left most joints to the right most joints. 

<img width="4284" height="5712" alt="IMG_1803" src="https://github.com/user-attachments/assets/f6c13f87-45c0-42a2-a510-a3a646d73030" />


I first listed my knowns and unknowns to help determine what I needed to solve for. The truss is built with A500 structural steel, with a yield strength range from 235 MPa to 345 MPa, and since the instructions didn't specify the exact yield strength I chose 300 MPa. I then decided to solve for cross sectional area. This calculation then helped me with the weight calculation I did after.

<img width="3019" height="1826" alt="IMG_1805" src="https://github.com/user-attachments/assets/2614d8ae-e9b3-4508-9619-01574f6f0c1e" />
 
I first listed my knowns and unknowns to help organize my work and to determine what I need to solve for. The pins are made of hardened tool steel, and the yield shear strength and density were given in the instructions. I first solved for the cross sectional area of the pin, which was important in the weight calculation I did after. 

<img width="3019" height="2055" alt="IMG_1806" src="https://github.com/user-attachments/assets/7ea1181b-cc34-49e2-a3da-15618c667797" />

After finishing with all the calculation of the truss, I moved onto designing this truss in Creo. I first sketched the parameter of the truss. Then I extruded the drawing by 20mm for the width of the truss, then I cut triangles into the drawing making sure that the total area of the truss stayed around 222.67mm^2. I then cut holes where the pins should go making sure each one has diameter of 9.33mm. 

<img width="1835" height="688" alt="image" src="https://github.com/user-attachments/assets/c5f702a4-35f9-4e93-aca7-d0b7311be6fa" />

I then moduled the pin by extruding a circle of 9.33mm in diameter by 20mm.

<img width="793" height="797" alt="image" src="https://github.com/user-attachments/assets/abe50a5f-17f6-4ac8-b416-055434ef7649" />

Unfortunately, I could not find A500 structural steel in the materials list in Creo, the closes thing I found was just steel, so the measurements are very inaccurate compared to what I found. 

<img width="1753" height="686" alt="image" src="https://github.com/user-attachments/assets/2ce02f76-dfc3-4f08-acb7-4fa1c643ba44" />

## Communicate
During this assignment, I learned how to optimize the structure of a truss using geometry and load distribution. The calculation of the internal loads showed how optimizing structure ensures that every bar bears the stress and strains relatively equally instead of an extreme bias to one support or side. This assignment also showed the importance of safety factors, since they set the boundaries for the allowable stress. I also found that calculating the single shear stress that the pins underwent showed how the high strength material that it was made of allowed it to have a minimal corss-sectional pin area, while also reducing the truss's mass. 

## Likelihood of Failure Modes in Truss Components
# Part 1
When it comes to the truss, I designed the compression members are prone to bucking, while the tension members are prone to yielding. A500 Steel is more ductile than it is brittle. For compression members I chose bucking as the most likely thing to happened because the beams of steel are very thin and this will fail under compression way before the yield stress. I chose yielding for the tensile loads because the truss is being pulled without lateral support and this will lead to plastic deformation. To prevent bucking and tensile yielding, use a stronger material that can withstand the constant compression.

# Part 2
The expected failure mode of pin is the direct single shear failure. I the Module 03 Truss Study of PressBooks, they have pictures and explain how shear failure in a pin is more common than other pin failures. If the single shear joint is replaced with a double shear connection, then the load would be across two planes, doubling the load capacity. 

## Sources Cited 
https://www.redriver.team/the-4-modes-of-failure/ 
https://www.tottentubes.com/astm-a500-specification-information 
https://www.linkedin.com/advice/0/what-most-common-methods-preventing-buckling-2omoc
https://saalck.pressbooks.pub/structuralconceptsforarchitectsandconstructionmanagers/chapter/module-3-truss-study/
