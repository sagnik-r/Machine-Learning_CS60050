The submission has the files:
7_asgn2_Qn1_2.ipynb
7_asgn2_Qn3.ipynb
ML Report_2

The first file has the solution for parts 1 and 2
The second file has solution for part 3

Keep the dataset in the same folder before running the codes

The files have been kept separately as the dataset is huge with >300000 entries
Running it on local machine was taking a lot of time. So they were separated so as to ensure
that the 2 can be parallely computed.

To run the ipynb file,
1) Open the jupyter notebbok environment in the system on a compatoble web browser. The supported web browsers are Chrome, Firefox and Safari
2) Ensure that the Data Set is present in the same directory as the one in which the notebook is saved and its name is "PercentageIncreaseCOVIDWorldwide.csv"
3) Click on Kernel and choose Restart and Run All Cells.
4) When prompted for an input for maximum height, enter 6 to ensure that the results in report are replicated
5) Any integer value can also be entered but then there will be variations in the observation and the results in the report
6) After all the cells have been executed, the final tree should be visible.

If jupyter notebook is not installed in your system, follow the steps below to install it:

USING conda

We recommend installing the classic Jupyter Notebook using the conda package manager. Either the miniconda or the miniforge conda distributions include a minimal conda installation.
Then you can install the notebook with:

conda install -c conda-forge notebook

USING pip
If you use pip, you can install it with:

pip install notebook

To run the notebook, run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):

jupyter notebook

For more details on installing and using jupyter notebook, please refer to: https://jupyter.org/install
