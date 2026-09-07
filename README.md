# Honey Bee Image Classification

A reproducible computer-vision study that distinguishes honey bees (**Apis**) from bumble bees (**Bombus**) using transfer learning.

## What this project demonstrates

- validation of image metadata and file availability;
- stratified train/validation/test splitting;
- TensorFlow input pipelines and data augmentation;
- MobileNetV2 transfer learning;
- accuracy, classification report, confusion matrix and ROC-AUC evaluation;
- explicit discussion of model limitations.

## Repository structure

- `codes/DTSense_Prediksi_Lebah_v1.ipynb`: complete analysis and modelling workflow
- `datasets/labels.csv`: image labels
- `images/`: labelled image dataset

## Run locally

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook codes/DTSense_Prediksi_Lebah_v1.ipynb
```

## Limitations

The dataset is relatively small and model performance may be influenced by image backgrounds and collection conditions. Independent validation is required before deployment.

## Acknowledgement

Developed as an extended and completed portfolio project based on learning material from DTSense. The workflow, implementation, evaluation structure and documentation in this repository were completed and revised by Muhammad Aziz.
