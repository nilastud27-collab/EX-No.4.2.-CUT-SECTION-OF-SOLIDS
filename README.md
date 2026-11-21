# EX No.4.2. CUT SECTION OF SOLIDS
## DATE: 05.11.2026

## AIM: 
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

## Step 1: Initial Setup 
1. Open Autodesk Fusion 360 and start a new design (File > 
New Design). 
2. In the Browser tree on the left, expand Document Settings 
and set the active units to Inches (in) (or Millimeters (mm) as 
per lab standard).

## Step 2: Sketch the Axis and Base Profile 
1. Select Create Sketch and choose the XZ Plane (Front plane). 
2. Draw a vertical Construction Line (L, then press X) upward 
from the origin (0, 0) of length 3.520 to serve as the center 
axis of revolution. 
3. Draw the base and stem profile to the left of the centerline: 
○ From the origin, draw a horizontal bottom line to the left 
of length 1.366. 
○ Draw a vertical line upward at the outer edge of height 
0.148. 
○ Draw a line tapering inward to a radius of 0.123 from the 
centerline to form the base foot. 
○ From that point, draw a vertical line upward for the stem 
up to a total height of 1.501 from the bottom baseline.

<img width="632" height="547" alt="Screenshot 2026-11-05 101323" src="https://github.com/user-attachments/assets/c52c11cd-c176-46d4-a5c7-7551faa9147d" />

## Step 3: Sketch the Bowl Profile 
1. At the top height of 3.520, locate the inner rim edge at a 
horizontal distance of 0.721 to the left of the centerline, and 
draw a horizontal line to the left of length 0.148 for the rim 
thickness. 
2. Select Create > Arc > Center Point Arc (or 3-Point Arc): 
○ Place the arc center at a vertical distance of 1.986 above 
the stem top (1.501 height). 
○ Draw the inner bowl curve with radius R2.261 
connecting the inner rim edge (0.721 from axis) down to 
the stem axis at height 1.501. 
○ Draw the outer bowl curve with radius R2.113 
connecting the outer rim edge down to the outer stem 
line (0.123 from axis). 
3. Verify that the entire cross-section forms a single closed loop 
and click Finish Sketch.

<img width="467" height="275" alt="Screenshot 2026-11-20 001901" src="https://github.com/user-attachments/assets/796a7b5b-37e0-45c7-856b-982e67d182c3" />

4. Trim the excess circle according to the sketch.

<img width="450" height="286" alt="Screenshot 2026-11-20 001956" src="https://github.com/user-attachments/assets/50031ac7-353f-4ec0-81e0-d8509beec245" />

## Step 4: Revolve the Solid Model 
1. Select Create > Revolve. 
2. Choose the closed cross-section profile as the Profile. 
3. Select the vertical centerline as the Axis. 
4. Set Type to Full (360°), Operation to New Body, and click OK.

<img width="457" height="287" alt="Screenshot 2026-11-20 002032" src="https://github.com/user-attachments/assets/0b59d3f2-62fc-4171-addc-002f0f6e7c9b" />

## Step 5: Create the Cut Section(To check) 
1. In the top toolbar, go to Inspect > Section Analysis. 
2. Select the XZ Plane (or YZ Plane) passing through the 
center of the goblet as the cutting plane. 
3. Adjust the section direction if needed and click OK to view 
the internal cut section of the solid model.

<img width="453" height="653" alt="Screenshot 2026-11-20 002716" src="https://github.com/user-attachments/assets/945ecfaf-6055-411d-aebc-67a6695a7697" />

## INPUT:

![image](https://user-images.githubusercontent.com/113594316/199409656-c021c100-857a-4ae4-9752-9ae59465c9c2.png)

## OUTPUT:
<img width="477" height="498" alt="Screenshot 2026-11-11 220707" src="https://github.com/user-attachments/assets/db343286-99bc-435b-911b-8534b2d2f6b6" />
<img width="953" height="668" alt="Screenshot 2026-11-11 220747" src="https://github.com/user-attachments/assets/4fdcb447-b47a-4326-8cb0-413356e28af0" />

## RESULT:
Thus, the cut section for solid model is created.
ILANILA VINNARASI.K.V
26017175
05.11.2026



