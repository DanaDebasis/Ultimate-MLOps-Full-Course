# Build & Track ML Pipelines with DVC

## How to run?
export PATH=/c/ProgramData/anaconda3/Scripts/:$PATH


conda create -n deb-dvc-test python=3.13 -y
conda init bash

conda activate deb-dvc-test

python -m pip install -r requirements.txt


## DVC Commands

git init

dvc init

dvc repro

dvc dag

dvc metrics show