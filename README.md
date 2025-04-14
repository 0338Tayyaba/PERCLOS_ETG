# PERCLOS_ETG
PERCLOS is the percentage of eyelid closure over the pupil over time and reflects slow eyelid closures (“droops”) rather than blinks. There could be several ways of calculating PERCLOS, such as eye-tracking glasses, screen-based fixed eye trackers, and cameras.
It correlates to cognitive load and several other neurophysiological indicators such as fatigue, drowsiness, emotional states like sadness and anger, motion artifacts, and changes in attention.

# PERCLOS Calculation using Eye-Tracking Glasses (ETG)
This repository provides code and documentation for calculating PERCLOS using data obtained from Eye-Tracking Glasses (ETG). PERCLOS is a widely recognized and validated metric for detecting drowsiness, especially in real-world driver monitoring and fatigue detection systems.

## Why do we need to calculate PERCLOS?
It is the percentage of time the eyelids are at least 80% closed over a defined time window. It is considered one of the most reliable indicators of drowsiness in real-time systems.

## How to get data (pupil diameter, eye validity, and timestamps) to calculate PERCLOS?
In this example, data from Tobii Pro 2 ETG is used and then processed before computing the percentage values. 

