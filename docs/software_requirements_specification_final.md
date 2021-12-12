# Overview
- Here are the various funcitonal and non-functional requirements that our project accomplished. They are relative to a subsystem having to do with tilt functionality, overall output functionality, or overall input functionality. Requirements are laid out here for success measuring now that we are completed. Our major points of highlight are being clearly understanding the tilt mathematics, outputting to a display, and other functionality such as our button input. 

# Software Requirements

- This section starts out with the functional requirements pertaining to the system/interface as a whole, inputs and implementations, and axis diagnostics. There are then non-funcitonal requirements describing system expectations, code workflow, output logistics, and portability.

## Functional Requirements
### Overall System/Interface
| ID | Requirement |
| :-------------: | :----------: |
| FR1 | Tilt-compensated compass shall record session data to a text file. |
| FR2 | Tilt-compensated compass shall be stabilized on a level surface. |
| FR3 | Tilt-compensated compass shall have capability to keep a file of raw data. | 
| FR4 | Tilt-compensated compass shall have a functioning wired-in button. | 
| FR5 | Tilt-compensated compass shall have corresponding output with the XSENS MT Manager GUI. | 

### Various Implementations
| ID | Requirement |
| :-------------: | :----------: |
| FR6 | When button is pressed once LCD screen shall begin displaying data. |
| FR7 | When button is pressed twice data collection shall stop. |
| FR8 | Our data shall react appropriately to the magnet. | 
| FR9 | Data recorded shall be delimited by spaces or commas. |
| FR10 | When titled on x and y, and not z, reading shall be same/similar. |
| FR11 | Language shall decode document and display info. | 
| FR12| Feature shall display header directions. |
| FR13 | Feature shall display pitch directions. |
| FR14 | Feature shall display roll directions. | 
| FR15 | Program shall have the smallest runtime complexity possible. |
| FR16 | Compass shall not crash when moved super fast. |
| FR17 | LCD shall light up when running. | 

### Axis Diagnostics
| ID | Requirement |
| :-------------: | :----------: |
| FR18 | Tilt-compensated compass shall record roll (x). |
| FR19 | Tilt-compensated compass shall record pitch (y). |
| FR20 | Tilt-compensated compass shall record heading (z). | 
| FR21 | Tilt-compensated compass shall record magnetometer data for magentic field around x-axis. |
| FR22 | Tilt-compensated compass shall record magnetometer data for magentic field around y-axis. |
| FR23 | Tilt-compensated compass shall record magnetometer data for magentic field around z-axis. |
 
## Non-Functional Requirements
### System Expectations
| ID | Requirement |
| :-------------: | :----------: |
| NFR1 | Compass shall be quiet to use. |
| NFR2 | Calculation of values shall have a response time under 2 seconds. |
| NFR3 | Compass shall have 5v maximum of power. |
| NFR4 | Records in a text file shall have a format for easy parsing of information. |
| NFR5 | Compass shall have LCD screen bright and clear enough to be read when a user is 18 away inches from it. |
	
### Coding
| ID | Requirement |
| :-------------: | :----------: |
| NFR5 | Updates shall be pushed/pulled using GitHub. |
| NFR6 | Comments throughout code shall explain our logic accurately. |
| NFR7 | Code will follow proper readable syntax. |
| NFR8 | It shall be able to work with any XSENS IMU device. |
| NFR9 | It shall interface with additional operations. |

### Output Logistics
| ID | Requirement |
| :-------------: | :----------: |
| NFR10 | LCD display shall display all information needed. |
| NFR11 | Compass' user interface shall be simple to read. |
| NFR12 | Display shall fit in a 16x2 or larger dimension screen. |
| NFR13 | Display shall be able to display all alphabetical characters, numbers, and symbols needed. |
| NFR14 | Compass shall have ability to display different output than what is already defined, with some code reconfiguring as needed. |

### Portability
| ID | Requirement |
| :-------------: | :----------: |
| NFR15 | Compass shall operate in environments 50-80 degrees Farenheit. |
| NFR16 | Entire project shall be easily used with a single hand. |
| NFR17 | Compass shall be under ten pounds in total weight. |
| NFR18 | Compass wiring shall be able to be taped down or zip-tied. |
| NFR19 | Compass with a few parts disassembled shall be powered by battery if needed.  |

# Software Artifacts
- We imported various photos that contributed towards development. The main purpose of having these imports is to make them easier to see how these were implemented in development. It is important that the requirements can be seen live. Whether or not the project is physically present, having that auditability is important. These artifacts also provide sample uses.
* [Button](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/ButtonArtifact.jpg)
* [Display](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/DisplayArtifact.png)
* [Imu](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/IMUArtifact.png)
* [Math Library](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/MathLibraryArtifact.png)

