# A5 – Bracket Design

## Objective
Designing a bracket that will satisfy both the strength and stiffness requirments through stress analysis, deflection analysis, and free body diagram was the aim of this exercise.

## Analyze

### Part 1 - Stress Analysis

![Part 1 Page 1](page-01.png)

![Part 1 Page 2](page-02.png)

![Part 1 Page 3](page-03.png)

![Part 1 Page 4](page-04.png)

![Part 1 Page 5](page-05.png)

![Part 1 Page 6](page-06.png)

![Part 1 Page 7](page-07.png)

![Part 1 Page 8](page-08.png)

![Part 1 Page 9](page-09.png)

![Part 1 Page 10](page-10.png)


### Part 2 - Stiffness Analysis

![Part 2 Page 1](page-11.png)

![Part 2 Page 2](page-12.png)

![Part 2 Page 3](page-13.png)

![Part 2 Page 4](page-14.png)

![Part 2 Page 5](page-15.png)


## Decide

### Part 3 - Multiview Sketches

#### Stress Analysis Multiview Sketch

![Stress Multiview Sketch](page-16.png)

#### Stiffness Analysis Multiview Sketch

![Stiffness Multiview Sketch](page-17.png)

## Lesson Learned

4. Governing Failure Mode

Feature C needed a minimum thickness of 0.80 in for the stress analysis, while it required approximately 0.343 in for the stiffness analysis.
The difference was:

0.80 - 0.343 = 0.457in

Thus, the final dimension was governed by the stress condition and was approximately 0.457 in larger.

5. Error Propagation

An example of an error propagation is when there was an error in calculation of Feature A dimension and thus Feature B dimensions because Feature A dimension was used in determining the dimensions of Feature B.
Checking every result before its use for the next feature allows avoiding such problems.

6. Assumption Sensitivity

The one assumption which was very important in calculations was location and distribution of the load. 

For Feature A, the load location was assumed according to the position of the strap. IF the actual load acts further away from the support point than assumed, the bending moment and deflection would increase and this a larger Feature A diameter would be required to satisfy both the stress and stiffness condtions
