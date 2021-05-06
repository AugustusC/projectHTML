#How to Run

### Requirements:
- Agda (tested on version 2.6.1)
- Agda stdlib (tested on version 1.5)
- Emacs with agda-mode

###Obtaining the Files
The files can be obtained via git: [repo](https://git-teaching.cs.bham.ac.uk/mod-ug-proj-2020/cxa657.git)

###Loading Hamming(7,4)
In Emacs navigate to the src folder within the repository and open the file hamming74.agda. In order to type check and load the file press CTRL+c, CTRL+l. By loading the file all of the proofs have been validated.

###Viewing the Results of Tests

There are some variables in the file hamming74.agda under the title Tests that can show the implementation computing. In order to view the results of these test press CTRL+c, CTRL+n and then type in the name of the variable. For some matrices to be displayed nicely it may be nessaccery to use the function toNaive. After pressing CTRL+c, CTRL+n type toNaive and then the name of the variable.
