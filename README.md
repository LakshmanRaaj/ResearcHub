![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![DockerHub](https://img.shields.io/badge/DockerHub-0db7ed?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/s3/)
[![Great Expectations](https://img.shields.io/badge/Great_Expectations-00778B?style=flat-square&logo=great-expectations&logoColor=white)](https://greatexpectations.io/)
[![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-007A88?style=flat-square&logo=apache-airflow&logoColor=white)](https://airflow.apache.org/)


# ResearcHub

## Introduction
ResearcHub is an application that allows users to scrape data from Springer and retrieve documents of interest. It also provides several features such as summarization, translation, and recommendations based on the retrieved documents. The application also allows users to query the documents for information.

This project aims to make it easier for users to retrieve and analyze academic documents by providing a range of features to enhance the user's experience and increase the accessibility of the documents.

Technologies used in this project
* Streamlit
* AWS S3
* Apache Airflow
* Docker
* Google Cloud Platform
* FastAPI
* Great Expectations

## Architecture diagram
![deployment_architecture_diagram](https://user-images.githubusercontent.com/108916132/235260615-d93723bb-91ca-4f2e-b723-427f6b53d6f0.png)

## Installation

To clone and replicate the repository, please follow the steps below:

1.  Open the command line interface (CLI) on your computer.
2.  Navigate to the directory where you want to clone the repository.
3.  Type `git clone <repo lonk>` and press Enter. This will clone the repository to your local machine.
4.  Navigate into the cloned repository using `cd your-repo`
5.  Set environment variables as mentioned below.
6.  Navigate to 'streamlit' directory and run the command `streamlit run video.py`

#### Environment variables:

* PINECONE_API_KEY = "your_key_here"
* PINECONE_ENV = "your_key_here"
* PINECONE_API_KEY_DOC = "your_key_here"
* PINECONE_ENV_DOC = "your_key_here"
* AWS_ACCESS_KEY = "your_key_here"
* AWS_SECRET_KEY = "your_key_here"
* USER_BUCKET_NAME =  "your_key_here"
* AWS_REGION =  "your_key_here"
* OPENAI_ACCESS_KEY = "your_key_here"
* RAPID_API_HOST = "your_key_here"
* RAPID_API_KEY = "your_key_here"

### Application demo:-
![Demo](https://github.com/Hmittal15/Instacart-customer-order-analysis/assets/108916132/d1fef5de-fd4b-4dc3-ad6f-7f4e916baea2)

### Link to full explanatory video:-
https://youtu.be/eG1IvwuZ9e4

## Application public link:
34.75.99.189:8000/

## Airflow DAGs:
http://34.75.99.189:8080/

## Codelab document:
https://codelabs-preview.appspot.com/?file_id=1-GWEz08lyZdIzqKjxUH_mkB46KBEHLkUl31T9X-kV1Y#0

## Attestation:
WE ATTEST THAT WE HAVEN’T USED ANY OTHER STUDENTS’ WORK IN OUR ASSIGNMENT AND ABIDE BY THE POLICIES LISTED IN THE STUDENT HANDBOOK
Contribution:
* Ananthakrishnan Harikumar: 25%
* Harshit Mittal: 25%
* Lakshman Raaj Senthil Nathan: 25%
* Sruthi Bhaskar: 25%
