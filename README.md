# City-Traffic-Operating-System
This repository is about a intelligent traffic management system where a city is represented in the form of  a grid and the traffic is managed with the help of dynamic routing and intelligent traffic light adjustment at the junctions so that the cars reach their destination in the least time possible as well as maintaining a steady flow of traffic throughout the city ie reducing the average waiting time for each and every car at the traffic junctions.

It consists of 2 main files
-The cos series files ie cos11.py or cos13.py or cos14.py etc are the traffic simulation python files where I have created a GUI to represent a city grid and manage the flow of traffic
-main.cpp file is the standalone C++ program that recognizes the cars entering into the city grid from a video.

The final part is running carcount.cpp with cos13.py where carcount.cpp counts the car in the video and adds them to the city grid in the cos13.py. There is a bug in this integration due to which the addition of cars to the grid doesnt look seamless.

Additional Dependencies
Opencv python library


