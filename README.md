# 3D-QSAR and Drug Design Analysis

A computational chemistry and machine learning project that explores the relationship between molecular structure and predicted solubility. The workflow processes chemical structures, generates 3D molecular conformations, calculates molecular descriptors, and applies machine learning for property prediction.

- **Molecular Input:** Processes chemical structures represented as SMILES.
- **3D Conformer Generation:** Generates molecular conformations using RDKit ETKDG.
- **Geometry Optimization:** Applies UFF optimization to generated conformers.
- **Molecular Descriptors:** Extracts molecular features for structure–property analysis.
- **Solubility Prediction:** Uses machine learning to predict molecular solubility from the available dataset and descriptors.
- **Model Evaluation:** Evaluates predictions using the metrics implemented in the project.

## Technologies Used

Python · RDKit · Pandas · NumPy · Scikit-learn · Molecular Descriptors

## Project Workflow

1. Load the molecular dataset and read the SMILES representations.
2. Process molecular structures using RDKit.
3. Generate 3D conformers with ETKDG and optimize their geometry using UFF.
4. Calculate molecular descriptors for analysis.
5. Prepare the features and target values for machine learning.
6. Train and evaluate the solubility prediction model.

## How to Run

1. Clone or download the repository.
2. Install RDKit and the other Python dependencies used by the notebook or script.
3. Place the required dataset in the expected location.
4. Update the input path if necessary.
5. Run the notebook or Python script.

## Project Status

The project covers molecular structure processing, 3D conformer generation, geometry optimization, molecular descriptor analysis, and machine learning-based solubility prediction.

> **Note:** The dataset and exact dependency list should be checked against the repository before running the project.
