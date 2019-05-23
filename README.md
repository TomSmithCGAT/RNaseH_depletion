# Scalable and cost-effective ribonuclease-based rRNA depletion for bacterial transcriptomics

Jupyter Notebook:

* **0.design_probe.ipynb**: design probe libraries for target 16S and 23S rRNA sequence

* **1.calculate_probe_identity.ipynb**: calculate probe identity to various different 16S and 23S sequences to evaluate the ability of pools to be applied to different sequences

## Dependencies

* Python 2.7, jupyter 4.3.0 
	- panda
	- numpy
	- _NB: Above libraries are bundled together in the [Anaconda distribution](https://www.continuum.io/downloads)_

* Required for probe identitiy calculation only: [Muscle (MUltiple Sequence Comparison by Log-Expectation)](https://www.drive5.com/muscle/)
	- Executable file of Muscle that compatible with your OS should be put to ./bin or other place specified in 1.calculate_probe_identity.ipynb
