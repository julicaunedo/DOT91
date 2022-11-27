# DOT91

To run this code, make sure to copy data repository (whose structure is defined later in this file) using command
```
cp -rf ~/data .
```

Now create a conda enviornment, giving the name of your choise and install the liraries defined in requirements.txt file using comand
```
pip install -r requirements.txt
```
If facing any issue with the particular version of the libraries, please try to remove the library version detail and simply install the default library version avaialbale at present point in time.

Once all the libraries are installed, please run the following command
```
python3 pipeline_take2.py
```

If all libraries are installed properly, then code will take around 5-6 hours to run and will generate 3 files as a response, namely:-
```
DOT91_term_matches_full_take2_oldcw.csv
DOT91_term_matches_full_take2_updatedcw.csv
DOT91_term_matches_full_take2_updatedcw_incw.csv
```

### Declaration
This repository is made on request from Prof Julieta Caunedo to open source the code for the replication of results from DOT91 project.
The code is not actually written by me, but I just tried to replicate the code files to work on dataset provided and generate some csv files in response. 
