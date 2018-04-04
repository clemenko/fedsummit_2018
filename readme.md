# Securing Applications with Docker EE Advanced

In this lab you will integrate Docker EE Advanced in to your development pipeline. You will build your application from a Dockerfile and push your image to the Docker Trusted Registry (DTR). DTR will scan your image for vulnerabilities so they can be fixed before your application is deployed. This helps you build more secure apps!


> **Difficulty**: Beginner

> **Time**: Approximately 30 minutes

> **Tasks**:
>
> * [Prerequisites](#prerequisites)
> * [Introduction](#introduction)
> * [Task 1: Create Secrets](#task1)
> * [Task 2: Deploy Docker Stack](#task2)
>   * [Task 2.1: Enable Docker Image Scanning](#task2.1)
>   * [Task 2.2: Create Repository](#task2.2)
>   * [Task 2.3: Create Promotion Policy](#task2.2)
> * [Task 3: Create DTR Repository](#task3)
>   * [Task 3.1: Enable Docker Image Scanning](#task3.1)
>   * [Task 3.2: Create Repository](#task3.2)
>   * [Task 3.3: Create Promotion Policy](#task3.3)
> * [Task 4: Pull / Push Docker Image ](#task4)
>   * [Task 4.1: Pull Image](#task4.1)
>   * [Task 4.2: Tag Image](#task4.2)
>   * [Task 4.3: Push Image](#task4.2)
> * [Task 5: Docker Content Trust ](#task5)
>   * [Task 5.1: Enable Content Trust](#task5.1)
>   * [Task 5.2: Push Image](#task5.2)


## Document conventions
When you encounter a phrase in between `<` and `>`  you are meant to substitute in a different value.
We are going to leverage the power of [Play With Docker](http://play-with-docker.com).

###<a name="abbreviations"></a>Abbreviations
The following abbreviations are used in this document:

* UCP = Universal Control Plane
* DTR = Docker Trusted Registry
* DCT = Docker Content Trust
* EE = Docker Enterprise Edition
* BOM = Bill of Materials
* CVE = Common Vulnerabilities and Exposures

## <a name="prerequisites"></a>Prerequisites
This lab requires an instance of Docker Enterprise Edition (EE). Docker Enterprise Edition includes Docker Universal Control Plane and Docker Trusted Registry. This lab provides Docker EE. 

## <a name="introduction"></a> Introduction
This workshop is designed to demonstrate the power of Docker Secrets, Image Promotion, Scanning Engine, and Content Trust. We will walk through creating a few secrets. Deploying a stack that uses the secret. Then we will create a Docker Trusted Registry repository where we can create a promotion policy. The promotion policy leverages the output from Image Scanning result. This is the foundation of creating a Secure Supply Chain. You can read more about  secure supply chains for our [Secure Supply Chain reference architecture](https://success.docker.com/article/secure-supply-chain).

## <a name="task1"></a>Task 1: Create Secrets 
The following task will guide you through creating two secrets within Docker Universal Control Plane. 



## <a name="task1"></a>Task 2: Deploy Docker Stack
The following task will guide you through how to create two secrets within Docker Universal Control Plane. 


### <a name="task2.1"></a>Task 2.1: Enable Docker Image Scanning

### <a name="task2.2"></a>Task 2.2: Create Promotion Policy


## <a name="task1"></a>Task 3: Create DTR Repository
The following task will guide you through how to create two secrets within Docker Universal Control Plane. 


## <a name="task1"></a>Task 4: Pull / Push Docker Image 
The following task will guide you through how to create two secrets within Docker Universal Control Plane. 


## <a name="task1"></a>Task 5: Docker Content Trust
The following task will guide you through how to create two secrets within Docker Universal Control Plane. 
