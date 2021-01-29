# Unsupervised Learning Awareness for AI Decision-makers

## AI decision-makers classroom trainings

This repository contains course materials for my Machine Learning class on the topic of Time Series specificities:
- <em>unsupervised_awareness.pdf</em> : course presentation with teaching content
- <em>time_series_usecase.ipynb</em> : Python notebook illustrating the course notions
- <em>time_series_usecase-empty.ipynb</em> : Python notebook illustrating the course notions, empty versions for students


### Option 1: Working with Google Colab

To follow the notebooks with Google Colab, simply go to https://colab.research.google.com/. Import a new notebook from GitHub, search for "jfabrice" and open one of the notebooks of this class (ml-awareness-unsupervised-learning), for example time_series_usecase-empty.ipynb. Then click on "Copy to Drive" to be able to execute it. The first section of the notebook is there to initialize the environment from Google Colab.


### Option 2: Working locally - Setting up Anaconda environment

To setup the Anaconda environment with required dependencies, execute the following instructions in Anaconda prompt or Linux shell.

```shell
# Clone this github repository on your machine
git clone https://github.com/jfabrice/ml-awareness-unsupervised-learning.git

# Change working directory inside the repo
cd ml-awareness-unsupervised-learning

# Create a new virtual environment
conda create -n timeseriesenv python==3.6

# Activate the environment
## For Linux / MAC
source activate timeseriesenv
## For Windows
activate timeseriesenv

# Install the requirements
pip install -r requirements.txt
```
