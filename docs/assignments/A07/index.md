# A7 – [Topic]

## Inner Loop
I could not get my results to convert on 7% even after 3 different tries. Below are pictures of my Cad Models and FEA's.
![Bracket](Stress)
![Bracket](Displacement)
## Outer Loop
Once on the outer loop I started changing my geometry for example adding another side to the arm so it isn't a cantilever beam and it is supported from both sides. Another example of something that I eventually changed was adding rounded corners so that less stress would build up on the pointy corners.

![Bracket](stress2)
![Bracket](Displacement2)
![Bracket](Stress3)
![Bracket](Displacement3)
## Table and Cad Model
![Bracket](table)

Cad Model: [bracket](bracket2_tyh.prt.1)
## Reflection
This assignment took about 3 hours to complete. I went back several times to try to get the results to merge on the inner loop but couldn't figure out how to make them merge after 3 times so I moved onto the outer loop. In the outer loop I first got a deflection of 66 inches which didn't sense so that was the first thing I changed in the outer loop. I changed it from a cantilever beam to a beam supported on either end and that alone reduced my deflection to 0.00359 in. It did increase the mass slightly. After that I rounded all of the corners to reduce some stress from the sharp corners. This for some reason didn't reduce stress it actual raised it from 1.090x10^7 to 1.733x10^7(lbm/insec^2). After realizing this I still am unsure why this would raise the stress but I then got rid of the rounded corners to reduce the stress again.

