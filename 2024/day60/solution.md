# Day 60 - Terraform🔥

Hello Learners , you guys are doing every task by creating an ec2 instance (mostly). Today let’s automate this process . How to do it ? Well Terraform is the solution .

## What is Terraform?

Terraform is an infrastructure as code (IaC) tool that allows you to create, manage, and update infrastructure
resources such as virtual machines, networks, and storage in a repeatable, scalable, and automated way.

## Task 1:

Install Terraform on your system

![Screenshot from 2024-10-08 04-01-31](https://github.com/user-attachments/assets/9b2dc226-46bd-4e4b-89e6-d513180676cf)

## Task 2: Answer below questions

- Why we use terraform? </br>

  **We use terraform for almost tasks that we need to automate like create files, backups, create containers-images, create containers, call with cloud and much more**

- What is Infrastructure as Code (IaC)? </br>

  **Infrasctructure as Code (IaC) is a way to automate almost tasks**

- What is Resource? </br>

  **Resource is a fundamental building block that represents a single piece of infrastructure you want to manage.**

- What is Provider? </br>

  **The provider is the service that we use to automate our tasks in terraform calling whith API**

- Whats is State file in terraform? What’s the importance of it ? </br>

  **State file is a crucial component that keeps track of the resources managed by your Terraform configurations. It serves as a mapping between your configuration files and the real-world resources.**

- What is Desired and Current State? </br>

  **Desired State:** </br>
  **Definition: The desired state is what you define in your Terraform configuration files. It represents the infrastructure configuration you want to achieve, including all the resources, their properties, and how they should be structured.**

  **Example: If you define a virtual machine with specific parameters (like instance type, AMI, and network settings) in your Terraform code, that configuration represents the desired state of your infrastructure.**

  **Current State:**</br>
  **Definition: The current state reflects the actual state of the infrastructure as it exists in the real world. This information is stored in the Terraform state file and is used by Terraform to understand what resources are currently deployed and their configurations.**

  **Example: If you have an EC2 instance running in AWS, the current state would include details about that instance, such as its ID, status, IP address, and any tags that are applied to it.**

