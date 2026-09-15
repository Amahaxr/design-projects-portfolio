# A4 – Motor Mount

 Objective/Description:
 Purpose of the Lab Activity. This lab activity sought to design a motor mounting which is going to be utilized in a brushed 24v DC gear motor which will be installed on a rigid wall. In designing the motor mounting, two main aspects were considered. Element 1 - the motor is held by this aspect. Element 2 - This aspect mounts the entire assembly to a rigid wall. Stress and deflection consideration were performed in designing the motor mounting and the safety factor adopted in this case is 3 while the maximum allowable dlefection at the free end of 0.30mm. Load on the motor shaft adopted for the design is 300N.

Design Requirments:
- Applied load: P = 300N
- Motor shaft length: 18mm
- Motor face diameter: Approximately 28mm
- Safet Factor: 3
- Maximum allowable deflection: 0.30,,
- Feature 1 width: 40mm
- Feature 2 width: 40mm
- M3 bolt clereance diameter: 3.4mm
- Shaft Clearance: 6.5mm
For the beam calculations, the material-property values used were
- Young's Modulus: E = 3500n/mm^2
- Yields strength: 50N/mm^2

Feature 1:
For Feature 1, I used a width and length of 40mm. The 300N load acting through the 18mm shaft created a moment of 5400N*mm. I first identified my knows and unknowns and created a free-body diagram of the feature.

![Part 1A Knowns and Unknowns](part1a.png)

![Part 2A Knowns and Unknowns](part2a.png)

I then used the beam bending equations to solve for the required thickness based on both maximum deflection and bending stress. The larger required thickness was used for the final design.

![Part 3A Knowns and Unknowns](part3a.png)

![Part 4A Knowns and Unknowns](part4a.png)

The calculations showed that deflection controlled the design, so I selected a final thickness of 11mm for Feature 1.

![Part 5A Knowns and Unknowns](part5a.png)

Feature 2:
For feature 2, I used the motor length and the thickenss of Feature 1 to determine the required length of the wall-mounted section. I then calculated the moment created by the 300N load and listed the knowns and unkonws for the design.

![Part 6A Knowns and Unknowns](part6a.png)

I created a free body diagram showing the loading and support conditions for feature 2.

![Part 7A Knowns and Unknowns](part7a.png)

I used the same beam bending approach as Feature 1 and solved for the required thickness using both deflection and stress. The deflection calculation controlled the design, so I selected a final thickness of 32mm for Feature 2.

![Part 8A Knowns and Unknowns](part8a.png)


![Part 9A Knowns and Unknowns](part9a.png)

Isometric Sketch:

I created and Isometric sketch of the motor mount using the dimensions calculated for Feature 1 and Feature 2. This sketch was used as a reference before creating the model in SolidWorks. 

![Part 10 Knowns and Unknowns](part10.png)














