Research Track 2 - Assignment 2 Solution
================================
The following repository contains the solution to the second assignment for the Research Track 2 Course, found in the Robotics Masters Programme at the University of Genoa, Italy. 
As part of the assignment, students were required to create a user interface using Python on Jupyter Notebook, that interacts with a Gazebo based robot. The implemented user interface
should be capable of allowing a target to be set and cancelled. Besides the UI, the robot and target positions were to be plotted, and the number of reached and cancelled targets graphed.
<br><br>

Table of Contents
----------------------
1. [Prerequisites](https://github.com/Markie3110/Research_Track_2-Assignment_2/tree/main#prerequisites)
2. [Project Contents](https://github.com/Markie3110/Research_Track_2-Assignment_2/tree/main#project-contents)
3. [How to Install](https://github.com/Markie3110/Research_Track_2-Assignment_2/tree/main#project-contents)
4. [How to run](https://github.com/Markie3110/Research_Track_2-Assignment_2/tree/main#how-to-run)
5. [Known Errors](https://github.com/Markie3110/Research_Track_2-Assignment_2/tree/main#known-errors)
<br>

Prerequisites
----------------------
In order to be able to run the simulator, the "assignment_2_2023" ROS package is needed. The package can be installed from the following Github repository: *https://github.com/CarmineD8/assignment_2_2023*.
<br><br>

Project Contents
----------------------
The project contains a single Jupyter Notebook file titled "Assignment_2.ipynb", that can be run from within the Jupyter workspace to experience the interactive UI and plots.
<br>

How to Install
----------------------
To download the repsitory's contents to your local system you can do one of the following:

1. Using git from your local system<br>
To download the repo using git simply go to your terminal and go to the src directory within your ROS workspace. Type the following command to clone the repository to your folder:
```bash
$ git clone "https://github.com/Markie3110/Research_Track_2-Assignment_2.git"
```

2. Download the .zip from Github<br>
In a browser go to the repository on Github and download the .zip file availabe in the code dropdown box found at the top right. Unzip the file to access the contents.
<br>

How to Run
----------------------
Carry out the following steps to run the program:<br>
1. In order to run the UI, it is first required to start the gazebo simulator. In the command line of the terminal, first run the rosmaster via the following command:
```bash
roscore
```
2. Then, to run the simulator, open another window of the terminal and execute the following command:
```bash
roslaunch assignment_2_2023 assignment1.launch
```
3. Once again, open another window within the terminal and move to the directory in which you have saved the Notebook file. From there you can start the Jupyter server with the following:
```bash
jupyter notebook --allow-root --ip 0.0.0.0
```
4. The server will open up in your default browser. From there double click the "Assignment_2.ipynb" file to open it. Run all the cells by opening the Cells tab on top and selecting "Run All".
<br>

Known Errors
----------------------
On occassion, the gazebo simulator may not display any changes due to the robot being stuck on a wall. In such a situation, it is required to restart the simulator, and after that the kernel within the Jupyter file.
<br>
<br>


