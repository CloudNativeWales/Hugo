---
author: Mohammed Sohaib Nawaz
categories:
- meetup
- devopsgroup
- ai wales
- aws south wales
- cardiff
- Ivan Pedrazas
- Dan Twining
date: 2019-11-14T09:00:00Z
description: The one where we learnt about the state of Devops, and Kubernetes , Gitops and ... whatever
draft: false
featured_image: /images/2019/05/header.jpg
slug: 019_novembermeetup
title: 019_NovemberMeetup.md
---

# OUR EIGHTEENTH MEETUP
Authored by: [Mohammed Sohaib Nawaz](https://twitter.com/saibnawaz), [Faiyaz Alam](https://www.linkedin.com/in/faiyaz-alam-4504b7b3)

> Thursday, November 14th, 6:30pm at DevOpsGroup offices, Cardiff.

# We Need Your Help!
We would like you to support and help out our friends over at Skills Matter due to the extremely sad news that they have gone into administration by retweeting [this tweet](https://twitter.com/nicpereirahere/status/1194946341488726016).

## Meetup Page
* [Cloud Native Wales](https://www.meetup.com/cloudnativewales/)

## Meetup Details
### Sponsors
* [DevOpsGroup](https://www.devopsgroup.com/)
* [KataKoda](https://www.katacoda.com)
* [LearnK8S](https://learnk8s.io/)
* [Jetbrains](https://www.jetbrains.com/)
* [Cloud Native Computing Foundation](https://www.cncf.io/)

# Acknowledgements

We have to say a massive thanks to [DevOpsGroup](https://www.devopsgroup.com/) for supporting us and helping us grow the Cloud Native Community in Wales for over a year! They have provided us with a stunning venue for our meetups. All the drinks and food provided by them also goes down well! Head over to their [careers page](https://www.devopsgroup.com/careers/) to check out exciting vacancies.

# Speakers
## [Dan Twining](https://twitter.com/dantwining)
### The State of DevOps
What is the DevOps Assessment?  
DevOps has taken hold in IT. A growing number of organisations are adopting DevOps to deliver applications and services at higher speed. As organisations realising the benefits of development and operations teams working together instead of in siloed environments, organisations are fast embracing the idea of DevOps.
 
To move forward in the DevOps journey, companies first should outline, identify and map the areas where they need improvement. Having a clear idea of maturity of your current IT infrastructure will help you greatly in that process. This is why we have the state of devops report.
 
Why the state of devops report matters?
Accelerate State of DevOps Report 2019 is out like every other year. The findings in the 2019 report outlines that higher performing teams were 24 times more likely than lower performers to execute all five capabilities of cloud computing  
* On demand self-service  
* Broad network access  
* Resource pooling  
* Rapid elasticity  
* Measured service  

In summary the report tells you:  
* how they manage,  
* Secondly how they use metrics to classify low, medium, high and elite performers using the following metrics (Lead Time, Deployment Frequency, Change Fail, Time to Restore and Availability)  
* Thirdly shows the differences in capabilities of cloud computing higher performers than lower performers  
* Lastly it includes context around the benefits you gain from Devops.  

During the talk Dan Twining gave an Analogy of Florence Nightingale of how she collected and analysed her findings:  
* Establish disproportionally high mortality rate within British Army  
* Establish disproportionally high incidence of hospital deaths within Army deaths  
* Establish that hospital death rates due to "something destructive in the building itself"  
* Identify causes of army hospital mortality  
* Quantify the benefits of adopting better practises  
 
Once Florence Nightingale had conducted her research she was able to find out the following:  
* What the business cares about but has no direct control over (mortality)  
* Proof that doing things differently has a positive, significant effect on what the business cares about (destructive in the building  
* What can be controlled, what can be done differently (causes of army hospital mortality)  
 
Similarly in the devops report it includes:  
* Prove a high distribution of organisational performance across orgs of All sizes, locations, industry sectors  
* Prove that high organisational performance can be predicted by "software delivery and operational performance (SDO)"  
* Identify key capabilities and practises that drive SDO performance  
* Quantify the benefits of adopting better practises  
 
From the devops report  the following can be identified:  
* What the business cares about but has no direct control over (organisational performance)  
* Proof that doing things differently has a positive, significant effect on what the business cares about (SDO)  
* What can be controlled, what can be done differently. (key capabilities and practises)  
 
 
Summary  
To summarise the devops report mentions that you are twice as likely to exceed organisational performance goals as an Elite performer as compared to a low performer
  
  
### Links:
* [Slides](https://docs.google.com/presentation/d/1iRkIg-5ivvVL3USz09T04pEFjEawFXNlCh_vK7RiZqw/edit)
* [The State of DevOps - Slides](https://cloud.google.com/devops/)
* [Dan's Twitter](https://twitter.com/dantwining)

<br />
<br />

## [Ivan Pedrazas](https://twitter.com/ipedrazas?s=20)
### Kubernetes , Gitops and ... Whatever
Ivan covered the following:  
* What, Why Kubernetes?
* Should I use Kubernetes 
* The talk was a mixture of best practices 
* Architecture of Kubernetes (APIs)
* Application Development
* Sarcasm 
 
What is Kubernetes?
The way Kubernetes was explained was by explaining API (Application Program Interface) & RESTful API which is all about moving state from location A to location B whereas Kubernetes is all about moving objects. 
Kubernetes is a container orchestrator. Kubernetes contains three sections 
1.	API
2.	State
3.	Compute
 
Why would you use Kubernetes over other orchestration tools?  
* Clear interfaces
* Clear primitive's
* Control pattern 
* UNIX pattern dashboard
* A complete tool with additional features. 
 
Above/Under API?
* Within Container everything happens our applications, scripts
* The application defines the stateful set here.
* We have a persistent volume claim and a persistent volume
* Before we never had persistent volume claims we just had pods and volumes
* Now we have an object in between to-do certain things.
* Above would be considered as Dev (YAML)
* Under as Ops (BASH)
 
 
The important thing is to understand the separation of concerns  
POD (What we run)<-- ReplicaSet (How many instances)<-- Deployment (How to update the instances)

One important thing Ivan mentioned was that you need to know how to upgrade your Kubernetes Cluster, you need to have a plan. Don’t rely on tools to upgrade your Cluster kubernetes such as GKE (Google Kubernetes Engine).  

What is GitOps?  
* Operations by pull request   
* Everything has to change by pull request  
 
Why is GitOps Important & Why should you use it?  
* Declaring all state of world in Git for everyone to see
* If someone changes, we all know
* GitOps makes your workflow far more efficient
* GitOps makes passing SOC 2 compliance far more cost-efficient
* Increased Productivity with CD automation
* Audit log of all changes
* Revert/rollback features
* Consistency and standardisation of end-to-end workflows
 
Challenges GitOps:  
1.	People will push back:  
* Developer
* CAB members
* Approvers
2.	Processes have to be :
* Implemented 
* Automated


### Links:
* [Ivan's Twitter](https://twitter.com/ipedrazas)
* [Kubernetes , Gitops and ... Whatever - Slides](http://ceur-ws.org/Vol-2382/ICT4S2019_paper_28.pdf)
* [Using Kubernetes - Video](https://www.youtube.com/watch?v=iJ67I4g5y2k&t=350s)


## Who is this for
We aim to build a community for discussion and support and will welcome anyone that wants to attend.


## Food & Drinks
As always, thanks to [DevOpsGroup](https://www.devopsgroup.com/), food and drinks will be provided. If you have any special dietary requirements, please let us know.

## Prizes
- 1 Raspberry Pi 
- 2 JetBrains license, thanks to [jetBrains](https://www.jetbrains.com/)


## Feedback / Content
Please contact either of the organisers if you want to:

* Give a talk
* Get more information regarding the Meetup
* Talk about sponsorship
* Any other suggestions or support

Please drop us a message on twitter [@CloudNativeWales](https://twitter.com/CloudNativeWal) or email us on info@cloudnativewales.io