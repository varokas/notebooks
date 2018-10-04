# Notebook
Example of using python data tools in jupyter notebook

## Prerequisite
```
brew cask install anaconda

# Add this to .zshrc or .bash_profile
export PATH=/usr/local/anaconda3/bin:"$PATH"

# Then restart the terminal
```

## Running jupyter
```
jupyter lab
```

## Using anaconda
To run gui for anaconda
```
anaconda-navigator
```

## Anaconda Environments and Packages
```
conda create -n notebooks python=3.7

source activate notebooks 
conda install jupyterlab matplotlib numpy pandas scipy scikit-learn
```

