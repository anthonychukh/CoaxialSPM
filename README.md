# CoaxialSPM
fusion360/step/stl file for a 3-DOF SPM end effector

This repository contains original Fusion360 design and 3D printable files of a coaxial Spherical Parallel Mechanism(SPM) module, designed to replace the end effector of a Delta 3D printer. SPM provide better performance than their serial manipulator counterparts with regard to positioning accuracy, speed, force application, and payload-to-weight ratio.
This project was made possible by the generous support of SPACE10 through a research residency program in summer 2019.


3D Print Guide:
This version was designed to be printed on an SLA printer. Avoid placing support on mating surfaces.
For tighter join fit, print parts with high-hardness resin.


Hardware: 
A prototype was build as part of the residency program. List of hardware used for this prototype
 * Anycubic Linear Plus
	This system was chosen for its fast Z feedrate and linear rail for sturdy linkage(vs magnetic)
 * Azteeg X3 Pro
	Or equivalent board with support up to 6 stepper motors
 * Zesty Drive Cables
 * 3x Stepper motors


Software:
 * This 3-DOF SPM end effector can be controlled by any 6-axis firmware or with Repetier6X.  https://github.com/anthonychukh/Repetier6X
 * Tool path can be created with SeastarNC, a Rhino Grasshopper plgin for 3D-printer-based robotic control.  https://github.com/anthonychukh/SeastarNC
Since most firmware do not support SPM, SeastarNC has build in component to precompute rotational input for a specific orientation.


-------------------DISCLAIMER--------------------------
This library and Grasshopper plugin was created out of good intension for the promotion and education of technology
User should take their own caution and risk when using this library
The creator(s) of this library do not provide any garantee and waranty to use of this library and digital tool derives from this library
  

--------------------CAUTION---------------------------
Working with electronic devices could be dangerous 
Always take precaution when working on electronic devices
Make sure you are well trained and informed to work on the specific system
Failure to appropriately operate your machine could lead to hardware damage and/or serious injuries
