# Crop Yield Detection from Satellite Images

This repository contains the implementation of a crop yield detection system using satellite images. The project applies attention mechanisms and 3D Convolutional Neural Networks (3D CNNs) to efficiently process gigapixel satellite images by focusing on patches of interest, improving computational efficiency and prediction accuracy.

## Features

- **Patch Selection**: Extracts relevant patches of the image using self-attention.
- **3D CNN**: Processes volumetric data from selected patches for feature extraction.
- **Multi-Head Attention**: Aggregates features across attention heads for better representation.
- **Efficient Workflow**: Avoids processing the entire image, saving computational resources.

## Methodology

### Patch Selection

- Randomly select patches from gigapixel satellite images.
- Apply self-attention to focus on relevant patches.
  
### Feature Extraction
Use a 3D CNN with ReLU activation and dropout layers to extract features from the selected patches.

### Attention Mechanism
Implement multi-head attention to enhance feature representations by capturing nuanced relationships.

### Prediction
Feed aggregated features into a linear layer with sigmoid activation to generate final predictions.

### Results
The proposed solution efficiently processes gigapixel satellite images, focusing only on patches of interest to reduce computational costs and improve accuracy.

