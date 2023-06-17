# Malware Image Classification with CNN

This project employs CNN to classify malware based on their images.

## Abstract
Using the malimg dataset of grayscale malware images, the goal of this project is to develop an accurate model for categorizing different types of malware. By leveraging shared visual characteristics, the approach represents malware binaries as grayscale images and groups similar types of malware based on layout and texture similarities within families.

## Key Features
- Malware image classification using Convolutional Neural Networks (CNN)
- Dataset preprocessing and augmentation techniques
- Baseline Logistic Regression (LR) model for comparison
- Evaluation metrics for performance analysis
- Heatmap visualization for interpretability and explainability

## Getting Started
### Prerequisites
- Python 3.x
- Required Python packages (specified in `requirements.txt`)

### Installation
1. Clone the repository:
git clone https://github.com/vaishnaviu/Malware-Image-Classifier-with-CNN.git
cd Malware-Image-Classifier-with-CNN

2. Install the required Python packages:
pip install -r requirements.txt
 
### Dataset
- The altered malimg dataset and additional dataset used for testing can be obtained from the following sources:
- [Malimg Dataset](https://www.kaggle.com/datasets/ikrambenabd/malimg-original)
- [Additional Dataset](https://www.kaggle.com/c/malware-classification/data?select=train.7z)

## Usage
1. Prepare the dataset by following the instructions provided in the repository.
2. Run the `main.py` file to train and evaluate the models:
   python main.py

## Results
The trained CNN model achieved an accuracy of 98% on the testing set, outperforming the baseline Logistic Regression model. Heatmaps were generated to visualize important regions in the images that contribute to the model's predictions.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- [Malimg Dataset](https://www.kaggle.com/datasets/ikrambenabd/malimg-original)
- Research papers and references mentioned in the project report


