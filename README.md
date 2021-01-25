# LabVIEW XY-Stage Controller
LabVIEW is systems engineering software for applications that require test, measurement, and control with access to hardware.<br>
This LabVIEW program allow control over an xy-stage with basic functionalities such as intiating motors, home search, move to a specified absolute position, abort execution and more.<br>
The program's heart is its ability to create network-shapes easily with a simple GUI that shows the expected output on a graph in real time.

NOTE that the program is communicating with a specific controller, and might need a readjustment to fit to your hardware.

[add gif here]

## Installation

To use the program simply download/clone the repository to a computer subscribed to LabVIEW.
It is possible to build the code as an .exe application by going to Tools >> Build Application From VI.
No executable files are uploaded here as minor changes must be done for any change of hardware.

## Usage

The GUI is devided to 3 sections:
1. Basic controls - basic controls like start & stop program, kill motors, go home, abort mission.
2. Absolute Movement - allow a single movement of the stage to a specified absolute position. Velocity & Acceleration can also be modified.
3. Relative Movement - allow creating complex shapes, specifically design to produce networks.

For additional and more detailed explanation read the manual in the 'manual' folder. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Any improvement should be saved as a new version, with documentation on changes and improvements from previous version.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
