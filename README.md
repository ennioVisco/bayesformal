# Set of programs specific for the bayesformal project

# Requirements
To run the full set of scripts, the following languages are needed in the running environment:
 - JDK 21+
 - python 3.8+ with jupyter notebooks

# Replication Setup 

## Prepare the datasets
- Download the datasets from: [https://doi.org/10.7910/DVN/6FEFUU](https://doi.org/10.7910/DVN/6FEFUU).
- Unzip the file `data-1.zip` and place the content of the `data-1` folder in the `src/main/resources` folder.

## Launch the experiments
To launch the experiments on the data, just run
```sh
./gradlew run
```

## Analyze the data & generate the plots
To analyze the data and generate the plots, just open in jupyter `analyzer.ipynb`, e.g. by:
```sh
jupyter notebook analyzer.ipynb
```
And run the cells in the notebook.

# Extras
Previous version of the project available at [https://github.com/ennioVisco/bayesformal-archive](https://github.com/ennioVisco/bayesformal-archive).