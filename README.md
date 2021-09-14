# MoviesData_Analysis
## Project Description
This project aims to analyse movies data by using Apache Hive .

## Technologies Used
- Hortonworks Data Paltform - version 2.6.5 (Minimum 12 gb RAM required)
- Hadoop - version 3.2.2
- Apache Hive - version 2.1.1

## Features
List of features :
- This project analyzes the movies data to get the 
  - movies of specific genre. 
  - movies which got most ratings.
  - top rated movies.
  - low rated movies. etc

To-do list :
- Partitioning on tables
- More queries to be added

## Getting Started
1. Clone the project.
```
$ git clone https://github.com/atulgandhi1137/P1_MoviesData_Analysis.git
```
2. Install Oracle Virtual Box [here](https://www.virtualbox.org/wiki/Downloads).
3. Download Hortonworks virtual box ova file [here](https://www.cloudera.com/downloads/hdp.html).
4. Import the ova file in virtual box.

## Usage
1. Start the Virtual Machine, clone the project onto local machine and unzip all the csv files.
```
$ unzip file.zip
```
2. Then, copy csv files from local to hdfs.
```
$ hdfs dfs -put ./filename /<hdfs path>
```
3. You can use hive using either hive shell or hive view. (Type hive to start hive shell)
4. Create a database.
```
$ create database movielens;
```
5. Upload the data from all the csv files to the respective tables from Hive View->Upload Table.
6. Then, start executing queries.
