# AI-Algorithms-in-Trading
This repository contains all projects belonging to part 2 of Udacity's "AI for Trading Nanodegree".

## Installation, Dependencies and Starting the Notebook
The code of these projects was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository
2. `git clone https://github.com/rp-dippold/AI-Algorithms-in-Trading.git`

### Setting up Python environments
#### Environment for Projects 5, 7 and 8
The Python environment created by the following steps works for projects 5, 7 and 8.

Enter the following commands in a bash terminal:
1. `cd AI-Algorithms-in-Trading`
2. `conda create --name aitrading_p7 python=3.6.3 -c conda-forge`
3. `conda activate aitrading_p7`
4. `python -m pip install --upgrade pip` 
5. `python -m pip install --upgrade wheel setuptools build`
6. `python -m pip install -r requirements_p7.txt`
7. `python -m ipykernel install --user --name aitrading_p7 --display-name "ai-trading-p7"`

#### Environment for Project 6
1. `cd AI-Algorithms-in-Trading`
2. `conda create --name aitradinggpu python=3.6.3 -c conda-forge`
3. `conda activate aitradinggpu`
4. `python -m pip install --upgrade pip`
5. `python -m pip install --upgrade wheel setuptools build`
6. `python -m pip install -r requirements2.txt`
9. Install Pytorch:
    * [CPU]: `pip install torch==0.4.0 torchvision==0.2.1`
    * [GPU]: `pip install torch==1.10.1+cu111 torchvision==0.11.2+cu111 torchaudio==0.10.1 -f https://download.pytorch.org/whl/cu111/torch_stable.html`.\
    Depending on your GPU and cudnn version a different pytorch version my be required. Please refer to 
    https://pytorch.org/get-started/locally/.
10. `python -m ipykernel install --user --name aitradinggpu --display-name "ai-trading-gpu"`

### Start a Jupyter Notebook
1. Activate the appropriate environment by `conda activate <aialogtrading/aitradinggpu>`
2. Navigate to a project's folder, e.g. by `cd p5_...`
3. Start the notebook by entering `jupyter-notebook` into the bash terminal.
4. Copy one of the displayed URLs, e.g. 'http://127.0.0.1:8888/?token=78c...' in a browser tab.
5. Select the corresponding notebook, e.g. `project_5_starter.ipynb` in your browser.
6. Select the appropriate kernel "ai-algo-trading" or "<tbd>" from the menu "Kernel" before running the cells.
