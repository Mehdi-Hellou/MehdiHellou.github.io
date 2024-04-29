---
title: Reasoning on human emotions
icon: fa-lightbulb
layout: page
order: 1
---
 During my master's at Sorbonne University(2019/2020), I realized an internship of 5 months at the laboratory Intelligent Robotics Lab (IRLab) at the University of Birmingham under the supervision of Dr. Mohan Sridharan. We focused on analyzing people's emotional states through facial expressions for reasoning and adjusting a social robot's behaviors during this internship. More specifically, we wanted to adapt the method on the assistance of elderly by enabling a mobile robot to detect emotions and assist seniors during their daily routine. For example, we took the scenario of a mobile robot that can deliver specific items to a user according to his preferences to increase his affective state. More precisely, if we have a user who loves to drink coffee and he is feeling sad, the robot should get a cup of coffee to cheer him up.

In doing so, the project included two main modules to integrate into the final system:
<ul>
    <li>An emotion recognition module to detect and predict human emotions. For that, we used current state-of-the-art methods used for emotion recognition in Deep Learning with Convolutional Neural networks (CNN), such as ResNet-50 or VGG-16.</li>
    <li>A module to reason on emotions and user's preferences, e.g., bring a cup of coffee if the user likes to drink coffee. This part includes a knowledge base for the robot to learn the different elements from the world and its preferences. It also has a planner to analyze and develop the robot's actions to assist the users.</li>
</ul>
Concerning the tools, Tensorflow 2.0 was used for the emotions recognition, and the declarative language Answer Set Prolog(ASP) was employed to represent the robot's knowledge. ASP was also mixed with the inference engines Clingo to plan the different robot's actions. To test our system in a real situation, we define a simulator environment and a scenario. We employed ROS(Robot Operating System) and Gazebo, which included six rooms with five objects, a human and a mobile robot. We provide a short demo below to have a better understanding of the simulator. 

<!--video width="320" height="240" controls>
  <source src="../assets/videos/UOB_ROS_project.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video-->
<div style="display: flex; justify-content: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/_5-VYTT911Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>