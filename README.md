# Optimizing Synthetic Data Using Differential Evolution Algorithm

## Overview
This repository implements a **Differential Evolution Algorithm (DEA)** to optimize synthetic household data. The project demonstrates the creation of synthetic datasets that closely resemble real-world demographic distributions. The primary objective is to fine-tune the DEA for efficient optimization and compare the generated synthetic data with empirical data.

Key files include Python scripts and Jupyter Notebooks for analysis and visualization:
- **The `num_person variable with comparison graph` Notebook** highlights the comparison between the optimal synthetic solution and empirical data proportions.
- Additional files demonstrate parameter analysis and algorithm behavior via box plots.

---

## Prerequisites

### Python and Libraries
- **Python (3.8 or higher)**: Install from [python.org](https://www.python.org/downloads/).
- **Required Libraries**: Install dependencies using:
  ```bash
  pip install numpy pandas matplotlib
### Optional: Jupyter Notebook

For an interactive experience, install Jupyter Notebook:

```bash
pip install jupyter
```
---

## Dataset

1. Download the `Household_data.csv` dataset and place it in the project directory.
2. Ensure the dataset format aligns with the code. It should include household configurations as described in the methodology section.

---

## Running the Code

### Using Jupyter Notebook

1. Open a terminal and navigate to the directory containing the notebooks.
2. Run the following command to start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

3. Open the desired notebook (e.g., `num_person_variable_with_comparision_graph.ipynb`) and execute the cells sequentially.

### Using Python Scripts

1. Navigate to the directory containing the Python script.
2. Run the following command to execute the script:

    ```bash
    python your_script.py
    ```

---

## Results

### Key Outputs

- **Boxplots:** These plots visualize the effects of parameter variations on computational time and fitness.
- **Comparison Graphs:** Bar charts that compare synthetic data proportions with empirical data, highlighting the DEA's optimization performance.

### Notable Findings

- The `num_person_variable_with_comparision_graph.ipynb` notebook demonstrates the fitness improvements achieved by optimizing synthetic data to match real-world distributions.
- Other notebooks analyze parameters such as mutation solutions, iterations, and offspring pairs to provide insights into their impact on the algorithm's efficiency.
