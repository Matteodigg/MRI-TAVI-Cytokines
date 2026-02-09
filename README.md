# MRI - TAVI: Cytokines Project
This repository contains the new Neuro Fertleman Project

## Installation

To install the required modules follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Matteodigg/MRI-TAVI-Cytokines
    ```

2. **Create a Virtual Environment**:

    ```bash
    cd MRI-TAVI-Cytokines/
    python -m venv venv/MRI-TAVI-Cytokines
    ```

3. **Activate the Virtual Environment** (for Unix-based systems):

    ```bash
    source venv/MRI-TAVI-Cytokines/bin/activate
    ```

4. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

5. **Add the virtual environment to Jupyter Lab**: register the virtual environment as a kernel so it appears as an option in Jupyter Lab:

    ```bash
    python -m ipykernel install --user --name=MRI-TAVI-Cytokines --display-name "MRI-TAVI-Cytokines"
    ```

6. **Use the MRI-TAVI-Cytokines kernel**: use the registered kernel in Jupyter to run code in the notebook.