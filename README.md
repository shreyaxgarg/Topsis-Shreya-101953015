# Topsis-Shreya-101953015
This is a python package for rank calculation using topsis.


TOPSIS Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) originated in the 1980s as a multi-criteria decision making method. TOPSIS chooses the altenrative of shortest Euclidean distance from the idael solution, and fartherst distance from the negative-ideal solution. More details at wikipedia. The TOPSIS algorithm is succintly explained in this paper comparing TOPSIS and VIKOR methods

Using TOPSIS-

Step 1: Install the package using :- pip install Topsis-ShreyaS-101917127

Step 2: Import the package :- tp =import("Topsis-ShreyaS-101917127"))

Step 3: In Command Prompt :- tp.topsis('101917127-data.csv',"1,1,1,1,1","+,-,+,-,+","101953015-result.csv")

The result gets stored in 101953015-result.csv


Subject to constraints
(1) Impacts and weights must be separated by commas.

(2) Impacts must be either +ve or -ve.

(3) Command prompt should include 4 paramters namely - input csv file, weights, impacts and name of the output csv file.
