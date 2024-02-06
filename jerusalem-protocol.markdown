---
layout: page
title: Jerusalem Protocol
permalink: /jerusalem-protocol/
---

This document contains draft best practices for evaluating FOG according to the *Jerusalem Protocol*. This document differs from the final accepted version and is for reference only.

## Instrumentation

### APDM Opal IMU Apparatus
Five APDM Opal IMUs are required for testing. The provided docking station and software are also required.

### Axivity AX6 sensors
Axivity AX6 sensors (https://axivity.com/product/ax6) are reusable data loggers that patients take home for a brief observation period. They are reusable, but you will need a few extras (once in a while they break). How many depends on how many subjects you anticipate studying at the same time (keep in mind that you need to allow time for the devices to be returned to your center, via mail or courier). With 6, you could study 3 subjects overlapping and have 3 spares.

### Video cameras
Two video cameras on tripods are recommended to record the entirety of each testing session. Any color “Handycam” style video camera that is sufficient for annotating FOG will be appropriate. iPads/tablets tend to blur during fast motion such as festination and are therefore not recommended. Be sure to purchase ample memory.

## Testing protocol

### Space Requirements & Set-up 

#### Kit Included:
Tape, Bluetooth speaker, Box stencil, distance string, measuring tape

Use tape (2.54 cm wide green painters) to mark two squares on the floor (the inside of the box measures 50cm x 50cm), one for the first 5 tasks and one square for walking through a doorway and turning 180 deg. Masking tape square on the floor (50cm x 50 cm) should be at least 30 cm clearance from a wall. Place a chair (with arms) 3m distance from the square for resting between trials when needed and to evaluate FOG during turn to sit maneuver. Place camera 1 (frontal facing) 3m behind the box centered with the chair and be sure the entire subject is in view, including feet during the turn. Place camera 2 (optional, sagittal facing) and 3m to [either] side of the route. Ensure that the camera field of view can view the participants feet and shoulders throughout all parts of the trial.

![Figure 1](images/jp-test-01.png)

For task 6 (Doorway), mark the start position on the ground 2m on one side of a doorway and place a 50cm x 50cm masking tape square .5 m past the doorframe.

![Figure 2](images/jp-test-02.png)

For dual-task trials, use the audio file provided, and instruct the participants to say out loud the tone (‘high’ or ‘low’) not the word as sometimes the tones and words will match and sometimes they will not. The goal is to only recite the tone. Please have the patient practice this while seated prior to commencing the protocol. If unable to complete this after two practice trails, please modify the task to only recite the word and ignore the tone. For the final calibration trial, participants will be asked to complete two 10m walks. Please indicate with tape on the floor a 10 m distance.

### Set-up

#### Gather Equipment

Refer to the image below to identify equipment needed:

![Figure 3](images/jp-test-03.png)

#### Connect the sensors and start Mobility Lab

1. Connect the Access Point to the docking station using a Micro USB cable.
2. Connect the external power adapter to the Docking Station and plug it into a power outlet.
3. Connect the Docking Station to your computer using a Micro USB cable.
4. Plug the Opals into the Docking Station in any order, with the port facing down. The Docking Station and Access Point should have a green light when powered on.
5. If installing Mobility Lab for the first time:
  - Insert the provided USB drive into your computer to set up the software.
  - Double click the setup file.
  - This will guide you through the installation process.
6. After the installation process, click on the Mobility Lab application to launch the program. 

#### Configure Sensors for Recording

1. Name Your Subject Group
  - Open the Mobility Lab application. Click the icon in the top right-hand corner to name your subject group. 
  - Click “+ Add New” from the drop-down menu. Name the new Subject Group FOG-ST. 
  - All new subjects will be added to the FOG-ST subject group.
    
![Figure 4](images/jp-test-04.png)

2. Configure Hardware
  - Navigate to the “Hardware Configuration” tab across the top indicated by a wrench icon.
  - Assign Opals to a body site location by dragging from the Available Sensors list and dropping on the human model. 
  - The sensors will now show in the Assigned Sensors list. 
  - For this protocol, sensors will be placed on:
    -	Left and right shins (facing forward above the lateral and medial malleolus of the ankle)
    -	Left and right feet (dorsal, proximal surface – atop the place you would tie shoe laces)
    -	Lower back (L5)
  - The sensors assigned to the wrist will have to be re-assigned to the shins. This can be done using the Custom Sensor Assignments fields. 
    -	Put the sensor serial number in the “Sensor” category and put “Left Shin” and “Right Shin” as the Display Label. 
  -	The Chest sensor can be removed from the docking station since it will not be used during this assessment. Click the small “x” beside the sternum label to remove it from configuration. 
  -	Once the sensors are configured, select “Apply Configuration”. 

![Figure 5](images/jp-test-05.png)

3. Configure Options
  -	The “Options” tab across the top of the application indicated by the three vertical lines shows all of the display options in the system for a selected subject group. 
4. Configure Metric Groups
  - Metric groups change which metrics are displayed in the test results window and add custom metric groups for each test.
  -	Keep all of the default boxes selected for the “Walk” tab as shown below.
  -	Keep all boxes selected for the “360 Degree Turn” tab as well. 

![Figure 6](images/jp-test-06.png)

#### Prepare to Record

1. Configure Tests and Conditions
  – Add, edit, and delete custom tests and test conditions. 
  - This is where each of the eight trials will be added. 
2. Import a test sequence
  - Test sequences can be imported into the application.
  - In the top right hand corner, select the ‘Import Sequence’ button and select the FOG-ST sequence from finder. This will be sent along with other ICFOG documentation.
  - All 8 tests will automatically be added to the Tests and Conditions tab under the Walk and 360 degree turn tab.  
  - This will allow you to skip adding all of the tests manually.
  - However, if adding the sequence does not work, these are the steps to manually add each test.

### Record

#### Trial 1: Walk
- Under the “Walk” tab, click +Add Condition
- Condition Name: Trial 1: Walk 
- Duration: 0
- Countdown(s): 3
- Check “Play Default Audio Cues” 

*Subject Instructions*
- Start standing in front of the chair and begin walking forward on your own
- You can go once you hear the beep and I say 'Start'. Walk forward as quickly and safely as possible
- When you step inside the square, turn 180 degrees whichever way you prefer and come back and sit down in the chair

*Administrator Instructions*
- Click the 'Record' button, let the computer countdown from 3. Wait for the beep. Then say 'Start'
- Participant is standing at the beginning of the trial
- After the participant is seated at the end, fill in the FOG-ST score sheet and patient meaningfulness survey




