# final_project_hybrid_brain

## Overview
This document describes the structure, dependencies, and usage of the notebook. The overview cell in the notebook did not include a summary, so this section is intentionally brief.

## Notebook Stats
- Total cells: **12**
- Code cells: **12**
- Markdown cells: **0**

## Table of Contents (from notebook headings)
_No headings found in markdown cells._

## Dependencies
**Third-party**

- kagglehub
- keras
- matplotlib
- numpy
- pandas
- skimage
- sklearn
- tensorflow
- tqdm

**Standard library**

- os
- time

> Tip: You can create a `requirements.txt` with the third-party list above and install via `pip install -r requirements.txt`.

## API Reference (functions & classes defined in code cells)
### Functions
- **`preprocess_and_cluster(image_path)`**
- **`preprocess_and_cluster(image_path)`**
- **`preprocess_and_cluster(image_path)`**
- **`plot_history(hist)`**
- **`calculate_metrics(true_labels, predicted_labels)`**

## Data Inputs & Outputs (guessed from code)
_No obvious data file references detected._

## How to Run
1. Create and activate a Python 3.10+ environment.
2. Install the required packages (see *Dependencies* below).
3. Open the notebook:
   ```bash
   jupyter lab IEEEbrain.ipynb
   ```
4. Run cells from top to bottom. If the notebook expects input files, place them in the paths noted under *Data Inputs & Outputs*.


## Reproducibility Tips
- Set a random seed in NumPy/PyTorch/TF if training or sampling is involved.
- Record environment details with:
  ```python
  import sys, platform; print(sys.version, platform.platform())
  ```
- If the notebook writes figures or results, consider adding `plt.savefig()` or file write paths to keep outputs organized.

## License & Citation
If this notebook is based on a paper, dataset, or external code, add proper citations here.
