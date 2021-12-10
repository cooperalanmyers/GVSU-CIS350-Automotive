# Automotive
Our team is working on creating a tilt-compensated compass with a raspberry pi. Our appliation is in the automotive field for car navigation.

## Team Members and Roles

* [Cooper Myers](https://github.com/cooperalanmyers/CIS350-HW2-Myers) (Programmer)
* [Jacob Neiheisel](https://github.com/jneiheisel98/CIS350-HW2-Neiheisel) (Programmer)

## Prerequisites
1. Raspbery Pi 3b+
2. Xsens IMU
3. LCD Display
4. Monitor
5. Keyboard
6. Mouse
7. Wiring
8. Button
9. Breadboard
10. HDMI

## Run Instructions

1. Boot up Raspberry Pi
2. Download MT Software Suite from [here](https://www.xsens.com/software-downloads) and save to right place in Pi.
3. Open terminal window
4. Go to the file location and run the following command: tar -xf MT_Software_Suite_linux-x86_2021.4.tar.gz
5. cd into the newly created folder
6. run this: ./mtsdk_linux-x86_2021.4.sh, type in sdk when prompted
7. run cd sdk/examples/mtsdk/xda_public_cpp
8. Use rm -r to removr example_mti_parse_logfile.cpp, example_mti_receive_data.cpp, and Makefile
9. Clone our source code from GitHub to the current directory.
10. Go into directory using cd GVSU-CIS350-Automotive/src
11. Move all files in except for LCD file and README.md file using mv filename ../.. for each file
12. Go up two directories usind ../..
13. Run make command & let it compile
14. Run ./example_recieve_data file
15. Press button to start collecting data
16. Tilt as needed
17. Press button once more to stop collecting data
