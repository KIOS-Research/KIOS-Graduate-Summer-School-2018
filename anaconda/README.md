## Anaconda

After you start the anaconda navigator, do the following...

### Create a new Anaconda environment
Create a new conda environment (and activate it by clicking on the play button)
![Add package in anaconda](anaconda-environment.png)

### Add a new package
From within the new environment you have created...
![Add package in anaconda](anaconda-guide.png)

**Important note:** CVXPy is likely to not show up on the list on some systems. In that case, you need to [add it using conda](https://www.cvxpy.org/install/index.html).

Open a terminal and activate your environment:

On Windows:
```
activate <nameOfYourEnvironment>
```

On Linux/Unix:
```
source activate <nameOfYourEnvironment>
```


and then run (these are the same commands on all OSs):

```
conda install -c conda-forge lapack
conda install -c cvxgrp cvxpy
```


### Start Jupyter
Start Jupyter (you might need to install it first). This will fire up a browser window.
![Add package in anaconda](anaconda-notebook.png)

