# sparkCAD-Plus-Thesis
# SparkCAD
SparkCAD+ (Spark Caching Anomalies Detector Plus): Logical plan visualization and size and transformaton time display of every dataset for Apache Spark applications.

* Current version: 2.0
* Contents:
  1. Overview
  2. Requirements
  3. Organization

---
### OVERVIEW ###

SparkCAD is an interactive decision support tool that visualizes the logical plan of Spark applications and displays dataset's size and transformation time. It parses the execution logs of Spark (thse same ones that Spark's History Server parses without additional metadata). With the help of these data, this thesis work is to propose a better caching strategy at different storage levels.


### Requirements ###
 * [Jupyter](https://jupyter.org/)
 * [Graphviz](https://graphviz.readthedocs.io/en/stable/manual.html)

### Organization ###

Samples of 170 execution logs could be found in "logs" folder.
The default configuration is stored in "config.ini". The user can change it or overwrite the default configuration values during using the notebook.
