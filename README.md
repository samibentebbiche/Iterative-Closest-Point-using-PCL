# Point Cloud Fusion Program
This is a small program designed to compute the alignment (fusion) of point clouds using the Point Cloud Library (PCL). It utilizes algorithms for point cloud registration, specifically Iterative Closest Point (ICP), to merge multiple point clouds into a single, unified 3D model.


![cloud Points](https://github.com/user-attachments/assets/e0825d42-66a7-42d2-94ad-65397a50247b)

## Current Functionality

Currently, the program:
- Takes a single `.ply` file as input.
- Applies simple transformations (rotation, translation) to the point cloud.
- Attempts to calculate the fusion of the point clouds using the ICP algorithm.

## Next Steps

- The next step will be to extend the functionality to handle multiple input `.ply` files and compute the fusion of these point clouds using ICP.

## Requirements
- **Point Cloud Library (PCL)**: Install PCL to handle 3D point clouds and perform operations such as ICP.
- **CMake**: For building the project.

## Usage

To compile the code, use the following steps:

   ```bash
   mkdir build
   cd build
   cmake ..
   make
   ./code_file_name.cpp cloud_point.ply NUMBER_OF_ITERATIONS```
