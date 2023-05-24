# OpenCV_eyetracking
Simple project for eye tracking
Forked from Vonej/OpenCV_eyetracking_Pavlov[https://github.com/Vonej/OpenCV_eyetracking_Pavlov]

- Added variables to store eye movement data, `eye_movements` and `overall_movement`.
- Introduced separate overall movement for each eye using a list, `overall_movement`.
- Added a variable, `blink_count`, to store the number of blinks.
- Modified the display to show the scrolling eye movement data as a single X, Y pair at a time, moving in a scrolling manner.
- Updated the display position of the eye movement data to create a scrolling column effect.
- Added the overall movement of each eye to be displayed in the upper right-hand corner.
- Displayed the number of blinks in the lower right-hand corner of the screen.

TODO future road map

- Fix bugs and check math for blinking
- Export eye movement data to CSV format for further analysis and visualization.
- Enhance data capture for each eye individually, enabling more accurate and detailed eye movement tracking.
- Improve the code for detecting blinking to ensure accurate detection and differentiation from other eye movements.
- Implement synchronization of eye movement data with a timestamp to enable temporal analysis and correlation with other events.
- Explore methods to map video frames, timestamps, and eye movement data for comprehensive analysis and visualization.
- Conduct textual analysis on eye movement data, such as identifying patterns, trends, or correlations with other variables.
