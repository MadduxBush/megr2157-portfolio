# A4 – Motor Mount

## Objective
Design a motor mount with two features taking account for yield strength and maximum deflection. For both features, the maximum deflection is 0.3mm, the safety factor is 3, and the material is ABS. After calculating all the dimensions, sketch the final design as an isometric view and 3D model it in SolidWorks.
Image of the motor reference that was used for this project. 
<img width="714" height="227" alt="image" src="https://github.com/user-attachments/assets/220a4681-0491-4893-9df0-c39c5ccc3624" />

Image of what motor with the motor mount should look like.
<img width="134" height="113" alt="image" src="https://github.com/user-attachments/assets/8de480a2-b582-4730-b607-1f4212d0893c" />

## Feature 1
The motor body has a diameter of 22mm, so I chose my length and wide of feature 1 to be 36 mm to insure there are no clearance issues when inserting the motor to the mount. This length does not account for what the second feature will add in the future. After deciding the length and wide of feature 1 I can find the height through beam bending equations. I first solved the equations symbolically, but after getting my numerical solutions, I found that the stiffness height was larger than the strength, so I will use the stiffness height of 15.39mm. 
<img width="3024" height="4032" alt="IMG_1845" src="https://github.com/user-attachments/assets/a6de3851-3c05-47d3-89ad-fb017cf05c8a" />

## Feature 2
Since I chose to keep the same length and width dimensions I used in feature 1, no numbers were changed for the known parts from figure one to figure two, so this made the calculation process very similar to figure 1. The only difference was the location of the moment. After finding the thickness needed for both the strength and stiffness, I found that stiffness was once again bigger than strength, so I used 36.97mm as my thickness for figure 2.
<img width="3024" height="4032" alt="IMG_1846" src="https://github.com/user-attachments/assets/86a4a62e-a726-4ef6-8cba-f311b3b4cab6" />

## Isometric view has dimensions of screw holes for feature two that I have chosen to work best for this design, with every other measurement labled as well.
<img width="3024" height="4032" alt="IMG_1847" src="https://github.com/user-attachments/assets/78a0dcf2-1d91-498b-ad4a-eb026201af21" />

## CAD
To make this I first sketched the bottom of feature 1 then extruded. Then I added the body of feature two by sketching and extruding. Then cut appropriate size holes by sketching then extrude cutting on both features. 
<img width="1059" height="774" alt="image" src="https://github.com/user-attachments/assets/4a99334b-deb1-4301-a4a3-29c6f11fb0e2" />
## CAD Drawing
I projected the three main views, and every view was dimensioned appropriately with internal holes shown as dotted lines. The only part I couldn't figure out was the isometric view. The one in my drawing is upside down to what I visioned in my head. In the bottom right, there is the needed information about the drawing.
<img width="1371" height="974" alt="image" src="https://github.com/user-attachments/assets/d555fdc1-ac37-4ab3-bf24-ce92e0d683d2" />


### CAD Links
Part: https://studentuncc-my.sharepoint.com/:u:/r/personal/mbush18_charlotte_edu/Documents/SoDesign/A4%20SoDesign.SLDPRT?d=w42cc331a0faf461f82fac554ae38148f&csf=1&web=1&e=ZbcixK
Drawing: https://studentuncc-my.sharepoint.com/:u:/r/personal/mbush18_charlotte_edu/Documents/SoDesign/A4%20SoDesign%20Drawing.SLDDRW?d=wd20b0febdaf049459bffb22d770ebed1&csf=1&web=1&e=UPBZFC

