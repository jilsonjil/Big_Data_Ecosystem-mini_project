# Word Count using MapReduce in Hadoop vs Spark

## Overview
This project implements the Word Count program using both **MapReduce** in **Hadoop** and **Apache Spark** to compare their performance. The goal is to demonstrate that Spark’s in-memory processing can result in faster execution times compared to Hadoop’s traditional disk-based approach.

The project includes two implementations:
- **Word Count using MapReduce (Hadoop)**: A classic implementation of the Word Count problem using the Hadoop MapReduce framework.
- **Word Count using Apache Spark**: An optimized version of the same problem using Apache Spark's in-memory processing.

Through benchmarking, the performance differences between the two approaches are showcased. Spark’s in-memory capabilities often result in up to **50% faster execution** than Hadoop’s disk-based processing, especially for larger datasets.

## Tech Stack
- **Hadoop**
- **Apache Spark**
- **Java**
- **Python**

## Features
- Implements the Word Count program using both Hadoop and Spark.
- Performance comparison between Hadoop MapReduce and Spark for word counting.
- Demonstrates the difference in execution time due to Hadoop’s disk-based approach vs Spark’s in-memory processing.

## Setup and Installation

### Prerequisites
- **Hadoop** installed and configured (can be a standalone cluster).
- **Apache Spark** installed and configured.
- **Java** and **Python** installed on your system.
- Proper setup for running **Hadoop** and **Spark** jobs on your local or cloud environment.


