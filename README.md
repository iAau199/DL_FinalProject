# Automated Polyps Detection

## Deep Learning 2023-25268-T1

## Repository Overview

Welcome to the Automated Polyps Detection project repository. This project focuses on developing a computational method for the automatic detection of colorectal polyps using deep learning techniques. Colorectal cancer (CRC) is a significant global health issue, and improving the accuracy of polyp detection during colonoscopies is crucial in preventing CRC. 

In this repository, you will find various implementations and strategies explored to enhance polyp detection accuracy, including the use of pre-trained models, data augmentation, fine-tuning, and testing with different datasets.

## Repository Structure

### Code Folder

- **FP_polypos.ipynb**: Contains the initial trial and version of the project using pre-trained models VGG16, Inception-V3, and ResNet50.

- **FP_polypos_fineTuning.ipynb**: Contains the code for the fine-tuning approach to address overfitting issues observed in the initial trials.

- **FP_polypos_data_augmentation.ipynb**: Contains the code for the data augmentation approach to address overfitting issues.

- **CVC-Clinic_DB.ipynb**: Contains the code for training the models on a different dataset (CVC-ClinicDB) while incorporating data augmentation and fine-tuning techniques.


## Conclusion

This project underscores the importance of addressing overfitting in deep learning models, especially in medical image analysis. Through continuous experimentation with fine-tuning, data augmentation, and different datasets, we aimed to develop a robust system for automatic polyp detection to assist in real-time during colonoscopies.
