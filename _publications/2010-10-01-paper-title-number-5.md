---
title: "Parallel space-time likelihood optimization for air pollution prediction on large-scale systems"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-5
excerpt: 'Gaussian geostatistical space-time modeling is an effective tool for performing statistical inference of field data evolving in space and time, generalizing spatial modeling alone at the cost of greater complexity of operations and storage, and pushing geostatistical modeling even further into the arms of high performance computing. It makes inferences for missing data by leveraging space-time measurements  of one or more fields. We propose a high-performance implementation of a widely applied space-time modeling method for large-scale systems, using a two-level parallelization technique.  At the inner level, we rely on state-of-the-art dense linear algebra libraries and parallel runtime systems to perform complex matrix operations required in modeling and prediction operations using maximum likelihood estimation (MLE), i.e., the Cholesky factorization of the Gaussian space-time covariance matrix. At the outer level, we parallelize the optimization process using a distributed implementation of the particle swarm optimization (PSO) algorithm. At this level, parallelization is accomplished using MPI sub-communicators, where nodes in each sub-communicator perform a single MLE iteration at a time. We evaluate the performance and the accuracy of the proposed implementation using synthetic datasets and a real particulate matter (PM) dataset illustrating the application of the technique to air pollution. We achieve up to 24.45, 49.70, 100.06, 189.67, 369.22, and 757.16 TFLOPS/s using 32, 64, 128, 256, 512, and 1024 nodes, respectively, of a Cray XC40 system, with an average of 60% of the peak performance on 1024 nodes with 490K problem size.'
date: 2022-10-01
venue: 'Proceedings of the Platform for Advanced Scientific Computing Conference (PASC)'
paperurl: 'http://marysalvana.github.io/files/pasc.pdf'
citation: 'Salvaña, M. L. O., Abdulah, S., Ltaief, H., Sun, Y., Genton, M. G., & Keyes, D. E. (2022). &quot;Parallel space-time likelihood optimization for air pollution prediction on large-scale systems.&quot; <i>Proceedings of the Platform for Advanced Scientific Computing Conference (to appear)</i>.'
---
This paper is about the number 2. The number 3 is left for future work.

[Download paper here](http://marysalvana.github.io/files/pasc.pdf)

