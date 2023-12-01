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
    unzip pruned_models.zip
    ```

## Running eval.py

Make sure to follow these steps to run the evaluation script.

1. Open a terminal.

2. Navigate to the project directory if you're not already there:

    ```bash
    cd Machine-Learning-for-Cyber-Security
    ```

3. Run the eval.py script with the following arguments:

    ```bash
    python eval.py /path/to/clean_data_filename /path/to/poisoned_data_filename /content/pruned_models/10.0
    ```
    Replace /content/pruned_models/10.0 with /content/pruned_models/4.0 or /content/pruned_models/2.0 for 4%, 2% repaired models
    Replace `/path/to/clean_data_filename` and `/path/to/poisoned_data_filename` with the actual paths to your clean and poisoned data files.

4. The script will use the specified model file from the pruned models directory.
   
5. Data
Download the validation and test datasets from [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq) and store them under data/ directory.
The dataset contains images from YouTube Aligned Face Dataset. We retrieve 1283 individuals and split into validation and test datasets.
bd_valid.h5 and bd_test.h5 contains validation and test images with sunglasses trigger respectively, that activates the backdoor for bd_net.h5.

## Note for Jupyter Notebook Users

If you prefer using the fine_pruning.ipynb file:

1. Open Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Navigate to the fine_pruning.ipynb file and open it.

3. Follow the instructions in the notebook for fine-tuning and evaluation.

