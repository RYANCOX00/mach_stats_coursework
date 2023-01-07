# Machine Learning & Statistics


<br>

The contents of this repository is for course work submittion for the Machine Learning and Statistics module in Atlantic Technological Univerity. 



<br>

***

<br>

## Project Description

<br>

The project is broken into 2 distinct sections. 

<br>

1. The first section contains a submission of regular exerises which were assigned throughout the semester.  The 4 workbooks in the weekly assignment folder contain the following notebooks.

    - statistics.ipynb
        - This notebook contains 3 questions. The first two relates to the lady tasting tea test.  Questions 1 is a manual calculation. Questions 2 uses scipy.stats' fisher_exact function to simulate the lady tasting tea problem. Questions 3 discusses how the scipy.stats.ttest_ind [documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html) code works.

        <br>

    - models.ipynb
        - This notenook contains two excerises relating to the absolute value function.

        <br>

    - parameters.ipynb
        - This notebook uses numpy's polyfit to fit polynomials to two datasets.

        <br>
    


2. The second section of the project will provide a recreation of the Keras time series anomaly detection demonstration. This original Kera demonstration is available [here](https://keras.io/examples/timeseries/timeseries_anomaly_detection/).  The notebook created in this repository provides detailed explainations on all the concepts with enhancements to the original code. 

 

<br>

Occasionally, Github does not render Jupyter Notebooks correctly.  You can view a static version of the re-created Keras Notebook on nbviewer by clicking this icon.

[![nbviewer]( )

<br>

***

<br>

## Steps to install

<br>

1. It is recommended that Windows users download Cmder to interact with the command line. Cmder can be downloaded [here](https://cmder.net/).   Mac and Linux user may continue to use the built in command line. 

2. To run this code a user will require Python 3 (available [here](https://www.python.org/downloads/) and the packages listed in the requirements.txt file.   It is however recommended that a user downloads Anaconda as these particular packages including Python 3 are already pre-installed.  You can download Anaconda [here](https://www.anaconda.com/products/individual).  

3. TensorFlow 2 is not provided in Anaconda.  Users will require TensorFlow 2 which is available [here](https://www.tensorflow.org/install).

4. Users will be required to download Git in order to pull contents from the repository into a local directory. Git is available [here](https://git-scm.com/downloads). 

5.  It is recommended to user Google Chrome to interact with Jupyter. 

<br>

***

<br>

## Run
1. To pull the code to a local directory a user will first need to clone this repository using the SSH. Go to your desired directory in the command line and type 

```
git clone git@github.com:RYANCOX00/mach_stats_coursework.git
```

<br>

2. To open the directory in Jupyter type jupyter lab in the current directory on the command line. 

```
jupyter lab
```

<br>

3. The browser should open automatically, however if it does not open go to Google Chrome or Firefox and type the below in the url bar.

```
http://localhost:8888/lab/workspaces/auto-d
```

<br>

4. To run the aml_accounts.ipynb notebook: 
- Open the file in Jupyter.
- Go to *Kernel*. 
- Click *Restart Kernel and Run All Cells*. 

<br>

***

<br>

## Contact
Should any person wish to contact me in relation to the content of this workbook, they can contact me on my [GMIT email address](mailto:G00398251@atu.ie).


<br>

***

<br>

## Troubleshoot
Should a user experience an error when running the code in these workbooks they should ensure they have the latest version of the packages listed in the requirements.txt file.  

To update a package a user should go to the command line on their terminal and type "*pip install --upgrade [name of package]*". For example, for the matplotlib package a user would type the following into the command line:

```
pip install --upgrade matplotlib

```


<br>

***

