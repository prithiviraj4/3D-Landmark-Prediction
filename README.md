### 3D-Landmark-Prediction
# 3D Facial Landmark Prediction Using Python 


## Overview

This repository presents an efficient and flexible approach for real-time facial landmark prediction leveraging Google’s pre-trained MediaPipe model in Python. The project overlays user-specified facial landmarks onto images, video frames, enabling applications in gesture recognition, human-computer interaction, augmented reality, and more. It is designed for use in Google Colab and is optimized for both sparse (5–68 points) and dense (up to 468 points) facial landmark detection, working robustly even on mobile and low-resource platforms.


## Features

- **Real-time facial landmark prediction** (sparse and dense) using MediaPipe.
- **Overlay of predicted landmarks onto input images & videos** for visualization and analysis.
- **Multi-face support:** Simultaneous tracking and prediction on multiple faces per frame.
- **User-defined number of facial landmarks:** Flexible output and visualization for different needs.
- **Automatic FPS calculation and image & video saving** with overlays.
- **Simple integration with Google Colab and Google Drive** for cloud-based workflows.

## Methodology

- Uses MediaPipe’s Face Mesh for both sparse and dense landmark predictions.
- Supports highlighting an arbitrary number of facial landmarks (maximum 468 for MediaPipe Face Mesh).
- Each processed frame overlays landmarks, computes and displays FPS, and saves the annotated result for later review.

## Results

- Accurately predicts facial landmarks across diverse videos, with overlays for visual analysis.
- Multi-face support provides robust tracking in challenging scenarios.
- Real-time performance suitable for applications like AR, gesture control, and avatar animation.

## Future Work

- Improvement in dense landmark precision and 3D facial reconstruction.
- Expanded cross-platform support for mobile and IoT devices.
- Integration with voice/gaze tracking for multimodal interaction.
- Advanced mapping to virtual assets for innovative AR/VR filters and controls.

## References
[1] P. Chandran, G. Zoss, P. Gotardo, and D. Bradley. Infinite 3d landmarks: Improving continuous 2d facial landmark detection. Computer Graphics Forum, 43(6), June 2024.
[2] Prashanth Chandran, Gaspard Zoss, Paulo Gotardo, and Derek Bradley. Continuous landmark detection with 3d queries. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pages 16858–16867, June 2023.
[3] Google. Mediapipe: Face mesh. https://google.github.io/mediapipe/ solutions/face_mesh.html, 2023. Accessed: 2024-10-28.
[4] Yury Kartynnik, Artsiom Ablavatski, Ivan Grishchenko, and Matthias Grundmann. Real-time facial surface geometry from monocular video on mobile gpus. In CVPR Workshop on Computer Vision for Augmented and Virtual Reality 2019, Long Beach, CA, 2019.
