# Age and Sex Prediction from Facial Images

MSc coursework project (University of Bath, 2025). Grade: 77%.

Trained a custom CNN from scratch and fine-tuned a pre-trained model
(MobileNetV2) to predict age and biological sex from facial images.
Compared the two approaches to assess the trade-offs between transfer
learning and training a bespoke architecture on limited data.

## Results
- Custom CNN: 6.1 MAE for age, 91% Binary Accuracy for sex
- Transfer learning model: 6.9 MAE for age, 88% Binary Accuracy for sex
- Key finding: The MobileNetV2 model may be too complex for the small dataset.

## Dataset
UTKFace, available at https://www.kaggle.com/datasets/jangedoo/utkface-new. Not included in this repo. Used a smaller subset to save on compute (5000 images).

## Running the code