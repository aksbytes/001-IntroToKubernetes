# What the Hack: Intro To Kubernetes
Student Files for [What the Hack 001-IntroToKubernetes](https://github.com/microsoft/WhatTheHack)


1. Follow Instructions [here](Challenge-00.md) to setup your environment


1. open up your Linux terminal and download the student files 
```bash
git clone https://github.com/aksbytes/001-IntroToKubernetes.git
```
3. I this video we are starting with Path C because we are not teaching Docker or how to create custom images but instead focusing on AKS and linking Azure Container Registry 

    ![paths](https://github.com/microsoft/WhatTheHack/raw/master/001-IntroToKubernetes/Images/wth-container-challenge-paths.png)

    #### [~~PATH A~~](./Solution-01A.md) - Challenge 1A & 2A Coach's Guides

    Use this path to provide students with a comprehensive experience of building, testing, and running containers locally. Students will create a VM (using a provided ARM template) with Docker and all other required tools to ensure uniformity of environments. In this path, your students will create a Dockerfile, build and test local containers, and then push these container images to Azure Container Registry. 
    #### [~~PATH B~~](./Solution-02B.md) - Challenge 2B Coach's Guide
    Use this path if your students understand Docker, don't care about building images locally, and/or have environments issues that would prevent them from building containers locally. In this path, your students will be given a Dockerfile, will create an Azure Container Registry, and then will use ACR tasks to build the images natively inside ACR.
    #### [PATH C](./Solution-02C.md) - Challenge 2C Coach's Guide
    Use this path to skip any work with Docker & containers, but you still want to learn about ACR.  The path is similar to Path B, however in this case students will simply import pre-staged containers from DockerHub into ACR (eg, there is no container building involved)
    #### [~~PATH D~~](./Solution-03.md) - Challenge 3 Coach's Guide
    Use this path to skip any work with Docker, containers, and ACR altogether. This path can also be used if students do not have "Owner" role permissions on their Azure subscription and thus will not be able to attach ACR to AKS.  Students will deploy our pre-built container images directly from DockerHub when creating their Kubernetes manifests.

4. Begin [Challenge 01](Challenge-01.md) and choose **PATH C**
