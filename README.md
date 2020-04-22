# UCI Adult Census Dataset Algorithm Implementation 
 Apriori Algorithm and FP-growth Algorithm implementation

This is the the mini project for CSC240 Data Mining. This project uses python to implement two frequent itemset mining algorithms introduced in the chapter: (1) Apriori and (2) FP-growth algorithm. This project uses the UCI Adult Census Dataset. The program chose minimum support of 30%
Files
adult.data.txt   adult.test.txt	apriori.py   fp_growth.py

Running the program
To run the program on Mac OS X, Open the a terminal window and get to a command line. Type cd to change directory to the project folder and type python filename (apriori.py and fp_growth.py) to run the program. The origin program would give the result frequent itemset for adult.data. If you want to know the result for adult.test, you need to change the readFile from adult.data.txt to adult.test.txt..
For example, you can download the zip file to desktop and unzip it. Then use the following command line:
cd desktop
cd project

Run the Apriori
python apriori.py

Run the Fp-growth
python fp_growth.py
