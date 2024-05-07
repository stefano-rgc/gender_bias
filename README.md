Order in which the folders must be executed:

1. cleaning
2. ner
3. training_dataset
4. inference_dataset
5. training
6. inference
7. plots

Within each folder, there is only one Jupyter notebook. You should only focus on the notebook and ignore other files (e.g., CSV and pickle ones). Those other files will be called within the notebooks in due time.

You can create a virtual environment with most of the needed packages to run the notebooks by using the yml file in this folder. To create such an enviroment, use the command below

```conda env create -f s2sd_environment.yml```

that will create a Conda environment named s2ds that can then be activated using the command below

```conda activate s2ds```

You still may need to install a few Python packages yourself as you execute the notebooks.
