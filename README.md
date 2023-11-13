# AI-Algorithms-in-Trading
This repository contains all projects belonging to part 2 of Udacity's "AI for Trading Nanodegree".

## Installation, Dependencies and Starting the Notebook
The code of these projects was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository
2. `git clone https://github.com/rp-dippold/AI-Algorithms-in-Trading.git`

### Setting up the Python environment
#### Environment for Projects 5, 7 and 8
The Python environment created by the following steps works for projects 5, 7 and 8.

Enter the following commands in a bash terminal:
1. `cd AI-Algorithms-in-Trading`
2. `conda create --name aialgotrading python=3.6.3 -c conda-forge`
3. `conda activate aialgotrading`
4. `python -m pip install --upgrade pip` 
5. `python -m pip install --upgrade wheel setuptools build`
6. `python -m pip install -r requirements.txt`
7. `python -m ipykernel install --user --name aialgotrading --display-name "ai-algo-trading"`

#### Environment for Project 6
1. ...
9. Install Pytorch:
    * [CPU]: `pip install torch torchvision torchaudio`
    * [GPU]: `pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117`.\
    Depending on your GPU and cudnn version a different pytorch version my be required. Please refer to 
    https://pytorch.org/get-started/locally/.

### Start a Jupyter Notebook
1. Navigate to a project's folder, e.g. by `cd p4_...`
2. Start the notebook by entering `jupyter-notebook` into the bash terminal.
3. Copy one of the displayed URLs, e.g. 'http://127.0.0.1:8888/?token=78c...' in a browser tab.
4. Select the corresponding notebook, e.g. `project_4_starter.ipynb` in your browser.
5. Select the kernel "ai-algo-trading" before running the cells.
