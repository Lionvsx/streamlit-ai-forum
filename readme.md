# Streamlit App for ABC Algorithm in Machine Learning

This Streamlit application demonstrates the use of the Artificial Bee Colony (ABC) Algorithm for optimizing parameters of a Support Vector Machine (SVM) model using various datasets from the `sklearn` library.

## Features

- Interactive parameter tuning for SVM using the ABC Algorithm.
- Choice of datasets: Iris, Digits, and Wine.
- Real-time visualization of the algorithm's progress and accuracy improvement.

## Prerequisites

Before running this application, you will need the following:

- Python 3.6 or later.
- Streamlit
- Other Python libraries: `sklearn`, `numpy`, `matplotlib`

## Installation

To set up the environment and run the application, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone [URL_of_Your_Repository]
   cd [Repository_Name]
    ```
   
2. **Create a Virtual Environment**

   On Windows:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
   
   On macOS and Linux:
   ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the Required Packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application**
    ```bash
    streamlit run app.py
    ```
   
## Usage
After running the command, Streamlit will open a new tab in your default web browser. Use the sidebar to select the dataset and set the parameters for the ABC algorithm. Click the "Run ABC Algorithm" button to start the optimization process and visualize the results.