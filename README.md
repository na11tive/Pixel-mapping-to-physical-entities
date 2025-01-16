# Pixel-mapping-to-physical-entities
![image](https://github.com/user-attachments/assets/98cb5b20-d789-493f-a757-83fa16ef69d5)
SGS-3DRecon Framework
This repository contains the implementation of the Segformer-GAN-Sobel 3D Reconstruction (SGS-3DRecon) framework, developed as part of a study on automated tree trunk volume estimation in large-scale forest surveys across various scenarios.

Background
Tree trunk volume estimation plays a crucial role in forest resource monitoring and management. Traditional methods, such as handheld LiDAR, often require significant manual effort and equipment costs. This project introduces a fully automated framework leveraging photogrammetric methods to achieve efficient and accurate tree trunk segmentation, 3D reconstruction, and volume calculation.

Features
Segformer Integration: Utilizes a transformer-based architecture for precise image segmentation.
GAN Inversion: Completes occluded areas of tree trunks, enhancing segmentation accuracy in complex forest scenarios.
Sobel Operator: Refines tree trunk boundaries, improving edge detection for better 3D reconstruction.
Scalable Application: Tested on diverse datasets across multiple tree species and scenarios, including natural forests, plantations, and urban parks.

Requirements
Python 3.8 or higher
PyTorch 1.10 or higher
CUDA 11.1 or higher (optional, for GPU acceleration)

Results
Our method achieves competitive performance across various scenarios:
![image](https://github.com/user-attachments/assets/2b2fd790-213b-414c-918f-0d8c6566ac5b)
![image](https://github.com/user-attachments/assets/b16f0c8d-1dab-48d9-ae1d-ff67eeadab09)

Natural Forest: IoU 82.65%, Dice 89.58%
Plantation: IoU 85.36%, Dice 91.22%
Urban Parks: IoU 90.38%, Dice 95.14%
For more details, refer to the associated paper.


Contact
For questions or collaborations, please contact yz13152988624@gmail.com.
