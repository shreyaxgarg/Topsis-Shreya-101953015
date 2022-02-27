# Topsis-Shreya-101953015
This is a python package for rank calculation using topsis.
TOPSIS
This package helps in finding the TOPSIS score and rank. TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.

How to use this package?
Step 1: Install the package using :- pip install Topsis-ShreyaS-101917127

Step 2: Import the package :- tp =import("Topsis-ShreyaS-101917127"))

Step 3: In Command Prompt :- tp.topsis('101917127-data.csv',"1,1,1,1,1","+,-,+,-,+","101917127-result.csv")

The result gets stored in 101917127-result.csv

Subject to constraints
(1) Impacts and weights must be separated by â€˜,â€™ (comma).

(2) Impacts must be either +ve or -ve.

(3) Command prompt should include 4 paramters namely - input dataframe, weights, impacts and name of the output csv file.
