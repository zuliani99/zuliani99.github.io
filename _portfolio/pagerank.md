---
title: "PageRank HITS InDegree Comparison"
excerpt: "The aim of this project is to compare the prestige computation of a sequence of web graphs using an implementation of PageRank, HITS and InDegree."
collection: portfolio
---

The aim of this project is to compare the prestige computation of a sequence of web graphs using an implementation of PageRank, HITS and InDegree.

## Startup
In order to run the benchmark you have to run these command in your console:
```
sudo apt update
sudo apt install build-essential
sudo apt-get install libboost-all-dev
```

After that, to compile the project, you have to jump into the */app/src* folder and type the following line in your console:

```
g++ -std=c++2a -o ../bin/app Main.cpp
```

For compiler optimization instead type:
```
g++ -std=c++2a -O3 -o ../bin/app Main.cpp
```

The *.exe* file will be inserted into the */app/bin* directory.

## Dataset
The used datasets are from the Web Graph section of the [Stanford Large Network Dataset Collection](https://snap.stanford.edu). For each dataset download the compressed file, extract *.txt* file and place it in the */app/dataset* folder. 

## Usage
After typed *./app* in the */app/bin* directory thw following message will be displayed:
```
Do you want to activate VERBOSE mode to see the top_k nodes for each k and algorithms? (0/1)
```
In case you want to see the *top-k* nodes for all *top-k* values and for all algorithms insert 1, otherwise 0. After having pressed enter with the respective choice the application execution will start.


## Example of Console Output with Verbose mode OFF
```
------------------------------------- PageRank - HITS - InDegree Comparison ------------------------------------

Do you want to activate VERBOSE mode to see the top-k nodes for each k and algorithms? (0/1) 0

-------------------web-NotreDame.txt---------------------
IN_DEGREE
Elapsed: 33.5669 ms

PAGE_RANK
Elapsed: 7611.09 ms      Steps: 93

HITS
Elapsed: 15693.9 ms      Steps: 136

-------------------web-NotreDame.txt---------------------

-------------------web-Stanford.txt---------------------
IN_DEGREE
Elapsed: 110.795 ms

PAGE_RANK
Elapsed: 25534.8 ms      Steps: 100

HITS
Elapsed: 8752.34 ms      Steps: 24

-------------------web-Stanford.txt---------------------

-------------------web-BerkStan.txt---------------------
IN_DEGREE
Elapsed: 114.209 ms

PAGE_RANK
Elapsed: 23478.5 ms      Steps: 100

HITS
Elapsed: 19699.3 ms      Steps: 47

-------------------web-BerkStan.txt---------------------

-------------------web-Google.txt---------------------
IN_DEGREE
Elapsed: 477.935 ms

PAGE_RANK
Elapsed: 81601.8 ms      Steps: 96

HITS
Elapsed: 350898 ms       Steps: 255

-------------------web-Google.txt---------------------
```

## [Github Link](https://github.com/zuliani99/PageRank_HITS_InDegree_Comparison)