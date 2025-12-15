
# Big title

##### Set up Conda environment

Create new environment from file:
- `conda env create -f environment.yml`

Update conda environment with add new packages (add to environment.yml first, then run `conda activate data`):
- `conda env update --file environment.yml  --prune`

Check with packages are installed:
- `conda activate data && conda list`