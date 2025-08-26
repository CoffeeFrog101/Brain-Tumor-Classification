# Brain-Tumor-Classification

## Description

This is a final year thesis that implements a neural network for classifying different types of brain tumors from MRI scans. The system can identify three types of tumors: glioma, meningioma, and pituitary tumors using convolutional neural networks (CNNs).

The project uses VGG16 as the primary model architecture with LeNet5 implemented for performance comparison. The system achieves approximately 95% accuracy with VGG16 and 85-90% accuracy with LeNet5.

## Why?

This project addresses the possibilities of critical need for fast and accurate brain tumor detection in medical imaging.  
The motivation includes:

- **Medical Impact**: Providing radiologists with an automated tool for more accurate diagnosis
- **Patient Care**: Helping improve prognosis for patients with brain tumors through early and precise detection
- **Efficiency**: Offering a rapid analysis method for MRI scans
- **Learning Opportunity**: Gaining hands-on experience with CNNs and applying cutting-edge research in medical image analysis

The proposed method involves pre-processing MRI scans to extract relevant features, training CNNs using datasets of MRI scans with and without brain tumors, and fine-tuning architecture and hyperparameters for optimal performance.

## Quick Start

**Prerequisites**: Google Colab or similar Jupyter notebook environment

1. Open `BrainTumorDetection.ipynb` in Google Colab or any similar technologies
2. Update directory paths for your dataset location
3. Run the training code blocks
4. Expected results: ~95% accuracy (VGG16), ~85-90% accuracy (LeNet5)

⚠️ **Note**: AI models (~2.5 GB) are not included in the repository due to size constraints.

## Usage

### Training the Model
```python
# Run the training code block in the notebook
# Make sure to update dataset directories before running
```

### Testing the Model
```python
# Update the testing directories to point to your test data
# Run the evaluation blocks to see model performance
```

### Model Comparison
The notebook includes both VGG16 and LeNet5 implementations for performance comparison:
- **VGG16**: Primary model with ~95% accuracy
- **LeNet5**: Baseline comparison model with ~85-90% accuracy

## Contributing

Contributions are welcome! This is an educational project with potential for real-world medical applications.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes and test thoroughly
4. Update documentation as needed
5. Submit a pull request

### Areas for Improvement
- Model optimization and hyperparameter tuning
- Additional tumor type classification
- Data augmentation techniques
- Model deployment and web interface
- Performance optimization for larger datasets

**Have fun exploring medical AI! 🧠🔬**

 






