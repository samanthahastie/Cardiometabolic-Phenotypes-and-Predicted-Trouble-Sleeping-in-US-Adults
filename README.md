# Cardiometabolic Phenotypes and Predicted Trouble Sleeping in US Adults

### University of Michigan | Master of Applied Data Science

Contributors: Yasthil Singh, Seema Guruvadoo, and Samantha Hastie

Project Description: This project explores cardiometabolic phenotypes in NHANES data in order to evaluate if the addition of phenotype membership improves prediction of sleep trouble beyond an initial supervised model.

## Setup

This project uses Python with Jupyter notebooks for data analysis and modeling.

1. Create and activate a virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter:

   ```bash
   jupyter notebook
   ```

4. Open `main_branch.ipynb`.

## Reproducing Results

To reproduce the notebook outputs, run `main_branch.ipynb` from the repository root after installing the dependencies above. The notebook uses repo-relative paths, so the working directory should be this project folder when the notebook is run.

Recommended workflow:

1. Open the project folder locally.
2. Activate the virtual environment.
3. Start Jupyter or open the notebook in PyCharm.
4. Run `main_branch.ipynb` from top to bottom.

## Data

The notebook loads NHANES `.xpt` files from the repository's `data/` folder by default. The data are organized by source category:

- `data/Demographic/`
- `data/Examination/`
- `data/Lab/`
- `data/Questionnaire/`

The repository includes the selected NHANES files used by the notebook, not the full downloaded NHANES data folder.

The source data are from the CDC NHANES 2017-March 2020 pre-pandemic cycle: https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2017-2020

If running the notebook in Google Colab with Google Drive, mount Drive and update the `DATA_DIR` variable near the top of `main_branch.ipynb` to point to the Drive data folder.

When data loading works correctly, the notebook should print all 21 selected NHANES files and their shapes.
