# Word Count Application using Hadoop's MapReduce

## Overview
This project was meticulously crafted as an integral component of the Advanced Database course curriculum at Rutgers University. It showcases the practical application and implementation of Hadoop's renowned MapReduce framework, with Java serving as the cornerstone programming language. The primary objective of this application is to demonstrate a fundamental, yet powerful, use case of Hadoop's MapReduce: counting the occurrence of words within a large dataset.

## Objectives
The aim of this project was to:
- Understand and apply the concepts of the MapReduce programming model.
- Utilize Hadoop's ecosystem for processing large sets of data efficiently.
- Develop proficiency in Java for creating MapReduce jobs.
- Highlight the scalability and robustness of Hadoop in handling big data challenges.

## Implementation Details
The word count application is designed to parse text data, breaking it down into individual words, and then counting the occurrences of each word across the dataset. The process is divided into two main phases:
1. **Map Phase:** Each document is split into words, and a key-value pair is generated for each word with the word as the key and `1` as the value.
2. **Reduce Phase:** The key-value pairs are shuffled and sorted by Hadoop, allowing all values associated with the same word to be aggregated. The reducer then sums up these counts to determine the total occurrences of each word.

## Technologies Used
- **Hadoop MapReduce:** A framework for easily writing applications that process vast amounts of data (multi-terabyte datasets) in parallel on large clusters (thousands of nodes) of commodity hardware in a reliable, fault-tolerant manner.
- **Java:** The project is implemented in Java, leveraging its robust API and ecosystem for developing efficient MapReduce jobs.

## How to Run
Instructions for setting up the environment, compiling the Java code, and executing the MapReduce job are provided in the subsequent sections. Users will need access to a Hadoop cluster or a single-node setup on their local machines to run the application.

## Conclusion
Through the successful implementation of this word count application, this project not only serves as a practical demonstration of the Hadoop MapReduce framework but also exemplifies the power of Java in crafting scalable solutions for big data processing challenges. It is a testament to the learning and skill development fostered by the Advanced Database course at Rutgers University, aiming to equip students with the knowledge and tools necessary to tackle real-world data-intensive tasks.
