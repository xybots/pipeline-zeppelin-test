## Pipeline Zeppelin test notebooks
Apache Zeppelin test notebook to trigger Pipeline

### How to use the tera-gen notebook

In order for the tera-gen Zeppelin notebook to work the following prerequisites need to be satisfied:

* the patched tera gen application needs to be available on the driver pod
* the jar is available in the s3: https://s3.amazonaws.com/lp-deps-test/libs/spark-terasort-1.1-SNAPSHOT.jar
* this needs to be available in the driver pod at: "/tmp/spark-terasort-1.1-SNAPSHOT.jar (otherwise the notebook needs to be corrected)
* the user's aws credentials need to be added to the notebook
* the amount of data to be generated and the location of the generated data needs to be added to the last paragraph

Import the [tera-gen](https://github.com/banzaicloud/zeppelin-notebooks/blob/master/tera-gen-notebook.json) notebook into Zeppelin and run the paragraphs in the order they are listed.


### How to use the open library notebook

Please follow this [lin](https://cambridgespark.com/content/tutorials/interactively-analyse-100GB-of-JSON-data-with-Spark/index.html) in order to use the open libary notebook.
