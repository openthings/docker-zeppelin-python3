# docker-zeppelin-python3

## A docker image for Apache Zeppelin with pyspark configured to use Python3.
## With pre-installed datascience python3 packages.

### Description

This docker image contains:
- Apache Zeppelin and Spark (%pyspark is fully configured to use only Python3)
- Python3 and Pip3
- Some Python3 packages: numpy, pandas, scipy, scikit-learn, pydataset...

For more informations about Apache Zeppelin project: https://zeppelin.incubator.apache.org/

### Installation

First, get the image:

```
docker pull gmousse/docker-zeppelin-python3
```

Then, launch the container:

```
docker run -it -p 8080:8080 -p 8081:8081 gmousse/docker-zeppelin-python3
```

You can access to zeppelin on **localhost:8080** in your web browser.
