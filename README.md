# ECE-276A-Particle-Filter-SLAM
Implementation of simultaneous localization and mapping (SLAM) with particle filter using real LIDAR data

## Code:
Particle Filter SLAM.ipynb: Jupyter notebook containing functions to perform coordinate transformations, predictions step, update step, resampling, and map update.  Also contains main loop to go through each time step in data.  
  
load_data.py: Python file provided by instructor used to load lidar and joint data
  
p2_utils.py:  Python file provided by instructor with functions to calculate map correlation and raytracing

## Results: 
### Map 1 - Dead Reckoning (no update step using LIDAR observations)
![alt text](https://github.com/jamessalem/ECE-276A-Particle-Filter-SLAM/blob/master/Final%20Maps/Dead%20Reckoning/lidar0_DR.png)

### Map 1 - Particle Filter SLAM (using LIDAR observations)
![alt text](https://github.com/jamessalem/ECE-276A-Particle-Filter-SLAM/blob/master/Final%20Maps/SLAM/lidar0.png)

### Map 2 - Dead Reckoning (no update step using LIDAR observations)
![alt text](https://github.com/jamessalem/ECE-276A-Particle-Filter-SLAM/blob/master/Final%20Maps/Dead%20Reckoning/lidar2_DR.png)

### Map 2 - Particle Filter SLAM (using LIDAR observations)
![alt text](https://github.com/jamessalem/ECE-276A-Particle-Filter-SLAM/blob/master/Final%20Maps/SLAM/lidar2.png)
