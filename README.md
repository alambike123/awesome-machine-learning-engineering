# awesome-machine-learning-engineering
A curated list of articles, papers and tools for managing the building and deploying of machine learning models, aka machine learning engineering.

- [Where to start](#where-to-start)
- [Data](#data)
- [Best practice](#best-practice)
- [Example pipelines](#example-pipelines)
- [Conference tracks and workshops](#conference-tracks-and-workshops)
- [Big data on a single machine / on the command line](#big-data-on-a-single-machine--on-the-command-line)
- [Software](#software)
    - [Managing building and deploying models](#managing-building-and-deploying-models)
    - [Managing building models](#managing-building-models)
    - [Deploying models](#deploying-models)
    - [Serialising and transpiling models](#serialising-and-transpiling-models)
    - [Monitoring models](#monitoring-models)
    - [AWS](#aws)
    - [Google Cloud](#google-cloud)
    - [Azure](#azure)
- [Related awesome lists](#related-awesome-lists)

## Where to start

* [A Few Useful Things to Know about Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)
* [Machine Learning glossary](https://developers.google.com/machine-learning/crash-course/glossary)

## Data

* [The Unreasonable Effectiveness of Data](https://ai.google/research/pubs/pub35179)
* [Revisiting the Unreasonable Effectiveness of Data](https://ai.googleblog.com/2017/07/revisiting-unreasonable-effectiveness.html)
* [Why you need to improve your training data, and how to do it](https://petewarden.com/2018/05/28/why-you-need-to-improve-your-training-data-and-how-to-do-it/)

## Best practice

* [Rules of Machine Learning: Best Practices for ML Engineering](https://developers.google.com/machine-learning/rules-of-ml/)
* [What’s your ML test score? A rubric for ML production systems](https://ai.google/research/pubs/pub45742)
* [Machine Learning: The High Interest Credit Card of Technical Debt](https://ai.google/research/pubs/pub43146)
* [Introducing the Facebook Field Guide to Machine Learning video series](https://research.fb.com/the-facebook-field-guide-to-machine-learning-video-series/)
* [Patterns for Research in Machine Learning](http://arkitus.com/patterns-for-research-in-machine-learning/)
* [Production Data Science](https://github.com/Satalia/production-data-science)
* [Making Netflix Machine Learning Algorithms Reliable](https://www.slideshare.net/justinbasilico/making-netflix-machine-learning-algorithms-reliable)
* [Scaling Knowledge at Airbnb](https://medium.com/airbnb-engineering/scaling-knowledge-at-airbnb-875d73eff091)

## Example pipelines

* [Ad Click Prediction: a View from the Trenches](https://ai.google/research/pubs/pub41159)
* [Learning a Personalized Homepage](https://medium.com/netflix-techblog/learning-a-personalized-homepage-aa8ec670359a)
* [Distributed Time Travel for Feature Generation](https://medium.com/netflix-techblog/distributed-time-travel-for-feature-generation-389cccdd3907)

## Conference tracks and workshops

* [Reliable Machine Learning in the Wild NIPS 2016 workshop](https://sites.google.com/site/wildml2016nips/)
* [Reliable Machine Learning in the Wild ICML 2017 workshop](https://sites.google.com/site/wildml2017icml/)
* [KDD 2017 Applied Data Science](http://www.kdd.org/kdd2017/applied-data-science-invited-talks)
* [KDD 2018 Applied Data Science](http://www.kdd.org/kdd2018/applied-data-science-invited-talks)
* [ECMLPKDD 2016 Industrial track](http://www.ecmlpkdd2016.org/program.html#accepted-industrial)
* [ECMLPKDD 2017 Applied Data Science track](http://ecmlpkdd2017.ijs.si/program.html#AppDSTab)
* [ECMLPKDD 2018](http://www.ecmlpkdd2018.org/accepted-papers-by-track-2/#tab-id-3)
* [WWW 2018 Industry track](https://www2018.thewebconf.org/program/industry-track/)

## Big data on a single machine / on the command line

* [Command-line Tools can be 235x Faster than your Hadoop Cluster](https://adamdrake.com/command-line-tools-can-be-235x-faster-than-your-hadoop-cluster.html)
* [Big Data, Small Machine](https://adamdrake.com/big-data-small-machine.html)
* [Dask](https://github.com/dask/dask)
* [Unix for poets](https://web.stanford.edu/class/cs124/kwc-unix-for-poets.pdf)
* [Data Science at the Command Line](https://www.datascienceatthecommandline.com)
* [Data hacks](https://github.com/bitly/data_hacks) command line utilities
* [Split command](https://linux.die.net/man/1/split)
* [Parallel command](https://linux.die.net/man/1/parallel)
* [Xargs command parallel flag](https://www.gnu.org/software/findutils/manual/html_node/find_html/Controlling-Parallelism.html)

## Software

### Managing building and deploying models

* [kubeflow](https://github.com/kubeflow/kubeflow) Machine Learning Toolkit for Kubernetes (kubeflow)
* [ModelDB](https://github.com/mitdbg/modeldb) A system to manage machine learning models (MIT)
* [mlflow](https://github.com/databricks/mlflow) Open source platform for the complete machine learning lifecycle (Databricks)
* [datmo](https://github.com/datmo/datmo) Open source model tracking tool for data scientists

### Managing building models

* [Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. (Spotify)
* [Airflow](https://github.com/apache/incubator-airflow) is a platform to programmatically author, schedule, and monitor workflows (Netflix)
* [Azkaban](https://github.com/azkaban/azkaban) workflow manager (LinkedIn)
* [Pinball](https://github.com/pinterest/pinball) is a scalable workflow manager (pinterest)

### Deploying models

* [Serving](https://github.com/tensorflow/serving) A flexible, high-performance serving system for machine learning models (Google)
* [deepdetect](https://github.com/jolibrain/deepdetect) Deep Learning API and Server in C++11 with Python bindings and support for Caffe, Tensorflow, XGBoost and TSNE (deepdetect)
* [clipper](https://github.com/ucbrise/clipper) A low-latency prediction-serving system (Berkeley)
* [MLeap](https://github.com/combust/mleap) Deploy Spark Pipelines to Production (combust.ml)
* [openscoring](https://github.com/openscoring/openscoring) REST web service for the true real-time scoring (<1 ms) of R, Scikit-Learn and Apache Spark models (openscoring)
* [mxnet-model-server](https://github.com/awslabs/mxnet-model-server) Model Server for Apache MXNet is a tool for serving neural net models for inference (AWS)
* [hydro-serving](https://github.com/Hydrospheredata/hydro-serving) ML FaaS - Machine Learning Serving cluster (hydrosphere.io)

### Serialising and transpiling models

* [Predictive Model Markup Language](https://en.wikipedia.org/wiki/Predictive_Model_Markup_Language) (PMML)
* [jpmml-sklearn](https://github.com/jpmml/jpmml-sklearn) Java library and command-line application for converting Scikit-Learn pipelines to PMML
* [sklearn2pmml](https://github.com/jpmml/sklearn2pmml) Python library for converting Scikit-Learn pipelines to PMML
* [sklearn-porter](https://github.com/nok/sklearn-porter) Transpile trained scikit-learn estimators to C, Java, JavaScript and others

### Monitoring models

* [Knowledge Repo](https://github.com/airbnb/knowledge-repo) A next-generation curated knowledge sharing platform for data scientists and other technical professions.

### AWS

* [Data Pipeline](https://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/what-is-datapipeline.html) "is a web service that you can use to automate the movement and transformation of data"
* [Glue](https://docs.aws.amazon.com/glue/latest/dg/what-is-glue.html) "is a fully managed ETL (extract, transform, and load) service"
* [Simple Workflow](https://docs.aws.amazon.com/amazonswf/latest/developerguide/swf-welcome.html) "makes it easy to build applications that coordinate work across distributed components"
* [Batch](https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html) "enables you to run batch computing workloads on the AWS Cloud"
* [Machine Learning](https://docs.aws.amazon.com/machine-learning/latest/dg/what-is-amazon-machine-learning.html) "cloud-based service that makes it easy for developers of all skill levels to use machine learning technology"
* [Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html) "is a fully managed machine learning service"

### Google Cloud

* [Dataflow](https://cloud.google.com/dataflow/docs/) "is a unified programming model and a managed service for developing and executing a wide variety of data processing patterns"
* [ML Engine](https://cloud.google.com/ml-engine/docs/) "brings the power and flexibility of TensorFlow, scikit-learn and XGBoost to the cloud"

### Azure

* [Batch AI](https://docs.microsoft.com/en-us/azure/batch-ai/) "helps you experiment with your AI models using any framework and then train them at scale across GPU and CPU clusters"
* [Machine Learning services](https://docs.microsoft.com/en-us/azure/machine-learning/service/) "enable building, deploying, and managing machine learning and AI models using any Python tools and libraries"
* [Machine Learning Studio](https://docs.microsoft.com/en-us/azure/machine-learning/studio/) "is a collaborative, drag-and-drop tool you can use to build, test, and deploy predictive analytics solutions on your data"

## Related awesome lists

* [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
* [awesome-etl](https://github.com/pawl/awesome-etl)
* [awesome-pipeline](https://github.com/pditommaso/awesome-pipeline)
