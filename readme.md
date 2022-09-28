when setting up venv please please use:

    Windows:
        python -m venv .venv

    Mac:
        python3 -m venv .venv

this way we ensure we're not including the venv in github

To install packages from requirements.txt in your venv simply use:

    pip install -r requirements.txt

This project uses this dataset to function https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
In order to make the project work, download the dataset and place it into the project data folder so that the structure looks like this: 
    /aai-mandatory-1/data/healthcare-dataset-stroke-data.csv