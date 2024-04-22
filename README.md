# mini-project-2
This repository consists of necessary files and scripts created and stored for the Mini-project 2.
Using Containerized Files from Docker Hub

#Introduction

-This README guide provides instructions on how to use the containerized Python
files available on Docker Hub. These files are pre-configured with dependencies and
ready for execution within a Docker environment.

#Prerequisites

-Before getting started, ensure that you have Docker installed on your system. You
can download and install Docker Desktop from the official Docker website.

#Usage Instructions

-Follow these steps to use the containerized Python files from Docker Hub:

Step 1

Pull Docker Image: Open your terminal or command prompt and execute the following
command to pull the Docker image containing the desired Python file:

1. docker pull ghaniahmad1506/mini-project:hzz_analysis
2. docker pull ghaniahmad1506/mini-project:data_processing
3. docker pull ghaniahmad1506/mini-project:data_plotting

Step 2

Run Docker Containers: Once the images are downloaded, run Docker containers using
the following commands:

1. docker run -it ghaniahmad1506/mini-project:hzz_analysis
2. docker run -it ghaniahmad1506/mini-project:data_processing
3. docker run -it ghaniahmad1506/mini-project:data_plotting

Step 3

Access Container Environment: You will now be inside the Docker container
environments. Use the appropriate command to execute the Python files within each
container. For example:

1. python data_processing.py
2. python data_plotting.py
3. python HZZ_Analysis.py

You are now able to run the python file!

## About
-This project is part of the HZZ Analysis conducted by Mohammad Ghani bin
Awang Ahmad. Student number 2472050.
