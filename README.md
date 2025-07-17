## Overview
The CV Plot helper is a workflow tool that can visiulise Biologic's .mpr file without reimporting it into their software. It can also extract the metadata out of the .mps files that Biologic privieds. In Addition a small peak finder tool is implemented with more evaluation methots to be added in the future.


## Key feature
- plot automation for .mps data
- basic peak finding
- extraction of metadata drom .mps files


## Dependencies
- galvani==0.5.0
- ipywidgets==8.1.7
- jupyterlab_widgets==3.0.15
- matplotlib==3.10.0
- numpy 
- pandas 
- path
- scipy==1.16.0
- seaborn==0.13.2


## Roadmap (still to come/planned)
- better usability --> changable parameters in the measurement can be changed more easy like in the peak finder section with the use of sliders, drop down menus, etc.
- better cycle split
- better peak fitting that can detect shoulder peaks better and more reliable
- graphical interface for an even better use
