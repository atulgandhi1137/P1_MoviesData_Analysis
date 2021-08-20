# P1_MoviesData_Analysis
## Project Description
This project aims to analyse movies data by using Apache Hive .

## Technologies Used
Apache Hive - version 2.1.1

## Getting Started
1. Clone the project
```
$ git clone https://github.com/atulgandhi1137/P1_MoviesData_Analysis.git
```

## Prerequisite
A Hadoop ecosystem
- Apache Hadoop should be installed with all the components.

## Usage
1. After logging into VM, clone the project onto local machine and unzip all the csv files.
2. Then, copy csv files from local to hdfs.
```
$ hdfs dfs -put ./filename /<hdfs path>
```
3. You can use hive using either hive shell or hive view. (Type hive to start hive shell)
4. Upload the data from all the csv files to the respective tables from Hive View->Upload Table
5. Then, start executing queries.
