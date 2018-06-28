# Exercise Session 1 - Learning DS from Demonstrations

In this exercise we will use a GUI simulation to test approaches for learning stable non-linear Dynamical Systems (DS) from demonstrations using SEDS [1] and LPV-DS [2,3] approaches developed in LASA-EPFL.

### Installation Instructions
See installation instructions in package [README](https://github.com/nbfigueroa/learning-ds-tutorial/blob/master/README.md), otherwise you can download all missing dependencies recursively as,
```
git submodule update --init --recursive
```
### Running the GUI
Type  ``` gui_learningDS.m``` in the command line or run the script. This will brings up a GUI (as shown below), including:
- Learn a SEDS model on self-drawn data with a GUI..
- Learn an LPV-DS model on self-drawn data with a GUI with different GMM fitting options and DS parameters optimization variants. 
- Option to simulate controlling a robot with the learned DS.

*A guided video explaining how to use the GUI, can be found in this [link](https://www.youtube.com/watch?v=5fQO9Oluih0)*
[![](https://github.com/nbfigueroa/learning-ds-tutorial/blob/master/img/GUI_2.png)](https://www.youtube.com/watch?v=5fQO9Oluih0)

**References**     
[1] Khansari Zadeh, S. M. and Billard, A. (2011) Learning Stable Non-Linear Dynamical Systems with Gaussian Mixture Models. IEEE Transaction on Robotics, vol. 27, num 5, p. 943-957.    
[2] Mirrazavi Salehian, S. S. (2018) Compliant control of Uni/ Multi- robotic arms with dynamical systems. PhD Thesis.  
[3] Figueroa, N and Billard, A. ".." [Under Review]

**Contact**: [Nadia Figueroa](http://lasa.epfl.ch/people/member.php?SCIPER=238387) (nadia.figueroafernandez AT epfl dot ch)
