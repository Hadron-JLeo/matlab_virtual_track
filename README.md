
# Solution for Matlab Project Nr. 171

[MATLAB Simulink Challenge Projects](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/3D%20Virtual%20Test%20Track%20for%20Autonomous%20Driving)



## Possible TODOs for the Virtual Test Track



- Both highway and urban road elements

- Range of road grades, banking, and curvatures

- Traffic control infrastructure (signals, signage, street markings)

- Occlusions (buildings, signposts, trees, parked vehicles)

- Complex junctions (offset, oblique, 5+ legs, roundabouts, merges and splits)

- Restricted lane types (bus only, bike only, gore points)

- Pedestrian-road interfaces (crosswalks, sidewalks, “pedestrian scramble”)

- Sensor challenges (weathered lane markings, occluded signage, overpasses, foliage)

- Unprotected turns

## Update 1: 11/10/2024

I decided to base the track on a road I would often encounter in lower-Bavaria, Germany.
Its name is Oberglasschleife just shortly before the city of my University, Deggendorf.

The reason I chose it: You would drive sharply down-hill with many hard-rights and lefts, which caused many accidents in the past.

However, I will be adding signs from other countries and other traffic-control items to maximally confuse the Virtual Driving AI.
![image](https://github.com/user-attachments/assets/63b677ae-a5da-44c9-9f04-cb3bb5f9cfa2)

![image](https://github.com/user-attachments/assets/0dee1660-a9f2-4889-94fa-276c942c913e)

![image](https://github.com/user-attachments/assets/65426b2c-d5e0-4dbb-9fa3-9c4167182f75)

Hard-Rights/Lefts from memory:
![image](https://github.com/user-attachments/assets/0717a325-5099-43ac-8de7-56d2abf8d2c9)

Grey: Guard Rails
Brown: Mountain

Keep in mind the curves had to be drivin within a massive decline/incline!

## Update 2: 18/10/2024 NOTE: this part has been completely redone after update 5
![image](https://github.com/user-attachments/assets/f84aeafb-7014-4b45-89be-314de9a8fbc3)


I am having a few issues deciding the right Height for the roads, but I think it will be solved with some more focus.
The beginning and the cross-section will likely be connected by the end (unlike the real city) just so the driver will have a functioning loop.
The entrance to the 'city' has been blocked off by cones. I have also added other vehicles to the road.

![image](https://github.com/user-attachments/assets/837ad589-83c7-4a69-acf9-de11d412d41c)

## Update 3: 19/10/24

Working with Blender and BlenderGIS Addon to generate a terrain straight from Google Maps

![image](https://github.com/user-attachments/assets/ae88d60e-5ab3-4b16-9528-fa1874b0528a)

A link to the Addon repository can be found here: https://github.com/domlysz/BlenderGIS?tab=readme-ov-file

![image](https://github.com/user-attachments/assets/ebf24f0c-8f2a-4985-9d7f-3ea16420da70)

![image](https://github.com/user-attachments/assets/4c051016-acca-4c16-b21c-732e3d9bf398)

## Update 4: 23/10/24

I imported the exported .fbx file from Blender into RoadRunner and adjusted the streets to the necessary elevations.

## Update 5: 27/10/24

I am working on complex street signs for the simulated environment:

- Middle Eastern Stop Sign in Arabic

- USA: Do not enter

- USA: Dip warning

- Germany: Pedestrians forbidden

- Germany: Minimum Speed 30

- Germany: Entrance forbidden

- Germany: Give Way

- Random: Warning, cow abduction!
![image](https://github.com/user-attachments/assets/bc902f90-d194-40af-ae71-48433af6fbe5)

## Update 6: 29/10/24

![image](https://github.com/user-attachments/assets/87c2cfcf-895a-41b8-b432-d0a8e4ca8c0f)

Signs have been added. My hope is to confuse the AI algorithms, as is the prime directive for testing: "finding problems"


## Update 7: 29/10/24 - Future Ideas

The project is being submitted early, but here are some possible update ideas I had:

- A roundabout connecting many of the streets in the scene
- Some buildings for realism/vision
- More precise elevation for roads
- Side/dirt roads leading through the (idealised) forests
- A parking space
- A traffic light
