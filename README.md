# Recommender System Demo (Last.fm dataset)
### Requirements:
- Apache Spark ([installation tutorial](https://www.tutorialspoint.com/apache_spark/apache_spark_installation.htm) or [install with Homebrew](http://brewformulas.org/ApacheSpark) [preferred])
- Python package [PySpark](http://spark.apache.org/docs/2.2.0/api/python/pyspark.html) (`pip install pyspark` or `conda install pyspark` [preferred])
- make sure these local variables are set as following:
```
# make sure to update <text> with your versions
export JAVA_HOME="/Library/Java/JavaVirtualMachines/<yourjavaversion>.jdk/Contents/Home/"
export SPARK_HOME="/usr/local/Cellar/apache-spark/<yoursparkversion>/libexec/"

### this is to Apache Spark with Jupiter Notebook ("pyspark" will execute notebooks instead of shell)
export PYSPARK_DRIVER_PYTHON="jupyter"
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
```

### To run the Jupyter Notebooks:
Within the directory of this repo, run `pyspark` in the Terminal.
