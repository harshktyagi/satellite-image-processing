# satellite-image-processing

Overview

This project analyzes forest cover changes over the past 10 years in a selected area (e.g., Delhi) using satellite images. It employs image processing techniques, including K-Means clustering and spectroscopy methods, to classify land cover types and assess deforestation trends.

Features

Satellite Image Acquisition: Uses publicly available satellite imagery.

Preprocessing: Noise reduction, resizing, and normalization of images.

Land Cover Classification: K-Means clustering for segmentation.

Spectroscopy Analysis: Identifies vegetation health.

Visualization: Generates comparative maps showing changes over time.

Technologies Used:

- MATLAB: Primary tool for image processing and clustering.

- K-Means Clustering: Unsupervised learning technique for land cover classification.

- Spectroscopy Techniques: Used to analyze vegetation health.


Usage

Place the satellite images in the data/ folder.

Run preprocess.m to clean and prepare images.

Execute kmeans_clustering.m to classify land cover types.

Use visualize_changes.m to generate comparison maps.

Analyze the results using the spectroscopy module.

Results & Findings

Displays land cover changes in a graphical format.

Provides quantitative data on deforestation trends.

Helps in environmental and urban planning assessments.

Future Enhancements

Integrating deep learning models for better classification.

Automating image acquisition from satellite APIs.

Expanding analysis to multiple regions.

Contributors:
-Harsh Tyagi   - parasharharsh.work@gmail.com
-Apoorva Pahal - apoorvapahal593@gmail.com

Acknowledgments

NASA, USGS, ISRO for satellite imagery.

MATLAB and Open Source Libraries for computational support.
