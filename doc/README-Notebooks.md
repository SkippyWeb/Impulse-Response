# Python Notebooks



**Development and run environment**

Python Notebooks in the Processing directory are developed and executed within the Anaconda environment on a Windows 10 (or higher) computer.   



**Anaconda**

The Python Notebooks were developed within the Anaconda environment. Anaconda is a distribution of the Python and R programming languages for scientific computing (data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to simplify package management and deployment.  https://www.anaconda.com/

See also

* Anaconda-Starter-Guide.pdf
* Conda-cheatsheet.pdf



**Starting a Notebook**

* Start the Anaconda Prompt (anaconda3) :

  \> cd [directory containing the notebook]

  \> activate [environment]   (if any) 
  
  \> jupyter lab [notebook.ipynb]
  
  
  
* alternatively:  

  \> jupyter notebook [notebook.ipynb] 

  Note that JupyterLab is the next generation of the Jupyter Notebook

  

* In case of message: Notebook is not trusted: 

  \>jupyter trust notebookName.ipynb

  



**Update Anaconda**

\> conda update --prefix C:\Users\[username]\anaconda3 anaconda

or

\> conda update -all



**List of available environments**

\> conda env list  (shows the active environment)

\> conda list (shows pacakges in active environment)



**Prepare new jupyter lab environment**

In case that the Jupyter notebooks do not execute, the following might solve the problem. 

 \>jupyter --version

\>conda install jupyter

\>conda install jupyterlab

 

**Check versions and environment**

\> conda -V  (check Anaconda Version)

\> python -V (check Python Version)



 **PyCharm and DataSpell**

To complement anaconda one may also use the PyCharm Python IDE from JetBrains (https://www.jetbrains.com/pycharm/). The free version of PyCharm does not run Notebooks, for one needs either PyCharm Pro or DataSpell (https://www.jetbrains.com/dataspell/)





