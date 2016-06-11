--------------------------------------------------------------------------------
TRACE Dataset version 1.0
--------------------------------------------------------------------------------

Katerina Karagiannaki (1,2)__
Athanasia Panousopoulou (1)__
Panagiotis Tsakalides (1,2)__

(1) - Signal Processing Laboratory (SPL), ICS - FORTH__
(2) - Computer Science Department, University of Crete__

--------------------------------------------------------------------------------
		EXPERIMENTAL SETUP
--------------------------------------------------------------------------------
The dataset is collected from 15 participants wearing 5 Shimmer sensor nodes 
on the locations listed in Table 1. The participants performed a series of 16 
activities (7 basic and 9 postural transitions), listed in Table 2.

The captured signals are the following:__
3-axis accelerometer__
3-axis gyroscope__
3-axis magnetometer__

The sampling rate of the devices is set to 51.2 Hz.

--------------------------------------------------------------------------------
		DATASET FILES
--------------------------------------------------------------------------------
The dataset contains the following files:

partX/partXdev1.csv__
partX/partXdev2.csv__
partX/partXdev3.csv__
partX/partXdev4.csv__
partX/partXdev5.csv__

Where X corresponds to the participant ID, 
and numbers 1-5 to the device ID (Table 1).

Each .csv file has the following format:

Column1: Device ID__
Column2: accelerometer x__
Column3: accelerometer y__
Column4: accelerometer z__
Column5: gyroscope x__
Column6: gyroscope y__
Column7: gyroscope z__
Column8: magnetometer x__
Column9: magnetometer y__
Column10: magnetometer z__
Column11: Timestamp__
Column12: Activity Label__

--------------------------------------------------------------------------------
		Table 1: LOCATIONS
--------------------------------------------------------------------------------
1. Left Wrist
2. Right Wrist
3. Torso
4. Right Thigh
5. Left Ankle

--------------------------------------------------------------------------------
		Table 2: ACTIVITY LABELS
--------------------------------------------------------------------------------
1: stand__
2: sit__
3: sit and talk__
4: walk__
5: walk and talk__
6: climb__
7: climb and talk__
8: stand -> sit__
9: sit -> stand__
10: stand -> sit and talk__
11: sit and talk -> stand__
12: stand -> walk__
13: walk -> stand__
14: stand -> climb, stand -> climb and talk__
15: climb -> walk__
16: climb and talk -> walk and talk__
