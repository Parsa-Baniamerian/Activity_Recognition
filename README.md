# Human_Activity_Recognition

This repository contains two deep learning models—ConvLSTM and LRCN (Long-term Recurrent Convolutional Networks)—to recognize human activities from video sequences using the UCF50 dataset. The project includes data preprocessing, model creation, training, and evaluation.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models](#models)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview
This project utilizes the UCF50 dataset, a well-known collection of labeled videos for human activity recognition. The dataset includes 50 different classes of activities, and this implementation focuses on a subset of these classes. Using convolutional and recurrent layers, the models learn to recognize activities from sequences of video frames.

## Dataset
The project uses the UCF50 dataset, which contains videos of 50 different activity classes. Each video is processed to extract frames, which are then normalized and resized.

## Models
This repository includes implementations of two deep learning architectures:

- **ConvLSTM**: Combines convolutional layers with LSTM units to capture spatial and temporal features from video frames.
- **LRCN (Long-term Recurrent Convolutional Networks)**: Uses CNN layers for spatial feature extraction followed by LSTM layers to capture temporal relationships across frames.

Each model can be trained and evaluated independently within the notebook, allowing comparison of their performance.


## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/activity-recognition.git
   cd activity-recognition

2. **Install the required packages: Install the dependencies using**:
   ```bash
   pip install -r requirements.txt

3. **Download and extract the dataset**:  
   The UCF50 dataset will be downloaded automatically within the notebook, but ensure that you have enough storage and extraction tools (e.g., `unrar`).

4. **Run the Jupyter Notebook**:  
   Open `Activity_Recognition.ipynb` in Jupyter Notebook to execute the code cells for data loading, preprocessing, model training, and evaluation. You can select between the ConvLSTM and LRCN models.


   






