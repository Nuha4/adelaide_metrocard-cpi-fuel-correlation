
## Getting Started

You can run this analysis using Google Colab (recommended) or on your local machine.

### Prerequisites
-   Python 3.8+
-   Git (for cloning the repository)

### Option A: Running on Google Colab (Recommended)

1.  **Open Google Colab:**
    Go to [colab.research.google.com](https://colab.research.google.com).

2.  **Upload the Notebook and Data:**
    -   In Colab, go to `File` > `Upload notebook...` and select the `adl_metrocard_cpi_fuel_correlation.ipynb` file from your computer (after cloning or downloading this repository).
    -   In the Colab file explorer panel on the left, click the "Upload to session storage" icon and select the `metrocard_cpi_fuel_combined.csv` file.

    **Note:** The notebook is configured to read the data file from the root Colab directory. You do not need to mount Google Drive.

3.  **Install Dependencies:**
    Run the first code cell in the notebook to install all the required Python libraries.
    ```python
    !pip install pandas==2.2.2 numpy==1.26.4 matplotlib==3.8.4 seaborn==0.13.2 \
                scipy==1.12.0 scikit-learn==1.4.2 xgboost==2.0.3 statsmodels==0.14.2
    ```

4.  **Run the Analysis:**
    You can now run all the cells in the notebook sequentially to replicate the entire analysis from data loading to model evaluation.

### Option B: Running Locally

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Nuha4/adelaide_metrocard-cpi-fuel-correlation.git
    cd adelaide_metrocard-cpi-fuel-correlation
    ```

2.  **Create a Virtual Environment (Recommended):**
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install Dependencies:**
    ```bash
    pip install pandas==2.2.2 numpy==1.26.4 matplotlib==3.8.4 seaborn==0.13.2 \
                scipy==1.12.0 scikit-learn==1.4.2 xgboost==2.0.3 statsmodels==0.14.2
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    This will open a new tab in your web browser. Navigate to and open the `adl_metrocard_cpi_fuel_correlation.ipynb` file to run the analysis.
