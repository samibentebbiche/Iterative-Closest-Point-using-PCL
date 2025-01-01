# Point Cloud Fusion Program
This is a small program designed to compute the alignment (fusion) of point clouds using the Point Cloud Library (PCL). It utilizes algorithms for point cloud registration, specifically Iterative Closest Point (ICP), to merge multiple point clouds into a single, unified 3D model.

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
