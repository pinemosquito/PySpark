# Getting started with PySpark

## Python3
Install latest Python version on Mac OS

## Java7+ 
Install latest Java (Spark requires Java 7+)

## Spark
Download Spark binaries

Follow steps 1, 2 and 3 to download .tgz file

Extract archive and placed in ~/Applications

```
tar -xzf spark-2.1.1-bin-hadoop2.7.tgz
```

~/Applications/spark-2.1.0-bin-hadoop2.7/bin/pyspark

## Environment
Set environment variable by adding following lines to ~/.bash_profile:

```
export SPARK_HOME="/Users/user/Applications/spark"
export PYSPARK_SUBMIT_ARGS="--master local[2]"
# Make pyspark available anywhere
export PATH="$SPARK_HOME/bin:$PATH"
```


