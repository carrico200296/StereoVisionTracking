# StereoVisionTracking
Stereo vision tracking and classification system for the Industry 4.0.


HOW TO RUN THIS CODE:
In order to run it you first have to run camera_calibration.py, which generates and saves the projection_matrices and rectification maps.

The other files (SIFT_*) are used by the main script for the classification task. You don't have to run them. They contain the trained classification model data and some functions used by the main script.

IMPORTANT:
In order to run final_project.py, you must have the following local directory tree:

(this directory)
../calibration/calibration_matrix               (create this empty folder, calibration matrices will be saved here)

../dataset/conveyor_with_occlusions/left        (put left images here)
../dataset/conveyor_with_occlusions/right       (put right images here)

../calibration/calibration_patterns/left        (put left calibration patterns here)
../calibration/calibration_patterns/right       (put right calibration patterns here)
