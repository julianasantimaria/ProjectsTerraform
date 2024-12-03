# Individual Infrastructure as Code projects

This repository contains a series of Infrastructure as Code files that I made to allocate resources in the Cloud: AWS, Azure and GCP.

## Overview

There are several individual projects for allocating resources in clouds through code. 

Each project has its particularity in the amount of resources, cloud, network, subnet, IAM, region of the allocated resource, etc. In some projects, the code may allocate resources to different characteristics at once. 

The advantage of increasing resources in this way is the guarantee of CI/CD control, cost control and greater control of all allocated resources, creating ease and agility in the process.

Lab2 and Lab3 - These are tool allocation projects in AWS using terraform; 
<br/><br/>
Lab4 - Development and implementation of a cloud infrastructure solution using Terraform to host a Data Science (Machine Learning) application on AWS;
<br/><br/>
Lab5 - I created an entire structure integrating S3 tools, with the var.tf file, ECS Elastic, Load Balance, cloudWatch, configurations and creation of VPC and Subnets. In the end generating an HTML page, on AWS;
<br/><br/>
Project1 - Tools and Languages: AWS EMR, Apache Flink, Terraform - AWS.
Project Functions: Automation of scalable infrastructure for batch and streaming data pipelines with low latency.
Objective: Develop a robust solution for data processing, leveraging AWS EMR and Apache Flink, with IaC provisioning automated via Terraform.
<br/><br/>
Project2 - Tools and Languages: Terraform, AWS (EMR), Azure, PySpark, Apache Spark - AWS.
Project Functions: Automated deployment of a scalable cluster for distributed Machine Learning, Big Data model training, and resource optimization through distributed processing.
Objective: Train large-scale ML models using PySpark on EMR, ensuring efficient analysis of petabyte-scale data with advanced Data Science practices. All integration and result generation are automated in Terraform.
<br/><br/>

## Infrastructure as Code (IaC)

 <img width="2500px" align="right"  src="https://github.com/julianasantimaria/ProjectsTerraform/blob/HTML/IaC.jpeg">

 <br/>
 <br/>


## Project Structure

The structuring of this repository is difficult and requires no Frontend, Backend, Data, Data Science or Machine Learning Development.

These are evolutionary projects for allocating resources in the cloud through code.

## Requisites

Make sure you have Docker and Terraform tools and accounts in the Azure, AWS and GCP clouds.

```bash
- Docker
- Terraform
- AWS
- GCP
- Azure