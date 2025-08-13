
# GTSRB Dataset Exploration

## Overview

This project focuses on exploring the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset. The aim was to load and inspect the dataset, analyze class distribution, and visualize sample images, including cropped regions of interest (ROI) that contain only the traffic signs.

## Dataset

* **Source**: Kaggle version of the GTSRB dataset
* **Number of classes**: 43 traffic sign categories
* **Data format**: Images and a CSV file (`Train.csv`) containing metadata
* **CSV columns**:

  * `Width`, `Height` — Original image dimensions
  * `Roi.X1`, `Roi.Y1`, `Roi.X2`, `Roi.Y2` — Coordinates for the bounding box around the traffic sign (Region of Interest)
  * `ClassId` — Numeric ID of the traffic sign class
  * `Path` — Relative file path to the image

## Work Done

1. **Loaded the dataset** from the provided CSV file and verified that there were no missing values.
2. **Added full file paths** to the dataset for easier image access.
3. **Analyzed class distribution** to check how balanced the dataset is, saving the results as a plot.
4. **Randomly sampled images** from the dataset and visualized them.
5. **Applied ROI cropping** so that only the traffic sign area is displayed, removing unnecessary background.

## Glossary

* **ROI (Region of Interest)** — The part of an image containing the object of interest, in this case, the traffic sign.
* **ClassId** — A numeric label identifying one of the 43 different traffic sign types in the dataset.

