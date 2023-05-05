# Brain Tumor Classification

In this project, we developed a Convolutional Neural Network (CNN) to classify brain MRI images into three types of tumors: glioma, meningioma, and pituitary adenoma. If there is no tumor present, the image is classified as a no_tumor brain image. The dataset used for this project is the Brain Tumor MRI Dataset from the Kaggle platform. The dataset contains 7023 MRI images that are categorized into four classes: glioma, meningioma, pituitary, and notumor. We preprocessed the images and used data augmentation techniques to increase the size of the dataset.

We trained the model for 10 epochs. The model achieved an accuracy of 87.49% on the test set.

The main files in this repository are:

* Brain_Tumor.ipynb: Jupyter notebook containing the code for data preprocessing, data augmentation, model training, and evaluation.
* requirements.txt: Python packages required to run the code.
* README.md: Project description and instructions on how to use the code.

To reproduce our results, clone this repository, install the required packages using pip install -r requirements.txt, and run the brain_tumor_classification.ipynb notebook. You can also use our pre-trained model to classify new brain MRI images.

We hope that our project will contribute to the field of medical image analysis and help doctors in diagnosing brain tumors.
