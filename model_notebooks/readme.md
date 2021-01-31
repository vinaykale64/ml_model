Step 1: 

- Download data from kaggle : https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
- Get the `train.csv` file. Save it in the data/ folder

Step 2:

- Create a conda environment with python 3.7 (for ex. if `myenv` is the environment name)
``` bash
conda create -n myenv python=3.6 -y
```

- Activate the environment
``` bash
source activate myenv
```

- pip install the libraries from `requirments.txt` file
``` bash
pip install -r requirements.txt
```
- Using ipykernel, add a jupyter notebook kernel based on the conda environment using following command:

``` bash

python -m ipykernel install --user --name myenv --display-name "Python (myenv)"
```

Step 3:

- Run the notebooks in sequence.
