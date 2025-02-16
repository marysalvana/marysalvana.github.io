---
title: "High performance multivariate spatial modeling for geostatistical data on manycore systems"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Modeling and inferring spatial relationships and predicting missing values of environmental data are some of the main tasks
of geospatial statisticians. These routine tasks are accomplished using multivariate geospatial models and the cokriging technique.
The latter requires the evaluation of the expensive Gaussian log-likelihood function, which has impeded the adoption of multivariate
geospatial models for large multivariate spatial datasets. However, this large-scale cokriging challenge provides a fertile ground for
supercomputing implementations for the geospatial statistics community as it is paramount to scale computational capability to match
the growth in environmental data coming from the widespread use of different data collection technologies. In this article, we develop
and deploy large-scale multivariate spatial modeling and inference on parallel hardware architectures. To tackle the increasing
complexity in matrix operations and the massive concurrency in parallel systems, we leverage low-rank matrix approximation
techniques with task-based programming models and schedule the asynchronous computational tasks using a dynamic runtime
system. The proposed framework provides both the dense and the approximated computations of the Gaussian log-likelihood function.
It demonstrates accuracy robustness and performance scalability on a variety of computer systems. Using both synthetic and real
datasets, the low-rank matrix approximation shows better performance compared to exact computation, while preserving the
application requirements in both parameter estimation and prediction accuracy. We also propose a novel algorithm to assess the
prediction accuracy after the online parameter estimation. The algorithm quantifies prediction performance and provides a benchmark
for measuring the efficiency and accuracy of several approximation techniques in multivariate spatial modeling.'
date: 2021-10-01
venue: 'IEEE Transactions on Parallel and Distributed Systems'
paperurl: 'http://marysalvana.github.io/files/tpds.pdf'
citation: 'Salvaña, M. L. O., Abdulah, S., Huang, H., Ltaief, H., Sun, Y., Genton, M. G., & Keyes, D. E. (2021). &quot;High performance multivariate spatial modeling for geostatistical data on manycore systems.&quot; <i>IEEE Transactions on Parallel and Distributed Systems</i>. 32(11), 2719-2733.'
---
This paper is about the number 2. The number 3 is left for future work.

[Download paper here](http://marysalvana.github.io/files/tpds.pdf)

