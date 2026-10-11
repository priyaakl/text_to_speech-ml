End-to-End Text-to-Speech Synthesis

Project Overview

This project explores machine learning techniques for converting written text into spoken audio.

We are using a Stanford CS229 Autumn 2018 project, End-to-End Text to Speech Synthesis, as our starting point. We aim to understand the original implementation, set up the environment, and test the models.

Models

The original project explores three approaches:

* Support Vector Regression (SVR)
* Simple Neural Network
* Sequence-to-Sequence (Seq2Seq) model with attention

Technologies

* Python
* TensorFlow
* NumPy
* SciPy
* Librosa
* tqdm
* Google Colab
* VS Code
* GitHub

Dataset

We plan to use the LJ Speech Dataset, which contains audio recordings and their corresponding text transcripts.

Dataset: https://keithito.com/LJ-Speech-Dataset/

Project Setup

Google Colab

We use Google Colab for notebook-based development and GPU access when available.

Install the required libraries in a notebook cell:

%pip install tensorflow librosa numpy scipy tqdm

Check the installation:

import tensorflow as tf
import librosa
import numpy as np
import scipy
import tqdm
print("TensorFlow:", tf.__version__)
print("GPU available:", tf.config.list_physical_devices("GPU"))

Fedora Linux with VS Code

Create and activate a virtual environment:

python3 -m venv .venv
source .venv/bin/activate

Install the required libraries:

python -m pip install --upgrade pip
python -m pip install tensorflow librosa numpy scipy tqdm

Project Workflow

1. Set up the Python environment.
2. Obtain the project source code and dataset.
3. Inspect and understand the original preprocessing pipeline.
4. Prepare text and audio data.
5. Test the original models and resolve compatibility issues.
6. Train and evaluate models on a manageable subset of the dataset.
7. Generate audio from input text and assess the results.

Team Workflow

* Colab: Environment setup, experiments, and model testing.
* VS Code: Source-code inspection, debugging, and code development.
* GitHub: Shared code, documentation, and version control.

Both team members should use compatible Python and library versions and document any changes to the original implementation.

Current Status

* GitHub repository created
* Development environments configured
* Required libraries installed
* Source code reviewed
* Dataset prepared
* Initial model tested
* Audio output generated
* Results evaluated

Notes

The original project README states that its source archive contains only part of the required libraries and a limited amount of training data. The original code may therefore require additional files or compatibility fixes before it runs successfully.

This repository will document our setup, implementation, experiments, and findings.
