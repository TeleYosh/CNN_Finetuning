## Project Description
The goal of this project was to classify images of skin lesions into eight different classes (Melanoma, Melanocytic nevus, Basal cell carcinoma, Actinic keratosis, Benign keratosis, Dermatofibroma, Vascular lesion, Squamous cell carcinoma) using machine learning techniques. These methods can contribute to the early detection of skin cancer through non-invasive computer-aided diagnosis (CAD) systems.

## Dataset
The ISIC dataset consisted of 25,331 dermoscopic images of skin lesions, along with corresponding segmentation and metadata (age, sex, and anatomical position) when available. The data was split into a training-validation set (75%) and a test set (25%).

## Methodology
TLDR: I Finetuned an EfficientNetV2M on the unbalanced ISIC dataset using a custom weighted loss, data augmentation and ensemble learning techniques.

A more thorough description of the approach can be found in this [report](https://drive.google.com/file/d/1XffQMk59ofjgFAQvjOdnO2WwIxlYbk-y/view?usp=sharing).

## Results
I reached a balanced accuracy of 84%, compared to the human baseline of 80% achieved by dermatologists with 10 years of experience.
