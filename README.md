# Classifying Chest X-ray with Spark Deep Learning

## 1. Introduction

## 5. Project Infrastructure
To apply image classification and object detection on large scale of images, several libraries have been introduced to integrate deep learning frameworks such as Cognitive Toolkit (CNTK), TensorFlow, BigDL for purpose into Apache Spark. Among these Deep Learning Pipeline has become one popular choice.

Deep Learning Pipelines provides easy-to-use high-level APIs for scalable deep learning in Python with Apache Spark. It is an open source library created by Databricks, and supporting ensorFlow and TensorFlow-backed Keras workflows. In particular, it can be used with pre-trained models as well as transfer learning.


https://databricks.com/blog/2017/06/06/databricks-vision-simplify-large-scale-deep-learning.html?preview=true

https://github.com/databricks/spark-deep-learning

### Local installation
Software required:
* Spark 2.3,
* Python 3.6
* pyspark
* TensorFlow
* [Deep-Learning-Pipeline][Spark Deep Learning] from Databricks

`$SPARK_HOME/bin/spark-shell --packages databricks:spark-deep-learning:1.2.0-spark2.3-s_2.11`

### Cloud Computing with Databricks Runtime
Databricks runtime features XGBoost, scikit-learn, and numpy as well as popular Deep Learning frameworks such as TensorFlow, Keras, Horovod, and their dependencies.

* Databricks on AWS
* Azure Databricks


Applying Pre-trained Models for Scalable Prediction

Transfer Learning

Local
Cloud with Azue/AWS



Using TensorFlow model

[Spark Deep Learning]

## References



[Spark Deep Learning]: (https://github.com/databricks/spark-deep-learning)

https://databricks.com/blog/2017/06/06/databricks-vision-simplify-large-scale-deep-learning.html

[Making Image Classification Simple With Spark Deep Learning](https://medium.com/linagora-engineering/making-image-classification-simple-with-spark-deep-learning-f654a8b876b8)

[Deep Learning With Apache Spark](https://towardsdatascience.com/deep-learning-with-apache-spark-part-1-6d397c16abd)

[Image Data Support in Apache Spark](https://blogs.technet.microsoft.com/machinelearning/2018/03/05/image-data-support-in-apache-spark/)

Tutorial

https://towardsdatascience.com/deep-learning-with-apache-spark-part-1-6d397c16abd

https://towardsdatascience.com/deep-learning-with-apache-spark-part-2-2a2938a36d35

http://www.adaltas.com/en/2018/05/29/spark-tensorflow-2-3/

Databricks-Deep-Learning-Pipeline

https://databricks.com/blog/2017/06/06/databricks-vision-simplify-large-scale-deep-learning.html?preview=true

https://databricks.com/training/instructor-led-training/courses/intro-deep-learning-theory-practice-keras-tensorflow

https://databricks.com/blog/2016/01/25/deep-learning-with-apache-spark-and-tensorflow.html

https://databricks.com/blog/2016/01/25/deep-learning-with-apache-spark-and-tensorflow.html

https://docs.databricks.com/applications/deep-learning/spark-integration.html

Microsoft

https://blogs.technet.microsoft.com/machinelearning/2018/03/05/image-data-support-in-apache-spark/

https://github.com/Azure/mmlspark

https://github.com/Azure/AzureChestXRay
