[tutorial link](https://youtu.be/Z-65nqxUdl4?si=TSOePM4MLGNrGYkw)

## Computer Vision
1. <b>Detection</b>
    - identifies and locates objects in an image or video
    - outputs bounding boxes around detected objects

<br>

2. <b>Classification</b>
    - Assigns a label or category to an image
    - No bounding box -- just a single class prediction

<br>

3. <b>Segmentation</b>
    - divides an image into meaningful regions (pixel-level classification)
    - two types:
        1. Semantic Segmentation 
            - objects of the same type are not distinguished (e.g., all cars look the same).
        2. Instance Segmentation 
            - similar to semantic segmentation but distinguishes between individual objects.

<br>

4. <b>Pose Estimation</b>
    - pose estimation detects keypoints (like head, shoulders, elbows, hands, knees, feet) in an image to track body posture.
    - types of pose estimation:
        1. 2d pose estimation
            - identifies keypoints in 2d space (x, y coordinates)
        2. 3d pose estimation
            - adds depth (x, y, z) to estimate spatial positioning