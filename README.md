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

## Data

The notebook loads NHANES `.xpt` files from the repository's `data/` folder by default. The data are organized by source category:

- `data/Demographic/`
- `data/Examination/`
- `data/Lab/`
- `data/Questionnaire/`

If running the notebook in Google Colab with Google Drive, mount Drive and update the `DATA_DIR` variable near the top of `main_branch.ipynb` to point to the Drive data folder.
