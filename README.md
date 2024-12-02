<img src="https://mediknothealth.web.app/imgs/vertispine-icon.png" width="100px"/>
# vertispine Jupyter notebook
This is a simulated application illustrating the use of a 3 target machine learning classification algorithm in the orthopaedics outpatient clinical setting, submitted to the BOA x Stryker AI in Orthopaedics Hackathon 2024.
<br/>
Please see full details here: [vertispine infodeck](https://vertispine.vercel.app/vertispine.pdf)
<br/>
A web-app simulation can be seen at: [https://vertispine.vercel.app/](https://vertispine.vercel.app/)

## Prerequisites
Python must be installed. The code automatically downloads all the necessary libraries from the `requirements.txt` file.

## Project structure
The project has a `./data/` folder containing two files `column_2C_weka.arff` and `column_3C_weka.arff` from [UC Irvine's Machine Learning Repository](https://archive.ics.uci.edu/dataset/212/vertebral+column).
`vertispine2C.ipynb` is the Jupyter notebook for two target classification and `vertispine3C.ipynb` is the Jupyter notebook for three target classification.

## Instructions
1. Clone the repository with either HTTPS:
`git clone https://github.com/jdrmota/vertispine-jupyter.git`
or SSH
`git@github.com:jdrmota/vertispine-jupyter.git`

2. Run it with Anaconda Navigator or in the command line with `jupyter nbconvert --to script --execute --stdout vertispine2C.ipynb | python` for the 2 target algorithm or `jupyter nbconvert --to script --execute --stdout vertispine3C.ipynb | python` for the 3 target algorithm.