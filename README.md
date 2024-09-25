# Image Classifier Adversarial Attack

This project demonstrates various adversarial attack methods on an image classifier using a pre-trained ResNet50 model.

## Project Overview

This project aims to explore the vulnerabilities of image classifiers by implementing and testing different adversarial attack techniques. The attacks include Fast Gradient Attack, Simba Attack, and DeepFool.

## Installation

To set up the environment for this project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/image-classifier-adversarial-attack.git
    cd image-classifier-adversarial-attack
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    ```bash
    source venv/bin/activate
    ```

4. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare the data:**

    Ensure that the `data` directory contains the `mapping.txt` file and the `images` directory with the images to be used for the attacks.

2. **Run the Jupyter Notebook:**

    Open the `main.ipynb` notebook and follow the instructions to run the cells and visualize the results.

## Project Structure

- `data/`: Directory containing the images and mapping file.
- `main.ipynb`: Jupyter notebook with the implementation of the adversarial attacks.
- `requirements.txt`: File listing the required Python packages.
