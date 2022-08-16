---
layout: post
title: How to build resiliency in a distributed cloud environment - Part 1
categories:
- resiliency
feature_image: "https://i.picsum.photos/id/588/2509/1673.jpg?hmac=09nSJgh9ylbzEnI7HTVOkIqbyIjREzpm0kTaDnJuFaY"
feature_text: <h2 style="color:white">How to build resiliency in a distributed cloud environment - Part 1</h2> <span
  style="color:white">What is Resiliency and why is it important</span>
excerpt: ''
tags:
- resiliency
- cloud
- aws
---

### Next-Generation Resiliency

With businesses increasingly transforming to digital and modernizing themselves, its imperative to understand and focus on offering the best user-experience. Also, the digitisation of enterprises have leapfrogged in a past few years and an unprecedented COVID pandemic has made businesses realize the importance of digitisation and having an online presence. To that extent, Cloud plays a very pivotal role in breaking the barriers to innovate and help businesses navigate through this digital transformation process more rapidly. 

However the challenge that enterprises face today is that they don't exactly know how they will use the cloud and the agility it provides. The value that we get out of cloud adoption really depends on how we use it. Cloud is really an enabler to innovation, resilience, scale and agility.

Resilience is a very important consideration for businesses to deploy their mission critical applications on the cloud. Enterprises are always keen to understand more about resiliency and how to achieve higher degree of resiliency in their cloud environments. 

* Resiliency is complex just like security, it is an end-to-end discipline that must be built in preferably at the start and not as an after thought. 

* Resiliency is critical as it affects the quality of end-user’s experience.

* Resiliency is key cost driver and is directly related to the number of sites, data copies with a potential to drive cost upwards in multiples of 2x, 3x.

Hence it's important to differentiate resiliency in the cloud from resiliency in the traditional IT, in order to meet the same business objectives of availability and recovery. There are much better ways to provide continuity in the cloud for us to leverage those capabilities.

### What is Resiliency

Resiliency is the ability of a workload to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions, such as misconfigurations or transient network issues. Resiliency is also a measure of how an infrastructure, workload, or platform can protect itself against disruption caused by adverse events and conditions. Resiliency is commonly measured on a scale (1 being the lowest degree, 5 being the highest degree).

Service availability is another commonly used metric to quantitatively measure resiliency. In addition to Service availability objectives, the resiliency strategy also commonly includes Disaster Recovery objectives, based on the strategies for business continuity in case of a disaster event. 

The [AWS Well-Architected Framework](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.resiliency.en.html) defines resilience as “the capability to recover when stressed by load (more requests for service), attacks (either accidental through a bug, or deliberate through intention), and failure of any component in the workload’s components.”

### Why is Resiliency important

The dependency on critical IT systems is so great that the tolerance to outages of these systems are getting lower day by day. The financial consequences of outages can be high, and the numbers are increasing.

> According to Gartner, [the average cost of IT downtime is $5,600 per minute](https://www.the20.com/blog/the-cost-of-it-downtime/), or about $300,000 per hour.

Also the business continuity of the mission critical workloads suffer greatly resulting in poor user experience directly impacting the reputation of the business. For organizations in their cloud adoption journey poor resiliency posture can also mean slower adoption of cloud and stalled migration projects.

Common rootcause for poor resiliency postures in applications are attributed to single points of failures in the architectures and its components.

Hence it's of a great importance to understand the criticality of building highly resilient systems through a well-defined resilency strategy.

### Design Principles

Let’s now take a look at a few design principles that can help enhance the resiliency posture of the workloads on cloud.

##### Automatically recover from failure
By monitoring a workload for key performance indicators, you can trigger automation when a threshold is breached. With automatic notification and tracking of failures, it is possible to automate the recovery process and further elevate the maturity of your operations through proactive and predictive remediation of failures before they occur.

##### Test recovery procedures
While we test feature and functionality extensively we at times fall short in testing recovery scenarios. In the cloud, you can test how your workload fails, and you can validate your recovery procedures. You can use automation to simulate different failures or to recreate scenarios that led to failures before. This approach exposes failure pathways that you can test and fix before a real failure scenario occurs, thus reducing risk.

##### Scale horizontally to increase aggregate workload availability
Mechanisms like horizontal scaling helps reduce the impact of a single failure on the overall workload by replacing one large resource with multiple small resources. It is recommended to distribute requests across multiple, smaller resources to ensure that they don’t share a common point of failure.

##### Stop guessing the capacity
In the cloud you will not have challenges of workloads exceeding capacity if you plan well. You can monitor demand and workload utilization, and automate the addition or removal of resources to maintain the optimal level to satisfy demand without over- or under-provisioning.

##### Manage change in automation
Changes to your infrastructure should be made using automation. The changes that need to be managed include changes to the automation, which then can be tracked and reviewed.

Resiliency is not just a technical problem to solve, but it is also about the Process, People and Culture. Hence it's important to view Resiliency as a multi-dimensional challenge that requires a holistic solution across architectural attributes such as availability, security, performance and operational attributes such as cloud operations, DevOps, Change management etc. 

### "Cloud" and "Architecting for Resiliency" - match made in heaven

There is no better place to design, build and deploy highly resilient workloads than in a Cloud environment. [AWS Cloud](https://aws.amazon.com/) offers the broadest range of services and building blocks for enterprises to architect, build and deploy their workloads in a highly resilient fashion. 

In the subsequent posts I will dive more deeper into the AWS Global Infrastructure and the services that AWS offers in the domain of resiliency. I also wish to throw more light into the best practices for planning resiliency on AWS along with some important design patterns for building highly resilient infrastructure and applications on AWS Cloud.

Thanks for reading this post. Stay tuned!! 