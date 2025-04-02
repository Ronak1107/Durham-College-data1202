# INTRODUCTION OF PREPROCESSING DATA FOR PYTHON (PANDAS)

We will use Python's powerful pandas package to find a clean and pre-data set for the dataset in this session. As the experiment gets to a finish, we will understand the fundamental processes and procedures for handling and preparing the data.

## Getting Started
1. Checking of dataset framework
2. more detailed statistics information
3. Easily giving name of categories and columns of data
4. find missing or wrong use of datatype
5. get utilization and filtering methods

## Prerequisites

1. Install Python (Download Anaconda)
2. Jupiter Notebook (Launch it for running and creating python file)
3. create github account and create repository so I can add my explanation in Readmi.md file

## Install
there are few libraries which is using in python.
1. Pandas (this library is useful to analize and manupulating data) and,
2. Numpy (helpfull for running numerical value) and,
3. Matplotlib & Seaborn (this libraries use for data visualization)

here is example of panda library because I used panda as pd 

To install libraries pip install pandas numpy

### loading dataset

df = pd.read_csv("auto.csv")

df.head() (this shows first 5 records of dataset)
then 

df.shape (find the records)

(201, 26) : output by (raw and column)

## Running the test

df.shape (Shows the record) : (201, 26) output while checking data

df. size (Shows elements) : (5226)

df.column (showing name of columns)

df.dtypes (showing datatype of column)

Error handling example
df.phd.dtype (here we don't have phd column that is attribute error)


### fixing data

#Convert data types to proper format with updating datatype

df[["bore", "stroke"]] = df[["bore", "stroke"]].astype("float")

df[["normalized-losses"]] = df[["normalized-losses"]].astype("int")

df[["price"]] = df[["price"]].astype("float")

df[["peak-rpm"]] = df[["peak-rpm"]].astype("float")

then

df.dtype (shows updated column datatype which we did in fixing data)

like bore and store now have float datatype

This test is to update datatype of particular column ny using a python and its libraries so we get perfect data type of each and every column.

## Deployment

to deploy this in live run it as a python script in jupyter notebook with having file of auto.csv so we get data from this file and run all the data in one file with proper required libraries like pandas numpy and many more.

## Built with
1. Python (Language)
2. pandas (library used to run data)
3. github (for report and submission)

## Author

Ronak Kotadiya : inclass lab 1 data from data 1202(Data analysis tools analytics) [Ronak](https://github.com/Ronak1107)

## contributing

Lab1.ipnynb

## Acknowledgement

1. Durham College
2. Professor Al-Trad Omar

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://gist.github.com/PurpleBooth/LICENSE.md) file for details

## References:
1. template provided under this project
2. [github.com](https://github.com/)




















