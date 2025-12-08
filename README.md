Exceptional Model Mining on Model Residuals: Balancing Interpretability and Expressiveness in Rich Description Languages

This repo contains the paper's code.
Look in the "Pipeline" folder for the code.

To reproduce the results, we need to do the following, after having a Python environment set up:

```
python3 1_dataset_setup.py

python3 2_dataset_shape.py

python3 run_and_compare.py
```

The commands will set up the data, run the EMM algorithm, and finally create the results. Once it's done running, you can run the code below to generate plots.

```
python3 3_create_plots.py
```
