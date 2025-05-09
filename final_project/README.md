# ECCS 3401 Final Project - Quentin Osterhage (SVM / Linear SVC)

This project demonstrates the use of dimensionality reduction techniques (UMAP and PCA) to optimize the training of linear SVC model on the MNIST dataset. 

The project is implemented in a Jupyter Notebook (`project2.ipynb`).

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.7 or later
- Jupyter Notebook

You can install the required Python libraries using the `requirements.txt` file provided in the project directory.

```bash
pip install -r requirements.txt
```

## Running the Project

1. Clone the repository or navigate to the project directory.

2. Open the Jupyter Notebook server:

   ```bash
   jupyter notebook
   ```

   Or:

   Run in VsCode w/ extensions

3. If using the Jupyter Notebook interface, navigate to the `final_project` folder and open `svc_final_project.ipynb`.

4. Execute the cells sequentially to:
   - Import libraries
   - Load and preprocess the MNIST dataset
   - Establish baseline SVC model performance on preprocessed dataset
   - Perform dimensionality reduction using UMAP and PCA
   - Visualize UMAP and PCA Performance
   - Train SVM models with hyperparameter tuning
   - Visualize results and evaluate model performance

## Notes

- The notebook includes visualizations for 2D and 3D plots of the data after dimensionality reduction.
- Grid search is used to optimize hyperparameters for the SVM classifier.
- Ensure that your system has sufficient memory to handle the MNIST dataset and the computations involved.
    - Can edit sample sizes, max iterations, and n_jobs (for parallel processing) to improve performance

