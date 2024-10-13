### Installation
run `conda env create -f environment.yaml`
If this fails for some reason, manually create the venv and install the packages via:
```
    conda create -n aligner -c conda-forge montreal-forced-aligner python=3.10
    conda install -c conda-forge montreal-forced-aligner
    pip install speechbrain, num2words, praat-textgrids
```