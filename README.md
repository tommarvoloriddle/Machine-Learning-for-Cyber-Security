# Fine Pruning


## Prerequisites

Make sure you have the following installed:

- Python (version x.x)
- Jupyter Notebook (if using the fine_pruning.ipynb file)
- Required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/tommarvoloriddle/Machine-Learning-for-Cyber-Security.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Machine-Learning-for-Cyber-Security
    ```

3. Unzip the pruned models:

    ```bash
    unzip pruned_models.zip -d /content/pruned_models
    ```

## Running eval.py

Make sure to follow these steps to run the evaluation script.

1. Open a terminal.

2. Navigate to the project directory if you're not already there:

    ```bash
    cd /path/to/your-repository
    ```

3. Run the eval.py script with the following arguments:

    ```bash
    python eval.py /path/to/clean_data_filename /path/to/poisoned_data_filename /content/pruned_models/10.0
    ```

    Replace `/path/to/clean_data_filename` and `/path/to/poisoned_data_filename` with the actual paths to your clean and poisoned data files.

4. The script will use the specified model file from the pruned models directory.

## Note for Jupyter Notebook Users

If you prefer using the fine_pruning.ipynb file:

1. Open Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Navigate to the fine_pruning.ipynb file and open it.

3. Follow the instructions in the notebook for fine-tuning and evaluation.

## Additional Information

- For more details and customization options, refer to the README.md file.

