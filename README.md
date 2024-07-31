### The above script takes the following inputs to check the lidar and camera registration. 
> 1. Camera Image
> 2. Lidar PCD file ( This file must contain pointcloud corresponding to the camera Image )
> 3. Lidar frame to Camera frame Projection Matrix (I got this matrix using MATLAB lidar camera calibration application)
> 4. Camera Intrinsic Matrix

### The script is tested on Anaconda environment with the following packages
> a. Numpy (1.26.4)
> b. Matpolotlib
> c. Open3d
> d. pytorch(2.3.0)

### The output images upon overaying lidar onto the camera image looks like this

![overlayed image](https://github.com/Juss-Chill/point_cloud_camera_reg_check_Script/tree/master/assets/Overlay_screenshot_09.07.2024.png)
