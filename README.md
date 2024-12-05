# LidarDepthSet
A dataset for the fusion of low-cost solid-state LiDAR and consumer-grade RGB-D camera depth information.

![image](https://github.com/Goughhhhhh/LidarDepthSet/blob/main/images/Sample.png)

# Dataset Download
The dataset is currently being organized and is coming soon.

# Dataset Structure
The dataset includes (semi) dense RGB-D camera depth images "depth", sparse LiDAR point clouds "lidar", sparse LiDAR depth images "lidar_depth", and groundtruth dense depth images "groundtruth". Additionally,  we also provide timestamp alignment files "associations.txt" for RGB-D camera depth images and LiDAR point clouds, as well as transformation matrices "transformations.txt" for two consecutive frames of point clouds in time series. The dataset structure is shown below. The format of images is *.png, and the format of point clouds is *.pcd.

![image](https://github.com/Goughhhhhh/LidarDepthSet/blob/main/images/Structure.png)

# Acquisition Set
The set consists of a Livox Avia solid-state LiDAR and a RealSense D435i RGB-D camera. The Avia's FOV is 70.4° x 77.2°, and the D435i's FOV is 64° x 41°. We construct the rigid assembly of LiDAR and RGB-D cameras as shown in figure. Thanks to our mounting method and the large vertical FOV of the Avia, the LiDAR's camera FOV can cover up to 100%.

![image](https://github.com/Goughhhhhh/LidarDepthSet/blob/main/images/Set.png)
