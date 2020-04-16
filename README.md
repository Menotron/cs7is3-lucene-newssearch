# cs7is3-assignment-2

#####Project developed under the coursework of  CS7IS3 - Information Retrieval and Web Search


######Following is an implementation of the Apache Lucene Library (v7.5.0), written in Java.

The Dataset contains files from:

* The Financial Times Limited (1991, 1992, 1993, 1994)
* The Federal Register (1994)
* The Foreign Broadcast Information Service (1996)
* The Los Angeles Times (1989, 1990).

###Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software

```
Ubuntu OS
Maven 3.3.9
OpenJDK 1.8.0_242
GCC 5.4.0
```


### Building, Compiling, Creating the Index, Querying the Index and Using Trec-eval to compare scores.

* Clone this repository to your designated directory.
* Using a terminal - cd the cloned directory.

run following scripts from project root

* Run the following command, this will compile, index files and generate trec_eval results and same will be displayed on the terminal
```
sh run.sh
```

* Running following command will generate trec_results for the latest run
```
sh run_trec_eval.sh
```


You should be able to view the score on terminal

####References
Document Parsing Implementation and Query Parsing: https://github.com/CS7IS3-A-Y-201718-IR2/text-search-engine-ir2


