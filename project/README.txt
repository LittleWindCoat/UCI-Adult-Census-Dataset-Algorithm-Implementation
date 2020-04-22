{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf400
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 Menlo-Regular;\f2\fnil\fcharset134 .PingFangSC-Regular;
\f3\fnil\fcharset0 .SFNSText;}
{\colortbl;\red255\green255\blue255;\red27\green31\blue34;\red10\green77\blue204;\red0\green0\blue0;
\red244\green246\blue249;}
{\*\expandedcolortbl;;\cssrgb\c14118\c16078\c18039;\cssrgb\c1176\c40000\c83922;\csgray\c0;
\cssrgb\c96471\c97255\c98039;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl600\sa320\partightenfactor0

\f0\b\fs48 \cf2 \expnd0\expndtw0\kerning0
Project 1 Apriori Algorithm and FP-growth Algorithm implementation\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\b0\fs32 \cf2 This is the the mini project for CSC240 Data Mining. This project uses python to implement two frequent itemset mining algorithms introduced in the chapter: (1) Apriori and (2) FP-growth algorithm. This project uses the UCI Adult Census Dataset. The program chose minimum support of 30%
\b\fs36 \cf3 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 Files\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardeftab720\pardirnatural\partightenfactor0

\f1\b0\fs27\fsmilli13600 \cf4 \cb5 \kerning1\expnd0\expndtw0 \CocoaLigature0 adult.data.txt   adult.test.txt	apriori.py   fp_growth.py\cf2 \expnd0\expndtw0\kerning0
\CocoaLigature1 \
\pard\pardeftab720\sl380\partightenfactor0

\f0\b\fs36 \cf2 \cb1 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 Running the program\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\b0\fs32 \cf2 To run the program on Mac OS X, Open the a terminal window and get to a command line. Type cd to change directory to the project folder and type python filename 
\f2 (apriori.py and fp_growth.py)
\f0  to run the program. T
\f2 he origin program would give the result frequent itemset for adult.data. If you want to know the result for adult.test, you need to change the readFile from adult.data.txt to adult.test.txt..
\f0\b\fs30 \

\b0\fs32 For example, you can download the zip file to desktop and unzip it. Then use the following command line:\
\pard\pardeftab720\sl380\partightenfactor0

\f1\fs27\fsmilli13600 \cf2 \cb5 cd desktop\
cd project\
\pard\pardeftab720\sl300\partightenfactor0

\f0\b\fs30 \cf3 \cb1 \
\pard\pardeftab720\sl360\sa320\partightenfactor0

\f3 \cf2 Run the Apriori
\f0\b0\fs32 \
\pard\pardeftab720\sl380\partightenfactor0

\f1\fs27\fsmilli13600 \cf2 \cb5 python apriori.py\
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf3 \cb1 \
\pard\pardeftab720\sl360\sa320\partightenfactor0

\fs30 \cf2 Run the Fp-growth
\b0\fs32 \
\pard\pardeftab720\sl380\partightenfactor0

\f1\fs27\fsmilli13600 \cf2 \cb5 python fp_growth.py\
}