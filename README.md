# Driver Monitoring System Using Machine Learning
 
## Problem Statement:
To develop a driver monitoring system with the objective of building a Machine learning algorithm for tracking of drivers behavioral attributes.

## Significance Of This Project:
Worldwide, road accidents are primarily caused by drowsiness and fatigue. In order to minimize and decrease the number of accidents involving cars, lorries, and trucks, Driver Drowsiness Detection by Using Webcam is being introduced. It recognizes the symptoms of drowsiness and warns drivers when they begin to nod off.

## Dataset Used:
The 300-W is a face dataset that consists of 300 Indoor and 300 Outdoor in-the-wild images. It covers a large variation of identity, expression, illumination conditions, pose, occlusion and facesize. Images were annotated with the 68-point mark-up using a semi-automatic methodology.




## Methodology:
High vision cameras are embedded to monitor and capture to extract frames one by one and generate the alerts accordingly. Each extracted frame is analyzed at time to study the pattern of facial features;Eye Aspect Ratio(EAR) and Mouth Aspect Ratio(MAR) for each frame . EAR and MAR values exceed their respective threshold values, a blink and a yawn is considered respectively. The system alerts the driver by playing an alarm if eye blinking rate and yawns are suspected for a certain number of consecutive frames. The alarm is activated to grab the drivers attention and keep on ringing until driver wakes up

<p align="center">
<img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/images/EAR.png"  width="350" title="E.A.R">
</p>
