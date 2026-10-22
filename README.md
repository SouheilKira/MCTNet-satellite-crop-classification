# MultiSource-Crop-Classification

Deep learning project for crop type classification using multi-temporal Sentinel-2 satellite imagery and environmental covariates.

---

## Project Overview

This project focuses on reproducing and extending the **MCTNet** architecture for agricultural crop classification from satellite image time series.

The main objective is to classify crop types using:
- Multi-temporal Sentinel-2 satellite observations
- Climate information
- Soil properties
- Topographic features

The project also studies the impact of integrating external covariates into the baseline model through ablation experiments and feature fusion strategies.

---

## Dataset

The dataset contains agricultural parcels from:
- Arkansas
- California

### Data Sources
- Sentinel-2 satellite imagery
- Climate covariates
- Soil attributes
- Topographic information

### Temporal Information
Each sample contains a temporal sequence of satellite observations across the growing season.

---

## Model Architecture

The implemented model is based on **MCTNet**, which combines:
- Temporal feature extraction
- Cross-temporal fusion
- Attention mechanisms
- Adaptive positional encoding

### Pipeline
1. Input temporal satellite sequence
2. Feature projection
3. Multiple CTFusion stages
4. Temporal pooling
5. Final crop classification

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## Training & Evaluation

The model is evaluated using:
- Accuracy
- F1-score
- Confusion Matrix
- Learning Curves

Experiments compare:
- Baseline MCTNet
- MCTNet + climate data
- MCTNet + soil data
- MCTNet + topography
- Full covariate fusion

---

## Results

The proposed model achieved strong classification performance while demonstrating the usefulness of environmental covariates for crop discrimination.

Example outputs:
- Training curves
- Validation accuracy
- Confusion matrices
- Feature analysis visualizations

---

## Team Members

- KAMELI Moncef
- Hadj-Ameur Ahmed
- Bentlidjan Souheil

---

## References

- MCTNet paper
- Sentinel-2 documentation
- Remote sensing crop classification literature

---

## License

This project is developed for academic and research purposes.