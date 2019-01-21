Capstone-NYCPoverty
==============================

Analysis and predictive model on the NYC Poverty data set

Items in this README:
- A Note on Cauldron vs Jupyter Notebooks
- Project Organization map

A Note on Cauldron vs Jupyter Notebooks
------------
Although Jupyter notebooks are widely used in data science, they suffer from a
few deficiencies: they're not *just* real code, they maintain constant global
state, they are difficult for Github versioning, and their internal editor
leaves much to be desired.

As a result, for this project I'm working in Cauldron notebooks
(http://unnotebook.com). They address some of the shortcomings of Jupyter
notebooks and are more conducive to a production environment.

What  this mean for you?
- Each notebook directory in /notebooks/ has a .pdf file showing the output of
  the notebook, like a Jupyter notebook without the code. (It's actually easier
    to follow the narrative in this format anyway).
    - The code that creates the notebook is already in the directory, and is real
      Python code with real testing.
      - If you prefer looking at the notebook itself, which includes both code and
        output in one place, Cauldron has a simple reader that requires a quick and
          simple install from http://unnotebook.com/reader-install/. Each /notebooks
            sub-directory has a .cauldron file that you can open.


            Project Organization
            ------------

