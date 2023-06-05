# Driver Monitoring System Using Machine Learning
 
## Problem Statement:
To develop a driver monitoring system with the objective of building a Machine learning algorithm for tracking of drivers behavioral attributes.

## Significance Of This Project:
Worldwide, road accidents are primarily caused by drowsiness and fatigue. In order to minimize and decrease the number of accidents involving cars, lorries, and trucks, Driver Drowsiness Detection by Using Webcam is being introduced. It recognizes the symptoms of drowsiness and warns drivers when they begin to nod off.

## Dataset Used:
The 300-W is a face dataset that consists of 300 Indoor and 300 Outdoor in-the-wild images. It covers a large variation of identity, expression, illumination conditions, pose, occlusion and facesize. Images were annotated with the 68-point mark-up using a semi-automatic methodology.

## Methodology:
High vision cameras are embedded to monitor and capture to extract frames one by one and generate the alerts accordingly. Each extracted frame is analyzed at time to study the pattern of facial features;Eye Aspect Ratio(EAR) and Mouth Aspect Ratio(MAR) for each frame . EAR and MAR values exceed their respective threshold values, a blink and a yawn is considered respectively. The system alerts the driver by playing an alarm if eye blinking rate and yawns are suspected for a certain number of consecutive frames. The alarm is activated to grab the drivers attention and keep on ringing until driver wakes up.

## Measuring Eye Aspect Ratio - E.A.R
Eye Aspect Ratio (EAR) is a facial feature-based metric used to determine driver drowsiness or fatigue. It involves analyzing the geometric characteristics of the eyes, specifically the relationship between the eye landmarks, such as the corners of the eye and the midpoint of the eye. EAR is calculated by measuring the ratio of the horizontal distance between the two eye landmarks to the vertical distance between the same landmarks.

<p align="center">
<img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/EAR.png"  width="350" title="E.A.R">
</p>

## Measuring Mouth Aspect Ratio - M.A.R
Mouth Aspect Ratio (M.A.R.) is a metric used to determine driver drowsiness by analyzing the shape and movements of the mouth. It involves measuring the width and height of the mouth region and calculating their ratio. The aspect ratio is calculated by dividing the width of the mouth by its height. A higher aspect ratio indicates that the mouth is more open or elongated horizontally, while a lower aspect ratio suggests a more closed or compressed mouth shape.

<p align="center">
<img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/MAR.png"  width="350" title="M.A.R">
</p>

## Graphical User Interface

<p float="centre">
  <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/GUI_2.png" width="500" />
 <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/GUI_3.png" width="500" /> 
</p>


## Sample Output

<p float="centre">
  <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/MV Eyes Open No Yawn.png" width="500" /> 
 <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/MV Eyes Closed Yawn.png" width="500" /> 
</p>


## Graphical Analysis

<p float="centre">
  <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/EAR_graph.png" width="500" /> 
 <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/MAR_graph.png" width="480" /> 
</p>

## Result Table

<p float="centre">
 <img src="https://github.com/ManishV18/Driver-Monitoring-System-Using-Machine-Learning/blob/main/Project Pictures/Result_Table.png" height= "300" width="700" /> 
</p>

