---
title: "How to develop E2E Applications"
description: "How I am learning E2E application development despite not being a full time developer"
dateString: Nov 2022
draft: false
tags: ["AWS", "Github", "Java", "React", "Git", "Linux"]
weight: 101
cover:
  image: "/blog/e2e-application-development/e2edev.png"
---

# Credentials

#### 🔗 [Full-Stack-Application](https://github.com/heyrmi/FullStackApplication)

#### 🔗 [Continuous Delivery GithubAction](https://github.com/heyrmi/FullStackApplication/actions/workflows/deploy.yml)

# Introduction

I am a test engineer by profession but I like to tinker things, this let me to explore the world of web dev with Java since I was working with Java anyways in testing. Thus I learned about Spring Boot the easiest way to bootstrap your backend development java.

# Why not use thymeleaf?

With the rise of SPA like React, companies have constantly been shifting from templating engines to separate their backend and frontend code and communicating via REST APIs, and host them seperate cloud servers, which offers far more elasticity in terms of scaling and resiliency.

The AWS **Solutions Architect - Associate** certification validates your ability to design and deploy well-architected solutions on AWS, which is the leading cloud provider today. In simple terms, this exam tests your ability to propose an architecture given a specific scenario. For example: a company wants their application to continue running even if an entire AWS region, where that application was hosted, is down due to a disaster. So, how would you design their infrastructure around this use case?

# Things used in Application

List of library used

- Spring Boot
- Spring Security
- React
- MUI
- JIB
- Maven Plugin
- Github Actions

# Github Actions

You can use Github Actions to:

- Test
- Build
- Deploy

your application

> Github Actions for public projects are free to use as of now.

# Deployment

For deployment you have plethora of options, but AWS seems most viable and in most demand.
Even in AWS there are many services and to choose one from those services can be hard.

We can take the route of deploying on simple EC2 (Elastic Compute) instance by configuring the EC2 instance to our needs that is by installing applications like Java and Node (and more dependencies) and then deploying it.

Or we can take the route of deploying our SpringBoot Application on Elastic Container Service (ECS) and manage it there. But this will again require us to tinker with the number of instance and scaling configurations.

The most easy way is to deploy it on Elastic Beanstalk, which is a service which takes care of scaling and does not care if you are deploying Dokcer Container or a executable JAR.

The process to that is mentioned below:

- To be done 1
- To be done 2

# That's all, untill next time

That was all about the E2E Application Development experience, see you next time in some other blog.
