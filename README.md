# CoaxialSPM
fusion360/step/stl file for a 3-DOF SPM end effector

This repository contains original Fusion360 design and 3D printable files of a coaxial Spherical Parallel Mechanism(SPM) module, designed to replace the end effector of a Delta 3D printer. SPM provide better performance than their serial manipulator counterparts with regard to positioning accuracy, speed, force application, and payload-to-weight ratio.  
This project was made possible by the generous support of SPACE10 through a research residency program in summer 2019.

<img src = "Resources/IMG_3227_2.jpg" height = 800>

**3D Print Guide:**

This version was designed to be printed on an SLA printer. Avoid placing support on mating surfaces.  
For tighter joint fit, print parts with high-hardness resin. Tough resin(eg formlab tough) might result in loose joints.


**Hardware:**

A prototype was build as part of the residency program. List of hardware used for this prototype
 * Anycubic Linear Plus
	This system was chosen for its fast Z feedrate and linear rail for sturdy linkage(vs magnetic)
 * Azteeg X3 Pro
	Or equivalent board with support up to 6 stepper motors
 * Zesty Drive Cables
 * 3x Stepper motors

**Software:**
 * This 3-DOF SPM end effector can be controlled by any 6-axis firmware or with Repetier6X.  https://github.com/anthonychukh/Repetier6X
 * Tool path can be created with SeastarNC, a Rhino Grasshopper plgin for 3D-printer-based robotic control.  https://github.com/anthonychukh/SeastarNC  
Since most firmware do not support SPM, SeastarNC has build in component to precompute rotational input for a specific orientation.
  
<img src = "Resources/AT0A3728.jpg" width = 750>
  
---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.  

--------------------CAUTION---------------------------  
Working with electronic devices could be dangerous 
Always take precaution when working on electronic devices
Make sure you are well trained and informed to work on the specific system
Failure to appropriately operate your machine could lead to hardware damage and/or serious injuries
