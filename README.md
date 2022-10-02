# IMDS-ZJF
The code requires python3 (>=3.5) with the development headers. The current version of the code only supports TensorFlow 1.x (>=1.5). 
1. Start it with the python file 'vmain'. Attention: You need to enter your own vehicle file.
2. 'xmlTocsv' is used to convert xml to csv for data processing.
3. 'dqn' is used to generate an appropriate set of seed vehicles to update the time point.
The simulation platform is based on a real map of Shenbei District, Shenyang City, China. The map information is achieved from the OpenStreetMap. Then, we apply SUMO to generate the trajectory data of vehicle fitting on these maps. 
