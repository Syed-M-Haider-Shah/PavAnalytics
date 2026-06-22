# PavAnalytics

Automating Pavement Condition Rating: A Deep Learning-Based Framework for Cycle Routes and Greenways.

## Overview

PavAnalytics is a deep learning framework designed to automatically assess pavement surface conditions from cycling infrastructure imagery.

The project includes:

- Fisheye Distortion Correction
- Pavement Condition Classification
- Explainable AI (Grad-CAM)
- Performance Evaluation

## Project Website
For additional project information, demonstrations, and results, visit:

Project Website: [https://www.paveanalytics.eu/]

## Publications

### Conference Papers
- Shah, S. M. H., Qureshi, W. S., Dea, G. O. and Ullah, I. (2025). Intelligent Pavement Condition Rating System for Cycle Routes and Greenways. In Proceedings of the 11th International Conference on Vehicle Technology and Intelligent Transport Systems - VEHITS; ISBN 978-989-758-745-0; ISSN 2184-495X, SciTePress, pages 668-675. DOI: 10.5220/0013505000003941
- Garcia, J. A. A., Shah, S. M. H., Baig, M. H., Qureshi, W. S. and Ullah, I. (2025). Enhancing Pavement Condition Assessment: A Comprehensive Review of Affordable Sensing Technologies for Cycle Tracks. In Proceedings of the 11th International Conference on Vehicle Technology and Intelligent Transport Systems - VEHITS; ISBN 978-989-758-745-0; ISSN 2184-495X, SciTePress, pages 676-682. DOI: 10.5220/0013505100003941
- M. H. Baig, J. A. Ayala Garcia, W. S. Qureshi, I. Ullah, Towards assessing cycleway pavement surface roughness using an action camera with imu and gps, in Proceedings of the 11th International Conference on Vehicle Technology and Intelligent Transport Systems - VEHITS, INSTICC, SciTePress, 2025, pp. 247–255. doi:10.5220/0013504900003941.


## Pavement Condition Rating Scale

We have introduced an intelligent pavement rating system for cycleways, named the Cycle Route Surface Index, a colour-coded, five-level rating system that combines visual inspection, roughness, vegetation, and drainage data to provide a clear and consistent pavement quality measure. 

![Pavement Condition Rating Scale](figures/Rating-scale.jpg)

## Project Structure

```text
PavAnalytics/
├── data/                  # Dataset and sample images
├── fisheye_correction/    # Fisheye distortion correction pipeline
├── classification/        # Pavement condition classification models
├── explainability/        # Grad-CAM and XAI visualisations
├── figures/               # Project diagrams and rating scales
└── README.md
```


## Technology Stack


### Core Libraries

| Library      | Purpose                                            |
| ------------ | -------------------------------------------------- |
| Python       | Core programming language                          |
| PyTorch      | Deep learning model development and training       |
| OpenCV       | Image processing and fisheye distortion correction |
| NumPy        | Numerical computations                             |
| Pandas       | Data handling and analysis                         |
| Matplotlib   | Visualisation and result analysis                  |
| Scikit-learn | Performance evaluation metrics                     |
| Transformers | Swin Transformer implementation                    |
| Pillow (PIL) | Image loading and processing                       |
| Grad-CAM     | Explainable AI visualisations                      |



## Status

The repository is currently under development. Source code, model checkpoints, installation instructions, and reproducibility documentation will be released following publication of the associated research papers.
