# 🚀 Optimizing FasterRCNN ResNet-50 for Object Detection on Edge Devices

## Overview
My project focuses on the review, evaluation, and pruning of the FasterRCNN ResNet-50 model, with the aim of optimizing it for deployment on edge devices such as the Raspberry Pi. Leveraging the PyTorch framework, the project enhances the model's efficiency while maintaining its accuracy, making it suitable for real-time object detection in resource-constrained environments.

## 🔑 Key Components
- **🔍 Model Selection:** FasterRCNN ResNet-50 was chosen after an extensive literature review and comparison with other object detection models, including YOLO, EfficientDet, and RetinaNet.
- **📊 Model Evaluation:** The model was validated using standard metrics like mean Average Precision (mAP) and Frames Per Second (FPS), tested on the PASCAL VOC 2007 dataset.
- **✂️ Model Pruning:** To reduce the model's size and computational load, a magnitude-based pruning technique was implemented, targeting specific channels in the neural network while preserving the model's detection capabilities.

## ⚙️ Installation
### Prerequisites
- 🐍 Python 3.8+
- 🔥 PyTorch 1.7+
- 📦 torchvision
- 🔢 numpy
- 📈 matplotlib

## 🚀 Usage
### Model Evaluation
1. **Prepare the Dataset:** Download the PASCAL VOC 2007 dataset.
2. **Run Evaluation:**

### Model Pruning
1. **Prune the Model:**
2. **Evaluate Pruned Model:**

## 🌟 Project Highlights
- **📚 Comprehensive Literature Review:** Provided insights into the evolution and state of object detection models, leading to the selection of FasterRCNN ResNet-50.
- **🔧 Optimized for Edge Devices:** The pruned model is tailored for deployment on devices with limited computational resources, maintaining a balance between performance and efficiency.
- **🌐 Real-World Applicability:** This project enhances the feasibility of deploying advanced object detection models in real-time applications like video surveillance and autonomous systems.

## 🏆 Results
The pruned FasterRCNN ResNet-50 model achieved a significant reduction in size and computational requirements, with minimal impact on accuracy. Detailed results are available in the `results` directory.

## 👥 Contributions
- **Chukwuka Onwubolu** - Developer and Researcher
