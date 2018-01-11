# Getting started with PySpark

## Install Anaconda

## Java7+ 
Spark requires Java7+ which you can download from Oracle's website

## Download Spark
Go to Spark download page
Follow steps 1, 2 and 3 to download .tgz file
Unzip folder and move to home directory

## Scala build tool
brew install sbt

go to directory you unzip spark

sbt assembly

## Environment
Specify location of Spark and special arguments in Environment
Use nano or vim to open ~/.bash_profile and add the following lines at the end:

export SPARK_HOME="$HOME/spark-1.5.1"
export PYSPARK_SUBMIT_ARGS="--master local[2]"
Replace "$HOME/spark-1.5.1" with the location of the folder you unzipped Spark to (and also make sure the version numbers match!).
