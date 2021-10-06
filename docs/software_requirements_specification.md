# Overview
- Here are the various funcitonal and requirements that the project seeks to accomplish. Whether relative to a subsystem having to do with tilt functionality, overall output functionality, or overall input functionality, requirements are laid out here for success measuring. Major points of highlight are being able to clearly understand what needs to be tilted, outputs as a result, and other functionality. One note of importance though is that this only has to do with what the software should do. Any hardware issues or needs are not part of this.
# Functional Requirements
1. Overall System/Interface
	1. Tilt-compensated compass shall record session data to an SD card or text file
	2. Tilt-compensated compass shall be stabilized on a level surface.
	3. Tilt-compensated compass shall have capability to record both compensated and uncompensated heading.
2. Axis Diagnostics
	1. Tilt-compensated compass shall separately record and display roll (x), pitch (y), and heading (z) axes.
3. Axis Logistics.
	1. When tilted, tilt-compensated compass Z-axis shall alter in value.

 
# Non-Functional Requirements
1. Overall System/Interface
	1. Compass’ user interface shall be simple to use.
	2. Calculation of values shall have a response time under 2 seconds.
	3. Compass shall operate in environments 50-80 degrees.
	4. Records shall be in a text file for easy parsing of information.
	5. Interface or separate user-input method shall be given conditions and output only the tilt-compensated value.
2. Output Logistics
	1. Seven segment displays shall display numbers between 00 and 35.
