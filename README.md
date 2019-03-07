# Web-scraping-with-Beautiful-soup-an-example-on-cryptocurrency-data
<p align="justify">In this code, we harvest the historical data of cryptocurrency coins using Python and the Beautiful Soup library. Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.</p>

## Getting Started

<p align="justify">These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.</p>

### Prerequisites

<p align="justify">You need Python 3.x to run the following code.  You can have multiple Python versions (2.x and 3.x) installed on the same system without problems. Python needs to be first installed then SciPy, Beautiful Soup or the Jupyter Notebook in whichever order, as they require Python to be installed.</p>

In Ubuntu, Mint and Debian you can install Python 3 like this:

    sudo apt-get install python3 python3-pip

Alongside Python, the SciPy packages are also required. In Ubuntu and Debian, the SciPy ecosystem can be installed by:

    sudo apt-get install python-numpy python-scipy python-matplotlib ipython ipython-notebook python-pandas python-sympy python-nose

The Beautiful Soup package is required for data parsing,and it can be installed for Python 3 by:
    
    sudo apt-get install python3-bs4 
    
Finally, the Jupyter Notebook which can be installed through Python's package manager:

    pip3 install --upgrade pip
    pip3 install jupyter
    
For other Linux flavors, OS X and Windows, packages are available at:

http://www.python.org/getit/  
https://www.scipy.org/install.html  
https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup
https://jupyter.readthedocs.io/en/latest/install.html


## File descriptions
<ul>
<li><div align="justify">'<em>Get_coin_data.ipynb</em>' which is the Jupyter Notebook of the project, where all the explanations and steps are explained throughout the notebook.</div></li>
<li>'<em>Get_coin_data.html</em>' which contains the html source code of the html conversion of the Jupyter Notebook.</li>
    <li>The directory '<em>Pictures_notebook</em>' that contains all the pictures used to write the current notebook.</li>
</ul>

### Running the files

<p align="justify">The notebook 'Get_coin_data.ipynb' can be directly opened on GitHub, but only the Python code will be visible, as most of its content is written in HTML format. To open the notebook, it is better to run the Jupyter Notebook. This can be done by executing the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):</p>

    jupyter notebook

<p align="justify">This will print some information about the notebook server in your terminal, including the URL of the web application (by default, http://localhost:8888):</p>

    $ jupyter notebook
    [I 11:47:00.830 NotebookApp] Serving notebooks from local directory: C:\Users\EC-PM-3
    [I 11:47:00.830 NotebookApp] The Jupyter Notebook is running at:
    [I 11:47:00.830 NotebookApp] http://localhost:8888/?token=d22181d47f4826316a37161bb8c8469d77a5851bf9ab2c1f
    [I 11:47:00.830 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

It will then open your default web browser to this URL.

<p align="justify">When the notebook opens in your browser, you will see the Notebook Dashboard, which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. The notebook can then be chosen by navigating in the Notebook Dashboard.</p>

<p align="justify">For more information on how to run a specific jupyter notebook, you can go to the <a href="https://jupyter.readthedocs.io/en/latest/running.html#running">following link</a>.</p>

<p align="justify">Another way to access the notebook is to look into its html version. To visualize the html page, we can use the https://htmlpreview.github.io/ webpage which allows to see html pages from GitHub.</p>

<p align="justify">The <a href="https://htmlpreview.github.io/?https://github.com/DavidCico/Web-scraping-with-Beautiful-Soup-an-example-on-cryptocurrency-data/blob/master/Get_coin_data.html">HMTL preview of the notebook</a> can then be directly accessed.</p>

## Contributing

Please read [CONTRIBUTING.md](https://github.com/DavidCico/Web-scraping-with-Beautiful-Soup-an-example-on-cryptocurrency-data/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **David Cicoria** - *Initial work* - [DavidCico](https://github.com/DavidCico)

See also the list of [contributors](https://github.com/DavidCico/Web-scraping-with-Beautiful-Soup-an-example-on-cryptocurrency-data/graphs/contributors) who participated in this project.

