## Exercise with the Movielens Dataset


#### Installation

To install the required dependencies, we recommend you to install Anaconda and run the following line:
```
conda create --name recommender_tut python=3.9
```
This will create a conda environment which you can activate by running
```
conda activate recommender_tut
```

###### Install the packages

```
conda install numpy
conda install pandas
conda install seaborn
conda install -c conda-forge collections-extended
conda install -c conda-forge scikit-surprise
conda install -c anaconda scikit-learn
conda install -c conda-forge jupyterlab
conda install -c conda-forge matplotlib
```

###### Using an already installed python / jupyter distribution

If you already use Python, please make sure the following packages are installed:
```
numpy
pandas
scikit-learn
jupyterlab (or jupyter notebook)
seaborn
matplotlib
collections
surprise

```
This can be done by simply running
```
pip install package_name
```

#### Running the files

Once you activate your environment, you can run on the terminal
```
jupyter notebook (or jupyter lab).
```
This will open an screen in which you can see the `DataMining_Practical_Recommender.ipynb` file. This is the main file we will use in the workshop. 
