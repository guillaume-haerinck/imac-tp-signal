# IMAC TP Signal

Classes about signal processing (Fourier transform, _etc_) in engineering school IMAC in France.

## Getting started

You need to use Jupyter Notebooks, the easiest way to do so is to install the Python distribution [Anaconda](https://www.anaconda.com/) and run Jupyter Labs from the launcher.

## Considerations

Notebooks are wonderfull tools, but they also comes with some caveats that we are trying to handle in this project.

### Proper presentation

Duplicate the file `template.ipynb` to create a new notebook. It is a way to stay consistent and have well organized and documented codebase.

### Out-Of-Order execution

The order in which the cells has been executed (with `shift + enter`) will influence the code output (it can be in any order, which is very dangerous). You __must__ run each cells once, from top to bottom, each time before committing your changes to be certain that it is properly working (it is built-in, just click on `Run/Restart Kernel and Run All...`).

The number to the left of each cell shows in which order the cell has been executed. For exemple `IN [1]` shows that it has been the first cell executed.

Consider using [Nodebook](https://github.com/stitchfix/nodebook) extension to ensure top-to-bottom order of execution.

### Code lint

Consider using VSCode to edit heavy pythons scripts. With it, you get powerfull code completion, debugging and error detections

### Dependencies

Consider using a `requirements.txt` file.

## Tips

### Shortcuts

- Use `shift + tab` to open help
- Use `tab` to get autocompletion once the cell has been executed

### Commands

- Type `?` at the end of a command to print the docstring
- Type `from ... import ...` to import a function from an external file

### Magics

- Type `%run` to run a python script in an external file
- Type `%history` to know in which order the cells has been executed

## Inspirations

- [Notable Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks#introductory-tutorials) - Good notebooks exemples
- [I don't like notebooks by Joel Grus](https://docs.google.com/presentation/d/1n2RlMdmv1p25Xy5thJUhkKGvjtV-dkAIsUXP-AL4ffI/edit#slide=id.g3cbe089527_0_89) - A great critique about notebooks caveats
- [VSCode](https://code.visualstudio.com/docs/python/jupyter-support) - The official tutorial to work with VSCode with notebooks
- [Interaction](https://blog.dominodatalab.com/interactive-dashboards-in-jupyter/) - Build UI interfaces in notebooks
- [Matplot](https://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) - Matplot getting started guide