# Quantum Paradoxes
A collection of Jupyter notebooks exploring various quantum mechanical paradoxes and phenomena. Many examples have accompanying blog posts and/or YouTube videos. Notebooks are relatively self contained, and include all of the information needed to get started. This assumes you have only a basic understanding of python and quantum.  

## Notebook Examples
- [Double Slit Experiment](./double-slit.ipynb)
- [EPR Paradox](./EPR-paradox.ipynb)
- [Many Worlds Interpretation](./many-worlds.ipynb)
- [Maxwell's Demon](./quantum-maxwells-demon.ipynb)
- [Minesweeper](./quantum-minesweeper-code.ipynb)
- [Pigeonhole Paradox](./Pigeonhole_paradox-notebook.ipynb)
- [Quantum Eraser](./quantum-eraser.ipynb)
- [Quantum Lie Detector for Hardy's Paradox](./A%20quantum%20lie%20detector%20for%20Hardy's%20paradox.ipynb)
- [Schrödinger's Cat](./schrodingers-cat.ipynb)
- [Teleportation](./teleportation.ipynb)
- [Time Loops in Quantum Mechanics](./time-loops.ipynb)
- [Wigner's Friend Paradox](./wigners-friend.ipynb)
- [Extended Wigner's Friend Paradox](./wigner-friend-friend-friend.ipynb)
- [Zeno Effect](./quantum-zeno-effect.ipynb)

## Getting Started
These examples can be run with a fairly straightforward python implementation. Simply clone this repository and setup your dependencies.  

You can do this manually by reviewing the necessary packages in [environment.yml](./environment.yml), or this environment can be setup with conda (e.g., [miniconda](https://docs.anaconda.com/miniconda/miniconda-install/)):  
```conda env create -f environment.yml
conda activate quantum-paradoxes```  

Once the dependencies have been installed you will be able to open any notebook of interest and run the cells to explore the quantum paradox implementations.  e.g., `jupyter notebook schrodingers-cat.ipynb`  

NOTICE: Not all notebooks have been tested, so it is possible that additional dependencies or depdency versions could be required. If this happens:  
- You will receive an error something like `MissingOptionalLibraryError: "The 'pylatexenc' library is required to use 'MatplotlibDrawer'. You can install it with 'pip install pylatexenc'."`
- Resolution is probably `pip install <missing-dependency>` (e.g., `pylatexenc` in the above example)
- Restart your Jupyter kernel to pickup the latest dependency changes	
- For any updated package or package version, add the item to the list of dependencies (pip or otherwise) in [environment.yml](./environment.yml) and update the file in the repo. Once all dependencies have been identified, this NOTICE can be removed.  

## Author
- **Maria Violaris**
  - [LinkedIn](https://www.linkedin.com/in/maria-violaris)
  - [Maria's YouTube Series on Quantum Foundations](https://www.youtube.com/playlist?list=PLlzqzbe3LGN8_fiJ9Pg_cFAkP3SJRgp8D)
