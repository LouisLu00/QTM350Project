Narrative
Imagine a typical evening at Emory: the streets are quiet, but for a group of junior and senior students, the walk back to their off-campus housing is a silent drumroll of apprehension. There's a shared concern among them—safety. As conversations unfold, it's clear that the predictability of their schedules and the lack of adequate security measures have left them feeling vulnerable. One evening, huddled in the modest living room of their shared apartment, the group voiced their frustrations. Kristen, who lived the farthest, shared her unease about the poorly lit paths she took home. The others nodded in agreement, each with their own tale of unease. They felt unequipped, defenseless, not just by the absence of tools but by the lack of proactive security measures.
 
It was during one of these discussions that the seed of an idea took root. Angelina, a computer science major with an interest in artificial intelligence, suggested leveraging our collective expertise to tackle this issue head-on. "What if we could improve our security without the need for constant human vigilance?" she proposed. The idea ignited a spark of our final project. We imagined a system where security cameras, equipped with Amazon Rekognition CompareFaces, could identify potential threats before they escalated. Specifically, the security camera system will accurately identify suspicious, unknown faces from those in the source, even when faces are covered with masks or sunglasses. 


Louis, who had tinkered with home automation systems, saw the potential immediately. "This could be more than just a class project. It's about making our community safer." he said with conviction. And so, the project began—not just as an academic pursuit but as a mission. They would delve into the world of image recognition, not just to explore its technological boundaries but to seek out solutions that could make a real difference in their daily lives. It was a story of students turning their vulnerability into empowerment through innovation, and it all started with the simple wish to feel safe on the streets they called home.
 
Problem Definition
In this project, we aim to:
1.         Assess the algorithmic performance of Amazon Rekognition when faces are covered with masks or sunglasses, an often-overlooked factor that could impact recognition accuracy.
2.         Understand the implications of facial obstructions on Amazon Rekognition’s robustness and adaptability, particularly for public safety and surveillance applications.
 
Hypothesis
We hypothesize that facial obstructions, like sunglasses or masks, will challenge the precision of Amazon Rekognition's CompareFaces function. Our study aims to quantify the impact of these common occlusions on the system's ability to match individuals with their corresponding images in a predefined dataset. This investigation will shed light on the robustness of facial recognition technology in scenarios where identity verification is critical.
[a]
 
   
Architectural Diagram
The architectural diagram for our project visualized this process, demonstrating the flow from data generation to final reporting.
 
In our AWS-based project, we first stored a dataset of facial images in an S3 bucket. Using SageMaker's Jupyter Notebooks with Python, we accessed these images, running them through Amazon Rekognition's API for facial recognition analysis. The output, including recognition accuracy metrics and pictures containing matching faces, was returned. We report this data directly within our notebooks to interpret the results. The entire process and findings were documented and shared on GitHub, providing a replicable model for others to analyze facial recognition performance, such as the impact of facial tattoos on emotion detection algorithms.
 
 
Conclusion:


Implication and potential application














# Project Name: Visionary Insights: AWS Rekognition in Action
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






## Contact
For queries or feedback, please reach out to lliu263@emory.edu.




[a]Updated