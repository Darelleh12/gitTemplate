# Skin Disease Diagnosis Using Computer Vision

Which supervised learning model (e.g., CNN, ResNet, Vision Transformer, or EfficientNet) provides the most accurate classification of skin lesions using dermatoscopic images, and how does including patient metadata (such as age, sex, and lesion location) affect model performance?
*Uncovered and meticulously analyzed three distinct biases present in ChatGPT, employing advanced Python techniques and data analysis methodologies, all within AI4ALL's cutting-edge AI4ALL Ignite accelerator.*


## Problem Statement <!--- do not change this line -->

Describe the motivation for this project, why it is relevant, and what its impacts are.

*EXAMPLE:*
*Given the substantial daily output of responses, the identification and mitigation of ChatGPT's biases become critical, safeguarding both the multitude of users and the far-reaching consequences they may influence.*

## Key Results <!--- do not change this line -->

fter comparing CNN, ResNet, and EfficientNetB0, we found that:
EfficientNetB0 achieved the best overall performance across accuracy, recall, and F1-score, particularly in detecting critical classes like melanoma.
Including patient metadata (age, sex, anatomical site) improved performance modestly
This confirms that:
The model architecture matters significantly in lesion classification.
Contextual data (metadata) enhances accuracy, especially for clinically important classes.
AI’s broader impact:
This research shows that well-designed AI can support medical diagnosis, but:
Model bias (e.g., by skin tone or age group) needs mitigation.
Ethical deployment requires transparency and clinician oversight.

## Methodologies <!--- do not change this line -->

Target Lesion Types
Top 4 Diagnoses:
Melanocytic nevi (NV) (Most common benign)
Melanoma (MEL) (High-risk malignant)
Basal cell carcinoma (BCC) (Common skin cancer)
Benign keratosis-like lesions (BKL) (Non-cancerous)

*To accomplish this, we created the models using CNN, ResNet, Vision Transformer, to undergo surpervised machine learning to classify dermatoscopic images into the top 4 diagnosis. Each data class was evenly training, validating, and testing stages. 

## Data Sources <!--- do not change this line -->

ISIC 2019 Challenge Dataset
25,331 high-quality dermatoscopic images of skin lesions
Each image is labeled with one of nine diagnostic categories, including:
- *Melanoma (MEL)*
- *Melanocytic nevus (NV)*
- *Basal cell carcinoma (BCC)*
- *Actinic keratosis (AK)*
- *Benign keratosis-like lesions (BKL)*
- *Dermatofibroma (DF)*
- *Vascular lesions (VASC)*
- *Squamous cell carcinoma (SCC)*
- *Unknown (UNK)*

Metadata file is included for each image, containing:
-Patient’s approximate age (age_approx)
-Sex (sex)
-Anatomical site of the lesion (anatom_site_general)
-Lesion ID (can be used to track images from the same lesion)

Kaggle Dataset: [Link to Kaggle Dataset](https://www.kaggle.com/datasets/andrewmvd/isic-2019/data)*

## Technologies Used <!--- do not change this line -->

- *Python*
- *pandas*
- *OpenAI API*
- *CNN*
- *ResNet*
- *Vision Transformer*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Alisa Teige ([john.doe@example.com](mailto:john.doe@example.com))*
- *Grish Tautam ([john.doe@example.com](mailto:john.doe@example.com))*
- *Emmanuel Moses ([john.doe@example.com](mailto:john.doe@example.com))*
- *Tory Leone ([john.doe@example.com](mailto:john.doe@example.com))*
- *Darelle Herrera ([jane.smith@example.com](mailto:jane.smith@example.com))*
