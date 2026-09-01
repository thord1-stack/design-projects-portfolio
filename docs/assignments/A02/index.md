# A2 – Truss Stress Analysis

## Objective
The objective of this assignment was to construct, analyze, and complete a Cad model of a truss system. This system had to be within parameters that were set at the beginning of the assignment. Below is a picture of the parameters that I followed. (a = 0.4 m, b = 0.3 m, point A is a pin, point B is a roller, and I picked P to equal 25 KN) 

![parameters](parameters)
## Analyze
![1stpage](truss1stpage)

This is where I began working on the assignment. I drew out the picture of the parameters and decided on a truss frame that I thought would be able to work according to the parameters. I also did some intial calculations and worked out some free body diagrams on this page also.
![jointspg1](joints1)
![jointspg2](Joints2)
![forcestruss](symbolicforcestruss)

This is where I spent a majority of my time working on this assignment. I beginning to struggle with keeping everything in symbolic terms instead of numbers but once I got the hang of it I started moving along. I found this part interesting because while working only with terms you start to notice that a lot of the terms cancel out before they reach the end of the problem. Then as you can see once I got all of the joints in symbolic terms I plugged all of the numbers in for the terms and solved the problems numerically. 

![trussweight](weightoftruss)

On this page I solved for the minimum cross sectional area of the truss. For the safety factor I used 3.5 as per the parameters listed in the assignment. To determine the weight of the truss I added all of the lengths up of the trusses and multiplied them by the cross sectional area I got in the previous step. Now that I had the volume I researched the weight of steel and multiple the volume by the weight (7,850 kg/m^3). This turned out to be 5.297 kg for the weight of my truss or 51.97 N.

![connectingpins](connectingpinFBD)

After those steps I then needed to determine the cross sectional area of the connecting pins. Which are made out of a hardened tool steel with a yield strength of 170 Ksi and a density of 0.278lb/in^3. Also according to the parameters I was to assume that all the elements in compression can not buckle. To calculate this I used a safety factor of 4. 

![cadtrussA](workingcadtruss)

After all of my calculations I headed over to Creo parametric and started working on the CAD model. I was instructed not to include the pins in this cad model and keep it to one single part. I made sure all of the cross sectional area still came out to the calculated amount of 203.21 mm^2. 

![trussfinal](finishedtrusscad)

The truss was completed to the parameters requested. The final weighted that Creo parametric calculated was 5.16 kg. So I was 0.13 kg off this could've been a rounding issue on my part while typing everything into the calculator. 

[Truss_Cad_File](https://github.com/thord1-stack/design-projects-portfolio/raw/refs/heads/main/docs/assignments/A02/trussdesign_tyh.prt.1)

## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._
I selected this geometry because it reminded me of bridges that you can see all around the world today. These bridges have to be strong and last for a long time in their environments so I decided I wanted to make my truss similar. Throughout my calculations it did turn out that truss CD didn't have any internal forces, so that truss wasn't necessary but I continued my calculations to the end.
## Communicate
This assignments made me work on my skills with keeping up with units. They're were many times where I had used KN when I was supposed to use N and it made me more aware at how important it is to keep up with. 

This assignment took me about 8 hours to complete.
