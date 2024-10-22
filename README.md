[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

Below are the images of the experiments:

## Simple:
**Time per epoch: 0.075s **- 451 epochs - HIDDEN_SIZE = 3
![Image](images/SIMPLE/graph.png)
![Graph](images/SIMPLE/graph2.png)

## Diag
**Time per epoch: 0.104s** - 800 epochs - HIDDEN_SIZE = 5
![Image](images/DIAG/graph.png)
![Graph](images/DIAG/graph2.png)
![Graph](images/DIAG/graph3.png)
![Graph](images/DIAG/graph4.png)


## Split
**Time per epoch: 0.177s** - 900 epochs - HIDDEN_SIZE = 10
![Image](images/SPLIT/graph.png)
![Graph](images/SPLIT/graph2.png)
![Graph](images/SPLIT/graph3.png)

## XOR
**Time per epoch: 0.179s** - 1100 epochs - HIDDEN_SIZE = 10
![Image](images/XOR/graph.png)
![Graph](images/XOR/graph2.png)