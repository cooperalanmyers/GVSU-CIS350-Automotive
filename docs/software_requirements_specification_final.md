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
| FR3 | Tilt-compensated compass shall have capability to record compensated heading. | 

### Various Implementations
| FR4 | When button is pressed once LCD screen shall begin displaying data. |
| FR5 | When button is pressed twice data collection shall stop. |
| FR5 | Our data shall react appropriately to the magnet. | 
| FR7 | Data recorded shall be delimited by spaces or commas. |
| FR8 | When titled on x and y, and not z, reading shall be same/similar. |
| FR9 | Language shall decode document and display info. | 
| FR10 | Feature shall display header directions. |
| FR11 | Feature shall display pitch directions. |
| FR12 | Feature shall display roll directions. | 
| FR12 | Program shall have the smallest runtime complexity possible. |
| FR12 | Compass shall not crash when moved super fast. |
| FR15 | LCD shall light up when running. | 

### Axis Diagnostics
| FR16 | Tilt-compensated compass shall record roll (x). |
| FR17 | Tilt-compensated compass shall record pitch (y). |
| FR18 | Tilt-compensated compass shall record heading (z). | 

 
## Non-Functional Requirements
### System Expectations
| ID | Requirement |
| :-------------: | :----------: |
| NFR1 | Compass shall be quiet to use. |
| NFR2 | Calculation of values shall have a response time under 2 seconds. |
| NFR3 | Compass shall have 5v maximum of power. |
| NFR4 | Records shall be in a text file for easy parsing of information. |
	
### Coding
| ID | Requirement |
| :-------------: | :----------: |
| NFR5 | Updates shall be pushed/pulled using GitHub. |
| NFR6 | Comments throughout code shall explain our logic accurately. |
| NFR7 | Code will follow proper readable syntax. |
| NFR8 | It shall be able to work with any Xsens IMU device. |
| NFR9 | It shall interface with additional operations. |

### Output Logistics
| ID | Requirement |
| :-------------: | :----------: |
| NFR10 | LCD display shall display all information needed. |
| NFR11 | Compass' user interface shall be simple to read. |
| NFR12 | Display shall fit in a 16x2 or larger dimension screen. |

### Portability
| ID | Requirement |
| :-------------: | :----------: |
| NFR13 | Compass shall operate in environments 50-80 degrees Farenheit. |
| NFR14 | Entire project shall be easily used with a single hand. |
| NFR15 | Compass shall be under ten pounds in total weight. |

# Software Artifacts
- We imported various photos that contributed towards development. The main purpose of having these imports is to make them easier to see how these were implemented in development. It is important that the requirements can be seen live. Whether or not the project is physically present, having that auditability is important. These artifacts also provide sample uses.
* [Button](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/ButtonArtifact.jpg)
* [Display](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/DisplayArtifact.png)
* [Imu](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/IMUArtifact.png)
* [Math Library](https://github.com/cooperalanmyers/GVSU-CIS350-Automotive/blob/master/artifacts/MathLibraryArtifact.png)

