[Running Jupyter Server]

jupyter lab --ip=0.0.0.0 --no-browser --NotebookApp.token=''

[Conda Environment Cloning Alternative]

conda env export > environment.yml
conda env create -f environment.yml -n IndoWaveSentiment
conda activate IndoWaveSentiment
pip install -r requirements.txt