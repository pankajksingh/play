# Talk for IITK 97

## Setup
We rely on Jupyter for running the notebook.
This requires conda environment with all the right python dependencies.
Such an environment can be created by running following command. The yml file contains list of dependencies that we need.
> conda env create -f iitk-conda.yml

Then we enter the environment by running following command
> conda activate iitk

We can configure Jupyter to recognize this environment by running the following command
> python -m ipykernel install --user --name=iitk

Run Jupyter 
> jupyter lab

## Talk Outline
* Function : Definition
* Neural Network : Function Approximator
* Example : Learning to Add