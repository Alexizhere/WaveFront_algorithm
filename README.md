Wavefront Path Planning Algorithm
This MATLAB script demonstrates a path planning algorithm using the Wavefront method. The algorithm finds the shortest path from a start position to a finish position on a grid-based map containing obstacles.

Getting Started
To run the script, ensure you have MATLAB installed on your system. The script has been tested on MATLAB R2016b Academic version.

Prerequisites
You need MATLAB software installed on your system. The script relies on the Image Processing Toolbox for image loading and manipulation functions.

Installation
Clone or download the repository to your local machine.
Open MATLAB and navigate to the directory where you saved the script files.
Run the main script (wavefront_path_planning.m) in MATLAB.
Usage
Prepare your map: The map should be an image file (such as PNG) where obstacles are represented by black pixels, the start position by red pixels, and the finish position by green pixels.

Run the script: Execute the main script in MATLAB. It will load the map, identify the start and finish positions, and perform the Wavefront algorithm to find the shortest path.

Visualize the results: The script will display the map with wavefront propagation and the shortest path highlighted.

Algorithm Overview
The Wavefront algorithm propagates wavefronts from the start position until it reaches the finish position. Each cell in the map is assigned a value representing the distance from the start position. Obstacles are assigned a special value to indicate that they cannot be traversed.

Contributions
Contributions and improvements to the script are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
This script was inspired by the Wavefront path planning algorithm.
Thanks to the MATLAB community for valuable insights and discussions.
