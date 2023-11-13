# AI-Algorithms-in-Trading
This repository contains all projects belonging to part 2 of Udacity's "AI for Trading Nanodegree".

## Installation, Dependencies and Starting the Notebook
The code of these projects was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository
2. `git clone https://github.com/rp-dippold/AI-Algorithms-in-Trading.git`

### Setting up the Python environment
The Python environment created by the following steps works for every project.

Enter the following commands in a bash terminal:
1. `cd Quantitative-Trading`
2. `conda create --name aialgotrading python=3.6.3 -c conda-forge`
3. `conda activate aialogtrading`
4. `python -m pip install --upgrade pip` 
5. `python -m pip install --upgrade wheel setuptools build`
6. `python -m pip install -r requirements.txt`
7. `python -m ipykernel install --user --name aialogtrading --display-name "ai-alog-trading"`
