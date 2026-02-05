# Exceptional Model Residual Mining, and Three Richer EMM Description Languages

  

##### This branch contains the frozen code for the [IDA 2026 conference]([https://ida2026.liacs.nl/](https://ida2026.liacs.nl/ "https://ida2026.liacs.nl/") ).

  

This repo contains the code the the paper "Exceptional Model Residual Mining, and Three Richer EMM Description Languages". The frozen code submitted to the IDA 2026 conference can be found in the branch: "IDA_2026_Submission".

To replicate the results in the paper the following steps need to be followed:

1.  Load a python environment
2.  Run the code inside the pipeline folder by following the instructions below
3.  The results will be saved locally.

### Replication Steps:

```
python3 1_dataset_setup.pypython3 2_dataset_shape.pypython3 run_and_compare.py
```

The commands will set up the data, run the EMM algorithm, and finally create the results. Once it's done running, you can run the code below to generate plots.

```
python3 3_create_plots.py
```