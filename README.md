# Deception Detection Using Speech Processing

![Block Diagram](block_diagrams.png)

## Research Question
Can a machine learning model, trained on extracted audio features, accurately distinguish between truthful and deceptive speech across various natural languages?

## Objective
- To design and implement a machine learning-based system that classifies speech recordings as truthful or deceptive.
- To extract and analyze acoustic features that may indicate patterns of deception.
- To evaluate multiple models and compare their performance using classification metrics.

## Project Structure
- `Project Report.ipynb`: Main notebook containing all code, feature extraction, model training, evaluation, and analysis.
- `data/`: Folder where audio datasets (not included here) should be stored.
- `features/`: Stores extracted features (optional if not regenerated each run).
- `models/`: Saved models and related artifacts.

## Methods Used
- Audio processing using `librosa` and `pydub`
- Feature extraction (MFCCs, pitch, energy, etc.)
- Machine learning models: Logistic Regression, Random Forest, and Support Vector Machines
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score
