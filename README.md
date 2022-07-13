# AlgoFnO

This is a PyPI Library code which helps automate Bhav Copy Analysis.


# Setup virtual environment<br/>

  <br>
  
  Starting by creating a virtual environment in conda by the name vnv
  ```
  conda create --name vnv
  ```
  
  Switching to the above created virtual environment
  ```
  source activate vnv
  ```
  
  Installing jupyter notebook to work on it
  ```
  conda install jupyter
  ```
  
  Installing the AlgoFnO library from PyPI to work on it and backtest option strategies.
  ```
  pip install AlgoFnO
  ```
  
  # Running a backtesting strategy example:<br>
  
  Opening up jupyter notebook
  
  ```
  jupyter-notebook
  ```
  The code : 
  ```
  from AlgoFnO import *
  list = [‘RELIANCE’,’TCS’,’INFY’]
  object = BhavCopyAnalysis() 
  object.doAnalysis(“/Users/<username>/Desktop/AlgoFnO Sample Data”,list)
  ```
  
  The output will be stored in the original folder location itself and the code requires two arguments, one is the location of the folder where the CM and F&O Bhav Copies are stored and the second argument is the list of stocks for which analysis is to be done.
  

  
