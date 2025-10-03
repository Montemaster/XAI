# On the Antagonism of Explainability and Privacy: a Comparative Study of Attacks and Explainers
This repository contains the code and data for the experiments of our XAI & data privacy research.

📁 Repository Structure

data/
This folder contains all preprocessed and prepared datasets used in our experiments. The data is ready to use and requires no additional preprocessing steps.


notebooks/
Each Jupyter notebook in this folder corresponds to a specific experiment conducted in the study.
Every notebook includes:

A description of the experiment
Instructions on how to run it
Code to reproduce the results

🧪 Reproducing the Experiments
To reproduce the experiments:

Navigate to the notebooks/ directory.
Open the notebook corresponding to the experiment of interest.
Follow the instructions provided in the notebook to run the code.

# Experiments
## Init Notebooks using Docker
Run command `docker build -t xaidataprivacy .` in the directory with the Dockerfile.

Then you can run the image mounted to your working directory with the following command: `docker run -p 8888:8888 -v WORKING_DIRECTORY:/home/jovyan/work xaidataprivacy` or `docker run -p 8888:8888 -v "$(pwd):/home/jovyan/work" xaidataprivacy`