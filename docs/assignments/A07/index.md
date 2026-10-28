
# A7 – [Topic]

## Objective

Purpose of this assignment is to analyze bracket of A6 through the use of SolidWorks Simulation under loading. In this analysis I have done stress, deformation and a factor of safety calculations and modified this bracket accordingly


## Analyze

I used 6061 Aluminum Alloy with a 600 lbf downward force applied to the circular section. The upper mounting section was fixed in place.

Fixed geometry

![Screenshot 1 – Fixed Geometry](Screenshot1.png)

Applied Force

![Screenshot 2 – Applied Force](Screenshot2.png)

Design 1 - Original Bracket 

I created a static simulation and generated a mesh to analyze the original bracket. The highest stress occurred around the narrow connecting section.

Initial Mesh 

![Screenshot 3 – Initial Mesh](Screenshot3.png)

Stress Analysis

![Screenshot 4 – Design 1 Stress Analysis](Screenshot4.png)

Mesh Details

![Screenshot 5 – Mesh Details](Screenshot5.png)

Design 2 - First Modification

I added a fillet near the lower circular connection to reduce the stress concentration

Modified Bracket

![Screenshot 6 – Design 2 Geometry](Screenshot6.png)

Stress Analysis

![Screenshot 7 – Design 2 Stress Analysis](Screenshot7.png)

Design 3 - Second Modification

I added another fillet near the upper connection to create a smoother transition and improve the bracket's stress distribution

Final Bracket Geometry

![Screenshot 8 – Design 3 Geometry](Screenshot8.png)

Stress Analysis

![Screenshot 9 – Design 3 Stress Analysis](Screenshot9.png)

Displacement Analysis

![Screenshot 10 – Design 3 Displacement](Screenshot10.png)

Factor of Safety

![Screenshot 11 – Design 3 Factor of Safety](Screenshot11.png)

## Mesh Convergence

I tested coarse, medium, and fine meshes to examine how refinement affected the results

For Design 3:

- Coarse: 799.5 MPa stress, 0.8902 mm displacement, 1,899 elements
- Medium: 839.8 MPa stress, 0.9099 mm displacement, 7,912 elements
- Fine: 892.1 MPa stress, 0.9200 mm displacement, 64,322 elements

The medium-to-fine changes were approximately 6.23% for stress and 1.11% for displacement, meeting the 7% convergence criterion for Design 3.

## Decide

I compared the three designs to evaluate the effects of adding fillets

- Design 1: 1,048 MPa maximum stress, 1.277 mm displacement
- Design 2: 816.4 MPa maximum stress, 1.100 mm displacement
- Design 3: 892.1 MPa maximum stress, 0.9200 mm diplsacement

The fillets improved the geometric transitions, but the minimum factor of safety remained below 1. Further design changes would be needed to safely support the applied load.

These stress results were obtained using different mesh resolutions, so they are preliminary comparisions.

## Communicate

## Conclusion

This task allowed me to learn about how stress concentrations can be detected by means of FEA and about how the designs can be analyzed mechanically.

## Finite Element Analysis

In FEA, a model is divided into small elements in order to find the stresses and displacements. Mesh refinement allows finding out if the obtained resuts are accurate enough.

## Problems and What I Have Learned

The key problem was decreasing the stress concentrations and the effect of mesh refinement on the results. I have learned that even though adding fillets will alter the stress distribution, it does not mean that the bracket will become sstructurally sound.

## Time spent 

5 hours

## Cad File
