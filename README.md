# Project Name: Visionary Insights: AWS Rekognition in Action
[Blog](https://qtm350project.s3.amazonaws.com/blog.html)

#### Group members: Winci Liang, Angelina Ying, Kristen Li, Angela Liu, Louis Lu


## Overview
This Jupyter Notebook offers an in-depth exploration of AWS's Rekognition API, demonstrating its fundamental mechanisms and conventional applications through practical Python examples using a dataset of our group members’ pictures.


## Prerequisites
- Basic understanding of Python programming.
- Familiarity with AWS services, especially AWS Rekognition.
- Access to an AWS account.
- Python libraries: `boto3`, `PIL`, `io`, `matplotlib`. Ensure these are installed in your environment.




## Structure
The notebook is divided into several sections, each focusing on a different aspect of the Rekognition API:
1. Fundamental Mechanism of Rekognition API
2. Conventional Applications of Rekognition API
3. Functions to evaluate the API’s performance and conduct outputs with similarity score and outlined location of the faces
4. Practical comparisons between the similarity between images identified using the Rekognition API using the functions written




## Usage
Navigate through the sections to understand the functionalities of the Rekognition API. The notebook includes code blocks that you can run to interact with the API and visualise its capabilities.


## Features
- Introduction of the AWS Rekognition API
- Hands-on examples with AWS Rekognition.
- Demonstrations of image comparison and facial recognition.
- Visualization of results.


## Architecture Diagram
![Diagram](/visualizations/diagram.PNG)
  

In our project, which utilizes AWS technology, we began by uploading a collection of facial images to an S3 bucket. Leveraging Python in SageMaker's Jupyter Notebooks, we processed these images through the Amazon Rekognition API for facial analysis. The results, encompassing both accuracy metrics and images with identified faces, were obtained and analyzed directly within the notebooks. We documented each step and the outcomes on GitHub, offering a comprehensive and reproducible framework for evaluating facial recognition efficacy. This includes examining how specific factors, like facial tattoos, influence emotion detection algorithms.


The diagram presents the workflow and components of an AWS-based facial recognition project. Here's a summary of the key steps and components illustrated:


1. **Image Input**: The process begins with an input of facial images.
2. **Amazon S3**: The images are stored in Amazon Simple Storage Service (S3), with separate source and target buckets designated.
3. **AWS Jupyter Notebook in SageMaker**: AWS SageMaker is used to run a Jupyter Notebook, which serves as the interactive coding environment.
4. **Python SDK**: The AWS Software Development Kit (SDK) for Python, likely Boto3, is utilized within the Jupyter Notebook to interact with AWS services.
5. **API Gateway**: An intermediary that provides an endpoint for the Jupyter Notebook to communicate with the Rekognition API.
6. **Rekognition**: Amazon Rekognition is the service used to analyze the facial images for recognition.
7. **Rekognition Image**: This likely refers to the output received from the Rekognition service after processing the images, which includes analyzed data and possibly transformed images.
8. **GitHub**: The final step involves documenting the entire process and findings on GitHub, making the project's code and results accessible for replication and further development.


This workflow demonstrates a cloud-based facial recognition system, from data storage to analysis and reporting, within the AWS ecosystem.



## Result
![Diagram](/visualizations/result.PNG)


## Contact
For queries or feedback, please reach out to lliu263@emory.edu.




[a]Updated
