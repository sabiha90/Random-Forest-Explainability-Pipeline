# Random-Forest-Explainability-Pipeline
## Name
#### Applying Improved Random Forest Explainability (RFEX 2.0) on synthetic data
## Contents
1. [Description](#desc-anchor)
2. [Installation](#install-anchor)
3. [Usage](#usage-anchor)
4. [Authors](#author-anchor)
5. [License](#license-anchor)
<h4 id="desc-anchor"> 1. Description </h4>
<p align="justify">
This toolkit serves to execute RFEX 2.0 “pipeline” e.g. a set of steps to produce information which comprises RFEX 2.0 summary namely information to enhance explainability of Random Forest classifier. It comes with the synthetically generated test database which helps to demonstrate how RFEX 2.0 works. Wth this toolkit users can also use their own data to generate RFEX 2.0 summary.

Background of the RFEX 2.0 method, as well as the description and access to the synthetic test database convenient to test and demonstrate can be found in TR 18.01 at cs.sfsu.edu site:

· S. Barlaskar and D. Perkovic “Applying Improved Random Forest Explainability (RFEX 2.0) steps on synthetic data for variable features having a unimodal distribution” which can be found in the [link](http://cs.sfsu.edu/sites/default/files/technical-reports/Applying%20RF%20Explainability%20on%20%20%20%20%20%20%20synthetic_data-variable_values_for_features-11_27Sabiha%20%20FINAL%2002-18-19%281%29.pdf)

Users are strongly advised to read the above report before using this toolkit.

Users of this toolkit are supposed to be familiar with Random Forest method and R toolkit, as well as Jupyther toolkit .

RFEX 2.0 toolkit is run in a set of RFEX 2.0 steps, as described below. Its output is a set of tabular-formatted data called RFEX 2.0 summary providing the information to help understand how RF performed its classification on given training data. RFEX 2.0 attempts to help explain how RF makes its decision on a set of data e.g. training data, thus it is a model based explainer.

In this tool we consider binary classification only, meaning there are only two classes, + (class of interest) and -.
</p>
<h4 id="install-anchor"> 2. Installation </h4>
<p align="justify">

To install Jupyter Notebook, Python installation is a prerequisite. But it is feasible to install Jupyter via Anaconda because it installs Python, Jupyter notebook together, as well as it is easier to install libraries instead of using `pip install`.
For installation direction, please follow the instructions in this [link](https://jupyter.readthedocs.io/en/latest/install.html).
After installing Anaconda, please install "rpy2" in the environment. This is required for using R and Python together in Jupyter notebook

For loading R and Python together, please execute the following line of code    
```
%load_ext rpy2.ipython
```
</p>
<h4 id="usage-anchor"> 3. Usage </h4>
<p align="justify">

To use this toolkit, download the data [here](https://drive.google.com/file/d/1KKZ6iK_0aBAesGZgwYnORHLPtGtfNXLM/view).
Start anaconda navigator and load the notebook provided in the repository. Install the packages "r-randomforest" and "r-ggplot2"
</p>
<h4 id="author-anchor"> 4. Authors </h4>
<p align="justify">

* Sabiha Hussain Barlaskar
* Dr. Dragutin Petkovic

Dept of Computer Science, San Francisco State University

<h4 id="license-anchor"> 5. License </h4>
<p align="justify">

This toolkit is provided for free use and modification. Those who publish the paper are required to cite this toolkit and the publication below

D. Petkovic, R. Altman, M. Wong, A. Vigil: “Improving the explainability of Random Forest classifier – user centered approach”, Pacific Symposium on Biocomputing PSB 2018, Hawaii

