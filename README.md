# Deep Learning for Wildlife Recognition from Drone Imagery

**MSc Thesis** — MBIT School, Madrid (2020–2021) · Grade: 10/10

Automated wildlife localization and classification on large areas using drone
images (optical + thermal) and deep learning.

## Problem

Manual wildlife surveys from drone footage are slow and error-prone. This project
automates animal detection and classification across large-area drone captures.

## Approach

1. **Image exploration & preprocessing** — optical and thermal drone image analysis
2. **Animal localization** — automated detection of animals in drone imagery
3. **Classification** — transfer learning with Inception v3 (pretrained on ImageNet)
4. **Explainability (XAI)** — model interpretability analysis of Inception v3 predictions

## Notebooks

| Notebook | Description |
|---|---|
| `Drone_Images_Exploration.ipynb` | Exploratory analysis of drone image data |
| `Sample_Drone_Images.ipynb` | Sample visualization and preprocessing |
| `Animal_Localization_Explained.ipynb` | Localization pipeline with explanations |
| `Automatic_Wildlife_Localization_Program.ipynb` | End-to-end automated localization |
| `Inception_v3_Transfer_Learning.ipynb` | Transfer learning for animal classification |
| `XAI - Explicabilidad_Modelo_Inceptionv3.ipynb` | Explainability / interpretability analysis |

## Tech Stack

Python · OpenCV · NumPy · Keras · TensorFlow · Inception v3

> Due to privacy agreements, the complete dataset and some results cannot be disclosed.

