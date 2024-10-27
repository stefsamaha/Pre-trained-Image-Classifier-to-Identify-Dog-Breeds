# **Image Classification for a City Dog Show**

## **Project Overview**

This project focuses on using a pre-built image classification algorithm to identify dog breeds for a citywide dog show. The goal is to ensure that only legitimate dog images are registered by identifying whether images depict dogs and, if so, classifying the breed. 

The classification algorithm (based on CNN models) is provided, and your primary task is to apply Python programming skills to use the classifier effectively. This project will also give you experience in comparing different CNN architectures, such as ResNet, AlexNet, and VGG, for accuracy and runtime.

## **Objectives**

1. **Identify Dogs**: Correctly identify which images are of dogs (even if the breed is misclassified) and which images are not of dogs.
2. **Classify Dog Breeds**: For images identified as dogs, correctly classify the breed.
3. **Compare CNN Architectures**: Evaluate ResNet, AlexNet, and VGG models to determine which achieves the best performance.
4. **Assess Runtime**: Compare the models' trade-offs between accuracy and runtime, determining if a faster solution could still yield acceptable results.

---

## **Project Structure**

- **`check_images.py`**: The main script that you will modify to complete the project. This script contains `TODO` comments indicating where code needs to be added to meet the project requirements.
- **`classifier.py`**: A pre-trained classifier that labels the images. You do **not** need to modify this file.
- **`pet_images/`**: The folder containing images of dogs and other animals that need to be classified.
- **`dognames.txt`**: A list of valid dog breeds, used to classify images as either "dogs" or "not dogs."
- **`print_functions_for_lab_checks.py`**: Helper functions to check parts of your code.

---

## **Setup Instructions**

### **Prerequisites**
You will need to install the following Python packages:
- Python 3.x
- NumPy
- PIL (Python Imaging Library)
- argparse (this is included by default in Python)

### **Installing Dependencies**
You can install the required packages by running the following command:

```bash
pip install numpy pillow

