# LidarDepthSet
LidarDepthSet is the first dataset for the fusion of low-cost solid-state LiDAR and consumer-grade RGB-D camera depth information, with a ground-truth camera field of view (cFOV) coverage of 100% and an effective pixel density greater than 95%. It contains both underground parking lot and the karst cave scenes, representing (semi) structured and unstructured subterranean environments, respectively.

![image](https://github.com/Goughhhhhh/LidarDepthSet/blob/main/images/Sample.png)

# Dataset Download
The dataset is currently being organized and is coming soon.

# Dataset Structure
The dataset includes (semi) dense RGB-D camera depth images "depth", sparse LiDAR point clouds "lidar", and sparse LiDAR depth maps "lidar_depth". Additionally,  we also provide timestamp alignment files "associations.txt" for RGB-D camera depth images and LiDAR point clouds, as well as transformation matrices "transformations.txt" for two consecutive frames of point clouds in time series. The dataset structure is shown below.

![image](https://github.com/Goughhhhhh/LidarDepthSet/blob/main/images/structure.png)
