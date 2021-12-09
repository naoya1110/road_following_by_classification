# JetBot Road Following by Classification

This is the instruction for **Road Following by Classification** exmaple in NCKU-NITKC AI Robotics Lab. 

## Setup
1. Log in to your JetBot from a web browser.
1. Open a terminal. Your current working directory must be `workspace` now. 
1. Then navigate to `workspace/jetbot/notebooks` directory.
    ```
    $ cd jetbot/notebook
    ```
1. Clone this repo.
    ```
    $ git clone https://github.com/naoya1110/road_following_by_classification.git
    ```

## Data Collection
1. Navigate to `workspace/jetbot/notebooks/road_following_by_classification` directory in the file browser.
1. Open `data_collection.ipynb`
1. Perform data collection by following instructions in the notebook.
1. Download `dataset.zip` to your local PC.

## Model Training
1. Download `train_model.ipynb` from `workspace/jetbot/notebooks/road_following_by_classification` directory to your local PC.
1. Upload `train_model.ipynb` to your Google Drive and open it with Google Colab.
1. Open [train_model.ipynb in Google Colab](https://colab.research.google.com/github/naoya1110/road_following_by_classification/blob/main/train_model.ipynb)
1. Upload `dataset.zip` by using the file browser in Google Colab.
1. Train a model with Google Colab by following instructions in the notebook.
1. Download `best_model.pth` to your local PC

## Live Demo
1. Upload `best_model.pth` to `workspace/jetbot/notebooks/road_following_by_classification` directory in your JetBot
1. Run your JetBot with the trained model by following the instructions in the notebook.