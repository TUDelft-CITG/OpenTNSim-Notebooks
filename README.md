# OpenTNSim Notebooks

This is the repository with examples for the [OpenTNSim](https://github.com/TUDelft-CITG/OpenTNSim) package. 

The package documentation can be found [here](opentnsim.readthedocs.io).

## Example notebooks

OpenTNSim allows the user to simulate (nautical) traffic flow over a [NetworkX](https://networkx.github.io/documentation/stable/) graph. A number of examples are presented in the [notebooks folder](https://github.com/TUDelft-CITG/OpenTNSim-Notebooks/tree/master/notebooks). You can run them locally or as an [Azure notebook](https://notebooks.azure.com/joris-denuijl/projects/OpenTNSim).

Check the information on how to get started either way.

### Using the notebooks locally

If you wish to use the notebooks on your local drive, use the following code to get started.

``` bash
# Download the package
git clone https://github.com/TUDelft-CITG/OpenTNSim-Notebooks

# Go to the correct folder
cd OpenTNSim-Notebooks

# Install package
pip install -r requirements.txt

# Go to the notebooks foldeer
cd notebooks

# Start jupyter notebooks
jupyter notebook
```

### Using Azure Notebooks

If you wish to run the notebooks using Microsoft Azure, use the following set-up to get started.

1. Create a Microsoft [account](https://docs.microsoft.com/nl-nl/azure/notebooks/quickstart-sign-in-azure-notebooks).
2. Go to the following [Azure Notebooks website](https://notebooks.azure.com/joris-denuijl/projects/OpenTNSim).
3. Clone the project, see [information](https://docs.microsoft.com/nl-nl/azure/notebooks/create-clone-jupyter-notebooks#clone-a-project) on cloning by Microsoft.
4. Start the notebook server.
5. Wait a short while before you run any of the notebooks, the environment takes some time to initialize with the additional packages (such as OpenTNSim and SimPy).
