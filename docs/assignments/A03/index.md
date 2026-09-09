# A3 – Parametric and FEA

## Objective
Use axial deflection modeling to design its dimensions
Use parametric design to determine a bars length
Introduce you to FEA (Finite Element Analysis)
Introduce you to linking dimensions to appropriate parameters in CAD.
Compare and contrast the different analysis


## Analyze
I first made my calculations of area, length, and weight of bar using given measurements and measurements that I chose to use. I decided that the bar will be made of Aluminum 6061-T6, since it fits in the allowable Young's Modulus of (8.5-11.5) X 10^6. I also decided that the load (F) would be 400lbs since it the middle of allowable load that was given. 
<img width="3024" height="4032" alt="IMG_1816" src="https://github.com/user-attachments/assets/79d91e6d-e70e-4657-903d-50ac7cdfe843" />

### Cad
I first imported my equations and values into the global equation manager in SolidWorks. This allowed me to sketch a circle with dimensions that are linked with the diameter value in the global equation manager. I then extruded the circle by a length that was linked with the length equation used in the global equation manager. 
<img width="1280" height="533" alt="image" src="https://github.com/user-attachments/assets/fea950ca-1bd4-4ab0-b360-853910b8e8a6" />

Material selected in SolidWorks was the aluminum 6061, the same one I used in my calculations.
<img width="611" height="481" alt="image" src="https://github.com/user-attachments/assets/c3616a1f-f901-44e3-ad2d-9387acb1b7e5" />

### FEA Simulation
For the FEA Simulation I decided to fix the left side of the bar, indicated by the green points, and I added the forces on the right side of the bar, indicated by the purple arrows. 
<img width="1280" height="502" alt="image" src="https://github.com/user-attachments/assets/afc2295a-4653-421f-80d2-e8283176967e" />

After running the simulation, it created a Von Mises stress curve table and this table says the max stress that the bar experienced was only .5592ksi while the allowed stress was 40ksi. 
<img width="1280" height="560" alt="image" src="https://github.com/user-attachments/assets/e461ea8c-9e73-41f4-8a24-2e6e810d1586" />

The safety factor that was calculated with these numbers was 71.5308.
<img width="3018" height="1227" alt="IMG_1820" src="https://github.com/user-attachments/assets/090c51f9-41da-4d95-9eea-3336051bb1c9" />

I then went to the displacement chart, and this told me that the max axial deflection was .009027 inches, which is very slightly over the given max for this assignment.
<img width="1248" height="563" alt="image" src="https://github.com/user-attachments/assets/baaf8a46-2d03-4e52-87da-96d1cfeefb54" />

The percent difference between the two is only 0.3%. This low percentage difference is expected since both my hand calculations and the CAD calculations used the same measurements and material properties. The small discrepancy could be caused by rounding errors or small differences in the material properties numbers. 
<img width="3023" height="1018" alt="IMG_1821" src="https://github.com/user-attachments/assets/8f027cda-1d1d-4a1b-a12d-2cfc17fc64c2" />


## Decide


## Communicate

