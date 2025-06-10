# 3D Reconstruction Using Structure from Motion

A complete Structure from Motion (SfM) pipeline implemented from scratch in Python. The project reconstructs a 3D point cloud of a monument using image sequences and classical computer vision techniques.

## 🛠 Features
- Feature detection and matching with SIFT
- Essential matrix estimation and camera pose recovery
- Triangulation to generate 3D world points
- PnP + RANSAC for multi-view pose estimation
- Reprojection error visualization
- Colored 3D point cloud generation using Open3D

## 📁 Technologies Used
- Python
- OpenCV
- Open3D
- NumPy
- Matplotlib

## 💡 Highlights
- Manual SfM pipeline without any SfM library
- PLY file generation and visualization
- Error tracking over image frames

## 🧠 Skills Applied
- Epipolar geometry
- Triangulation & PnP algorithms
- Matrix transformations and 3D projection

## 📦 How to Run
1. Clone the repository
2. Place your image dataset in the `/monument_dataset` folder
3. Run `group21_code.py`


