# December 2019

The files in this directory are related to my presentations given at the
[West Michigan RHUG](https://events.redhat.com/profile/form/index.cfm?PKformID=0x1097260001)
and [Detroit RHUG](https://events.redhat.com/profile/form/index.cfm?PKformID=0x1116640001)
events.

## Slides

[AI_ML-from-data-scientist-to-application-developer.pdf](AI_ML-from-data-scientist-to-application-developer.pdf)

## Videos

[Demo 1, Value at Risk Jupyter Notebook](https://vimeo.com/378428621)

[Demo 2, Value at Risk sandbox service](https://vimeo.com/378429415)

## Manifests

* `spark-cluster.yaml` - A template to deploy Apache Spark clusters needed
by the sandbox service. These clusters have been configured to contain custom
data files and Python packages. **WARNING** This template requires that you
have the [Apache Spark Operator](https://operatorhub.io/operator/radanalytics-spark)
installed.

* `var-notebook.yaml` - A template to deploy value at risk Jupyter notebooks.
These images contain several notebooks that give an introduction to machine
learing, Apache Spark, and value at risk calculations.

* `var-sandbox.yaml` - A template to deply value at risk sandbox services. This
service exposes a route that allows users to calculate their value at risk.
