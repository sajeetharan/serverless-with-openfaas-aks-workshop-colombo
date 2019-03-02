# Security for AKS - AKS Workshop 2019 Colombo
Going Serverless using OpenFaas with AKS Hands-On Session Guidelines for AKS Workshop 2019.

# Content of the Hands-On Session

* [Let's get OpenFaas live on AKS](https://slides.com/sajeetharansinnathurai/openfaas#/13)

# Prerequisites
Make sure to install the following tools in your development machine prior to the hands-on session.

## 1. Latest Version of Azure CLI
The current latest version of the Azure CLI is 2.0.59 as of now. Download and Install the Azure CLI for your operating system by following the links given below.

* [Install On Windows](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest)
* [Install on MacOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest)
* [Install on Linux](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)

Run the following commands to verify the installation and the CLI version
```bash
# Check the Azure CLI version
az --version

# Login to Azure Subscription
az login --use-device-code
```
# Using Azure Cloud Shell
We will be using the Azure Cloud Shell to execute the same commands and follow along as its easy to see the resources created and all the necessary AKS commands are available without any additional installation.

## 2. Install Docker for windows
You need to Docker on your local machine to upload the functions built to OpenFaas on AKS. Grab it from [here](https://docs.docker.com/docker-for-windows/install/).

## 3. Create DockerHub account
You will need an account on Docker hub. Create one from  [here](https://hub.docker.com/).

## Setup OpenFaas on AKS.

 [Lets's setup OpenFaas on AKS](https://slides.com/sajeetharansinnathurai/openfaas#/15).




