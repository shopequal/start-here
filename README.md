## Shop Equal

This project folder provides a description of the Shop Equal Project

The Getting Started repo will provide an overview of the project, and show you how to get the shop equal application running.


### About

Shop equal is an open source project that provides a public API of Black Owned Businesses, as well as a website where
you can browse these businesses as well.

This project was initiatied during the NYC Coders Black Lives Matter Virtual Hackathon held in June 2019.

Our goals are to:

- Create a public API that can developers can use to integrate Black Owned Businesses into their apps
- Provide a central website for users to view various Black Owned Business
- Allow anyone to contribute Black Owned Businesses to the website and database
- As an open source project allow interested developers to contribute code to this project.


### Architectual Overview

Our application consists of:

Frontend:
- React

Backend:
- Ruby on Rails
- PostGres


### How to use the Shop Equal Website & API

Website: www.shop-equal.netlify.app


#### Running the Front End Locally:

##### Prerequisites

- Install Node.js : [Install Node.js](https://nodejs.org/en/download/)
- Clone the Front End Repository (shop-equal-frontend) : ```git clone https://github.com/shopequal/shop-equal-frontend```
- Check out the available issues: https://github.com/shopequal/shop-equal-frontend/issues


#### Run the Front End Using Docker:

##### What is Docker?

Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package. If you an unsure if your computer can
download the dependencies, libraries and other parts associated with it, docker allows you to run the application in an isolated environment on your computer.

##### Prerequisites

- Install Docker
  - [Install Docker Desktop on Mac](https://docs.docker.com/docker-for-mac/install/)
  - [Install Docker Desktop on Windows](https://docs.docker.com/docker-for-windows/install/)
  - [Install Docker Desktop on Linux](https://docs.docker.com/engine/install/)

##### Learn Docker

- [LearnDocker.online](https://learndocker.online/)
- [Learn Docker & Containers using Interactive Browser-Based Scenarios](https://www.katacoda.com/courses/docker)

##### Deployment Methods

- Docker - Work in Progress
- Podman - Pending
- OpenShift/Kubernetes - Pending

#### shop-equal-api-documentation

[shop-equal-api-documentation](shop-equal-api-documentation/)

##### shop-equal-frontend

Once you have downloaded Docker, go here: [shop-equal-frontend](shop-equal-frontend/)


### How to Contribute to the Shop Equal Project Front End
- Go to the 'Issues' tab of shop-equal-frontend and choose a current issue
- In your terminal, create a branch with a name that references the issue
- Once you have added the changes needed to solve the issue, create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) on the 'master' branch of shop-equal-frontend


