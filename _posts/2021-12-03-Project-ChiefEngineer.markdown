---
layout: post
title: Chief Engineer of Blue Sky Solar Racing
date: 2022-12-25 19:32:20 -0500
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: Shannonville.JPG # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Teamwork, Club, Engineering]
---
Blue Sky Solar Racing website: www.blueskysolar.org

# Table of Contents

1. [Blue Sky Solar Racing](###Blue Sky Solar Racing)
2. [My Role as Chief Engineer](###My Role as Chief Engineer)
    1. [Mechanical](####Mechanical)
    2. [Structural and Fabrication](####Structural and Fabrication)
    3. [Electrical](####Electrical) 
    4. [Aerodynamics](####Aerodynamics)
    5. [Array](####Array)
    6. [Strategy](####Strategy)
3. [Testing of the Solar Car](###Testing of the Solar Car)

### Blue Sky Solar Racing

Blue Sky Solar Racing is a student lead design team at the University of Toronto, that has built and raced solar cars for over 25 years. Currently, we are building our 11th generation car to race in the [World Solar Challenge](https://www.worldsolarchallenge.org/) of 2023. 

The team is composed of 78 students and 9 subteams.

![](/assets/img/Technical.jpg)

### My Role as Chief Engineer

I have taken the role of Chief Engineer from September 2022 until the race in October 2023. As a chief engineer, I have several major responsibilities:

1. Create timelines for technical subteams
2. Ensure compliance of the solar car to regulations
3. Direct the design and manufacturing decisions with subteam leads
4. Engage sponsors to secure materials, machining, and technical supports
5. Testing the roadworthiness of the solar car on actual tracks

Besides the “formal” responsibilities, I have two personal goals as a chief engineer. 

Firstly, I took the role of chief engineer to learn the most across all engineering disciplines, therefore, I try to be less in a managerial role but be an engineer by assisting the subteams with solving problems and taking on projects. 

Secondly, I want to ensure all the leads and members who have trusted me to take this role to see the results of their sacrifices and time committed to this team as a lifetime achievement. 

#### 1. Mechanical

##### Forces on the Suspension and Chassis 

The forces on the suspension system are used for all mechanical and structural simulations to ensure the safety of the car in different scenarios. The scenarios include bumps, brakes, and turns for different accelerations. For example, a [2,1,1] case represents 2g acceleration for bump, 1g for brake, and 1g for turn.

The dynamic loads on each wheel can be calculated after finding the lateral and longitudinal weight transfer for different scenarios. These loads are applied to the wheel and using force body diagrams, we can calculate the forces on the mechanical components such as the lower control arm, upright, and upper control arm for our solar car, Borealis. 

![](/assets/img/FBD.jpg)

##### Spring rates, Preload, and Shocks

Choosing proper shocks and springs is vital for the safety of the car and the comfort of the driver. Shocks need to have the correct stroke length allowing the full bump and droop travel of the wheels. Proper springs are required for the correct ride height, comfort, and stability of the car; preload needs to be calculated to achieve the correct ride height for that particular spring. 

![](/assets/img/Springs.jpg)

##### Ansys Transient Analysis 

The solar car’s top shell needs to be opened for the driver to exit the car and the array to be orthogonal to the sun during charging. Utilizing Ansys, I was able to analyze the four-bar mechanism used to open and close the top shell. 

[![](ansys.jpg)](https://www.youtube.com/watch?v=_3VnMIyA7GE)


#### 2. Structural and Fabrication

##### Canopy 

We were able to improve the clarity of the canopy segnificantly based on testimonies from previous alumni of the team. The canopy was manufactured through thermoforming a PETG sheet onto a fiberglass mould. 

![](/assets/img/canopy.jpg)

![](/assets/img/canopy_mould.jpg)

##### Top Shell

Manufactured the top shell of the car, made using carbon fiber and Divinycell core and utilizing vacuum infusion process to build the composite part.

![](/assets/img/TopAero_Prep.jpg)

![](/assets/img/vacuum_infusion.jpg)

![](/assets/img/toppart.jpg)

##### Composite Rollcage

The composite rollcage will allow us to reduce the weight of the car by 10 Kg, instead of a tubular-steel metal rollcage. 

#### 3. Electrical

##### Battery Thermal Analysis 



#### 4. Aerodynamics
#### 5. Array
#### 6. Strategy


### Testing of the Solar Car
