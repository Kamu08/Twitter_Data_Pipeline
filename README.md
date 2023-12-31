# Twitter Data Pipeline with Airflow and Python

## Overview:

I recently completed a data engineering project focused on building a robust data pipeline for efficiently collecting and analyzing large amounts of Twitter data. Leveraging Python, Apache Airflow, and Amazon Web Services (AWS), I successfully extracted data from the Twitter API, performed data transformations and processing, deployed the processed data to an Apache Airflow instance on AWS EC2, and stored the data on AWS S3 for further analysis.

## Project Roadmap:

In this project, I followed a well-defined roadmap to create an effective data pipeline for Twitter data analysis. The initial step involved creating an architecture diagram to visualize the data flow and understand the interaction between each component.

Following that, I implemented Apache Airflow, a powerful platform for scheduling and managing workflows. Using Airflow, I defined the directed acyclic graph (DAG) and specified individual tasks constituting the entire pipeline.

Upon setting up the DAG, my focus shifted to executing the pipeline, necessitating the setup of the Twitter API and obtaining the API key and secret key. Once successfully executed, I deployed the code on Apache Airflow to ensure the smooth and efficient running of the pipeline.

## Architecture:

![Pipeline Architecture](arch.png)

## Technologies Used:

- **Python and Pandas**
- **Apache Airflow**
- **Amazon EC2**
- **Amazon S3**

## What I Learned Through This Project:

This project provided me with invaluable hands-on experience in constructing a data pipeline from inception to completion, significantly enhancing my understanding of data engineering. Key takeaways include:

- Utilizing Apache Airflow to schedule and manage workflows.
- Extracting data from the Twitter API and processing it for further analysis using Python and Pandas.
- Understanding the limitations and restrictions of the Twitter API.
- Deploying code on AWS EC2 and storing data on S3, essential skills for a data engineer.

In summary, this project presented a challenging yet rewarding experience, allowing me to apply data engineering concepts in a practical setting. The skills and knowledge gained are foundational as I pursue a career in the dynamic field of data engineering.
