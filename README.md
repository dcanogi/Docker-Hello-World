# Hello Docker Project
This project contains a simple Dockerfile that, when built and run, outputs “Hello, @Name” to the console.

# Project URL
This is a local Docker project from the roadmap.sh, You can find the project details here.

# Getting Started
These instructions will guide you through building and running the Docker image.

# Prerequisites
Ensure you have Docker installed on your machine. You can download and install Docker from here.

# Instructions
## Clone the repository (if applicable):

`git clone https://github.com/dcanogi/Docker-Hello-World.git
cd Docker-Hello-World`

## Build the Docker image:

Run the following command to build the Docker image using the Dockerfile in the root directory:

`docker build -t Hello-World .`
## Run the Docker container:

After building the image, you can run the container using:

`docker run Hello-World`
Output:

After running the container, you should see the following output in your terminal:

`Hello, Daniel!`
