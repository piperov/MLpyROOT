# MLpyROOT
An example of setting up a complex ML + pyROOT environment with conda and CMSSW

## How to try it
Start a Jupyter Hub session (e.g. on [Hammer](https://notebook.hammer.rcac.purdue.edu/)) and open a New -> Terminal
Then clone this repo: 
```
git clone https://github.com/piperov/MLpyROOT
```
Then end the terminal session by typing "exit", close the tab, and return to your directory tab.  There should be a new directory present called `MLpyROOT`, where you will find the notebooks for building the environment, and for running the example.

If running this for a first time, you'll need to 
  1. Build the conda environment containing all desired ML libraries
      * run the `build_conda_environment.ipynb` notebook.
  2. Build a new Jupyter kernel with that conda environment and a current CMSSW version
      * run `build_MLpyROOT_kernel.ipynb`
  

When you have the environment and kernel setup you can try the example

  3. Load the example notebook `example.ipynb`
  4. Load the new kernel `Kernel -> Change Kernel -> MLpyROOT`
  5. Try the example by clicking through the individual cells in order, or run them all `Cell -> Run All`
