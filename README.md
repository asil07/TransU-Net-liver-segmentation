# 🧠 TransUNet: Transformer Meets U-Net for Medical Image Segmentation 🩺

Welcome to the **TransUNet** repository! This project combines **Transformers** with the classic **U-Net** architecture to provide powerful segmentation results in the medical imaging field. Whether you're working with histopathological images or any other medical imaging data, TransUNet offers a cutting-edge approach to achieve precise segmentation.

## 🌟 Key Features


- **Hybrid Architecture**: Merges the self-attention mechanism of **Transformers** with the localization strength of **U-Net**.
- **Multi-Scale Feature Extraction**: Captures both global and local information, crucial for medical image analysis.
- **Optimized for Medical Image Segmentation**: Specifically tuned to handle the unique challenges of medical imaging, such as varying resolution and structure sizes.
- **Flexible and Adaptable**: Suitable for a wide range of segmentation tasks, including liver tumor detection, lesion segmentation, and histopathological image analysis.

## ❇ TransUNet Segmentation Results

This figure shows a comparison between the **input images**, **ground truth masks**, and **predicted masks** generated by the TransUNet model:

- **Input Image (left)**: The original histopathological patch images used for model input.
- **Ground Truth (middle)**: Manually annotated masks showing the actual regions of interest (e.g., tumor areas).
- **Predicted Mask (right)**: The TransUNet model's predicted segmentation results.

![Segmentation Results](https://github.com/user-attachments/assets/7671caf0-58f0-4724-a6c0-686d81927cbb)

## 🛠 Installation

To get started with TransUNet, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/asil07/trans-unet.git
cd trans-unet
pip install -r requirements.txt
