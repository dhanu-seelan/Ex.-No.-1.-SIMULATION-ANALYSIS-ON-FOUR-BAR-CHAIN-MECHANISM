# Ex. No.  - SIMULATION ANALYSIS ON FOUR BAR CHAIN MECHANISM

## DATE: 04/03/2026

## AIM:

###   To determine & simulate the displacement & velocity analysis for the given four bar chain mechanism. 

###   In a four bar chain ABCD, AD is fixed and is 120 mm long. The crank AB is 30 mm long and rotates at 100 rpm clockwise, while the link CD = 60mm oscillates about D. BC and AD are of equal lengths. ∟BAD = 600.

![image](https://github.com/Sellakumar1987/Ex.-No.-1.-SIMULATION-ANALYSIS-ON-FOUR-BAR-CHAIN-MECHANISM/assets/113594316/03952954-387e-4fd3-a1a0-a8dd4b82ae07)

## REQUIREMENTS:
###  ●	Mech Analyzer software.
###  ●	Processor: Minimum 1.5 GHz
###  ●	RAM: Minimum 512 MB
###  ●	Operating System: Windows XP, Windows Vista, Windows 7, Windows 8 or higher.
###  ●	Dependencies: Microsoft .Net 2.0 framework
###  ●	Mini Drafter.
###  ●	Geometry instruments.

## PROCEDURE:
## Step 1. Establishment of the Fixed Link (Base):
## Draw a horizontal line segment AD with a magnitude of 120 mm.
## Engineering Significance: In product development, this represents the "Fixed Link" or the "Ground" of the mechanism. Mark the endpoints clearly as A and D.
## Step 2: Angular Orientation of the Input Link:
## Position the protractor at vertex A. Measure and mark an angle of 60° relative to the horizontal line AD.
## Draw a line segment AB exactly 30 mm in length along this angular path.
## Step 3: Determining the Coupler Point (C) via Triangulation
## Since the position of point C depends on its distance from both B and D, we use the arc-intersection method:
## From Point B: Adjust the compass to a radius of 120 mm (Length BC = AD). Draw a thin construction arc.
## From Point D: Adjust the compass to a radius of 60 mm (Length CD). Draw a second arc that intersects the first one.Label the exact point of intersection as C.
## Step 4: Final Assembly of the QuadrilateralJoin the points B to C and D to C using a dark pencil (HB) to finalize the profile.Verify the connectivity of all four links (AB, BC, CD, AD) to ensure the quadrilateral is closed and follows the given constraints. 

![image](https://github.com/Sellakumar1987/Ex.-No.-1.-SIMULATION-ANALYSIS-ON-FOUR-BAR-CHAIN-MECHANISM/assets/113594316/a99fb530-e8df-49bf-9b2c-d537ff992534)

###   This value of VBA is used to decide the scale for the velocity diagram 
###   Let us construct the velocity diagram taking a scale: 
###   0.3141 m/s = 60 mm (say) 
###   1. The fixed link AD, appears as a point in the velocity diagram 
###   2. From a, draw ab = 60mm, perpendicular to AB in configuration diagram and in the direction of velocity (downward direction) 
###   3. From b, draw vector bc perpendicular to BC
###   4. From (a,d), draw vector cd perpendicular to CD. This will intersect the previous vector at c.  

<img width="508" height="296" alt="EX-01 Pictures" src="https://github.com/user-attachments/assets/f1dfdd15-789a-45c4-9912-c1545102264a" />


###   1. First measure cd from velocity diagram  
###   2. Now, Calculate VCd using the scale of the diagram 
###   3. Finally, calculate ωcd from the relation v = rω 
###   Thus, link CD revolves with ωcd = 4 rad/s (clockwise about D) 




## Output:
<img width="476" height="382" alt="EX-01 velocity simulation" src="https://github.com/user-attachments/assets/fc417d6c-14df-4c60-a080-6cc9d19c6510" />
<img width="469" height="263" alt="EX-01 Velocity variables" src="https://github.com/user-attachments/assets/8e6b9e5b-54ad-49b2-8d7c-a82a6fef7151" />
<img width="480" height="379" alt="EX-01 Acceleration Simulation" src="https://github.com/user-attachments/assets/c46e169e-8e48-4fea-80cf-9b7eea25773f" />
<img width="482" height="351" alt="EX-01 Acceleration Variables" src="https://github.com/user-attachments/assets/411825d5-8e18-4e51-b3e1-42763fc3cac3" />




### Name:Danaseelan G
### Register Number: 212225040053

## RESULT:
 ### Thus the displacement & velocity analysis for the given four bar chain mechanism is simulated.
