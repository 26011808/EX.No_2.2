EX. NO.-2.2
CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING

AIM:
To create a 3D model from the given isometric drawing using Fusion 360 tool.

REQUIREMENTS:
 * Autodesk Fusion 360
 * Windows 10
 * 16 GB of RAM (integrated graphics recommended 1 GB or more)
 * (2.5 Mbps) or faster download; 500 Kbps or faster upload
 * 
PROCEDURE:
Step 1: Environment Setup
 * First, open the CAD software and create a new Part File (.prt or .sldprt).
 * Set the unit system to MMGS (Millimeter, Gram, Second).
 * 
Step 2: Modeling the Base Plate
 * Select the Top Plane and open a new sketch.
 * Draw two circles with a diameter of 16 mm (Ø16), keeping them equally spaced along the centre axis.
 * Draw concentric outer arcs with a radius of 18 mm (R18) and maintain the given spacing of 56 mm between the circle centres.
 * Connect the outer arcs using tangent lines to form the slot-shaped base outline.
 * Finally, use the Extrude Boss/Base command to extrude the sketch upwards to a height of 8 mm.

 <img width="887" height="572" alt="Screenshot 2026-11-26 091232" src="https://github.com/user-attachments/assets/b25fed52-f8f4-49a0-974c-f72e66cd07cb" />

Step 3: Modeling the Vertical Block
 * Select the top surface of the base plate and create a new sketch.
 * Draw a rectangle with a width of 40 mm and a thickness of 10 mm.
 * Set the height of the vertical block to 32 mm above the base plate.
 * Apply Extrude Boss/Base to create the solid vertical support.
 * 
   <img width="883" height="332" alt="Screenshot 2026-11-26 091251" src="https://github.com/user-attachments/assets/8553c5bc-e4f4-4de9-9a72-bbc322bf55e1" />

Step 4: Creating the Triangular Support Rib (Stiffener)
 * Select the Right Plane or the centre symmetry plane of the part.
 * Create a sketch and draw a right-angled triangle connecting the vertical block to the top surface of the base plate.
 * Select the Rib Feature or Extrude Mid-Plane option.
 * Set the rib thickness to 12 mm.
 * Click OK to create the triangular support rib.

   <img width="891" height="436" alt="Screenshot 2026-11-26 091325" src="https://github.com/user-attachments/assets/55fd8ae7-6535-48f2-9000-d7a79694a6b6" />

Step 5: Modeling the Upper Cantilever Arm
 * Select the front face of the vertical block and create a new sketch.
 * Draw a rectangle with the following dimensions:
   * Extension length: 32 mm
   * Height/Thickness: 10 mm
   * Width: 40 mm
 * Make sure the arm extends horizontally forward from the vertical block.
 * Apply Extrude Boss/Base to create the solid horizontal cantilever arm.
 * Click OK to complete the feature.
   
Step 6: Modeling the Upper Cylindrical Boss & Center Hole
 * Select the top surface of the upper cantilever arm and create a new sketch.
 * Draw a circle of diameter 30 mm (Ø30) at the front end of the arm.
 * Apply Extrude Boss/Base and extrude the circle upwards by 10 mm.
 * Select the top face of the new cylinder and create another sketch.
 * Draw a concentric circle of diameter 20 mm (Ø20).
 * Select Extruded Cut and set the end condition to Through All.
 * Click OK to create the central hole.

   <img width="941" height="490" alt="Screenshot 2026-11-26 091353" src="https://github.com/user-attachments/assets/069b9cbd-b4da-4fb8-99c8-4a99202d8261" />

   
Step 7: Final Inspection & File Saving
 * Check the Feature Tree to ensure all features are properly created and sketches are fully constrained.
 * Verify all dimensions with the original engineering drawing.
 * Apply the required appearance or material, such as Magenta/Purple colour, if needed.
 * Check the final 3D model from different views to ensure there are no errors.
 * Click File -> Save As.
 * Enter the file name as Mechanical_Bracket.SLDPRT.
 * Select the required folder and click Save.

OUTPUT:
<img width="1008" height="707" alt="Screenshot 2026-11-22 180400" src="https://github.com/user-attachments/assets/56c92996-9525-434e-9ebf-59ceb9cec6f7" />

<img width="907" height="682" alt="Screenshot 2026-11-22 182653" src="https://github.com/user-attachments/assets/16ee1fda-62e5-44d7-8a76-e5e2e6dc65cf" />

RESULT:
Thus the given sketch is drawn and drafted using Fusion 360 tool.
