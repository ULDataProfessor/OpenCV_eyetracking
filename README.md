# OpenCV_eyetracking_Pavlov
Simple project for eye tracking
Forked from Vonej/OpenCV_eyetracking_Pavlov[https://github.com/Vonej/OpenCV_eyetracking_Pavlov]

- Added variables to store eye movement data, `eye_movements` and `overall_movement`.
- Introduced separate overall movement for each eye using a list, `overall_movement`.
- Added a variable, `blink_count`, to store the number of blinks.
- Modified the display to show the scrolling eye movement data as a single X, Y pair at a time, moving in a scrolling manner.
- Updated the display position of the eye movement data to create a scrolling column effect.
- Added the overall movement of each eye to be displayed in the upper right-hand corner.
- Displayed the number of blinks in the lower right-hand corner of the screen.
