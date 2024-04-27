# ECoG Finger Movement Prediction

## Project Overview
This project involves developing a machine learning model to predict finger movements from electrocorticography (ECoG) data collected from epilepsy patients. The data includes ECoG signals recorded from patients at Harborview Hospital in Seattle, Washington, as they performed finger movement tasks. The goal is to utilize signal processing and machine learning techniques to accurately predict the movements of individual fingers.

## Data Description
The dataset consists of ECoG signals recorded from three subjects, each having implanted subdural electrode grids. Signals were acquired, band-pass filtered, and sampled at 1kHz. The dataset splits into training data (first 2/3 of the experiment) and test data (last 1/3), with corresponding finger flexion data recorded via a data glove.

## Installation

### Prerequisites
- Python 3.0+
- pip

### Libraries
Install the necessary Python libraries using pip:

```bash
pip install numpy scipy matplotlib scikit-learn tensorflow keras keras-tuner
