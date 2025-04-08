# opencv-feature-matching
This project implements three popular computer vision algorithms using OpenCV to detect and match keypoints between images and detect corners:

## ✅ Implemented Algorithms

1. **SIFT (Scale-Invariant Feature Transform)**  
   - Detects and matches keypoints between two images using SIFT.
   - Matches are visualized using `cv2.drawMatches`.

2. **ORB + RANSAC**
   - Detects keypoints using ORB.
   - Removes outlier matches using RANSAC to estimate a homography matrix.
   - Matches are shown before and after RANSAC filtering.

3. **Shi-Tomasi Corner Detection**
   - Detects corners using the Shi-Tomasi method.
   - Corners are visualized on a chessboard image with enlarged green circles.

---

## 🖼 Sample Images Used

- `box.png`  
- `box_in_scene.png`  
- `chessboard.png`
![chess](https://github.com/user-attachments/assets/36c6354e-fa3d-4c1c-9faa-caae30465adf)
![box_in_scene](https://github.com/user-attachments/assets/802f39d5-0e54-4f6e-830f-ebd54616451a)
![box_in_scene](https://github.com/user-attachments/assets/f0d0daf7-58bb-4b54-97af-6c72053eb0c1)







These images are commonly used in computer vision for keypoint and corner detection tasks.

---
