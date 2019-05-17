---
author: Salman Iqbal
categories:
- meetup
- devopsguys
- ai wales
- aws south wales
- cardiff
- julien simon
- james strachan
- james rawlings
date: 2019-05-16T09:00:00Z
description: The one when we did a joint meetup with AI Wales & AWS South Wales...
draft: true
featured_image: /images/2019/05/header.jpg
slug: 016_maymeetup
title: 016_MayMeetup.md
---

# OUR THIRTEENTH MEETUP

> Thursday, May 9th, 6pm at Tramshed Tech, Cardiff.

* [Meetup Page](https://www.meetup.com/Cloud-Native-Wales/events/csxbwqyzhbmb/)
* Video (Will be added soon)

# The Meetup

For this epic meetup we joined forces with [AI Wales](https://twitter.com/ai_wales) and [AWS South Wales User Group](https://twitter.com/AWSSWalesUG). For the action packed evening we had:
* [Louise Harris](https://twitter.com/louiseharris33)
* [Julien Simon](https://twitter.com/julsimon)
* [Jack Kelly](https://twitter.com/06kellyjac)
* [James Strachan](https://twitter.com/jstrachan) & [James Rawlings](https://twitter.com/jdrawlings)

# Acknowledgements

We have to say a massive thanks to [DevOpsGroup](https://twitter.com/DevOpsGroup) for supporting us and helping us grow the Cloud Native Community in Wales for over a year! They have provided us with a stunning venue for our meetups. All the drinks and food provided by them also goes down well!

The organisers of [AI Wales](https://twitter.com/ai_wales) and [AWS South Wales User Group](https://twitter.com/AWSSWalesUG) helped a lot in putting this evening together. So a special thanks to [Jaymie Thomas](https://twitter.com/jaymiethomas), [Matt Lewis](https://twitter.com/m_lewis), [Toby White](https://twitter.com/TobyARTIMUS) and [David Pugh](https://twitter.com/DavidPugh_DPA). 

Thanks also to [DevOpsGroup](https://twitter.com/DevOpsGroup), [Yolk Recruitment](https://twitter.com/Yolk_Recruit), [Tramshed Tech](https://twitter.com/TramshedTech), [Artimus](https://twitter.com/ARTIMUS_UK) and [Mobilise.Cloud](https://twitter.com/MobiliseCloud) for sponsoring the evening.

### Louise Harris ([@louiseharris33](https://twitter.com/louiseharris33))

Louise Harris, founder and director of [Tramshed Tech](https://www.tramshedtech.co.uk/) and [Big Learning Company](https://www.biglearningcompany.com/) spoke about new digital apprenticeships that are available for free. They are: 

* Digital Application Support Level 3
* Digital Learning Design Level 3
* Social Media & Digital Marketing Level 3
* Information Security Level 3
* Data Analytics Level 4

Keep an eye out on [Big Learning Company](https://www.biglearningcompany.com/) for announcement soon!

### Julien Simon ([@julsimon](https://twitter.com/julsimon))
#### Scale Machine Learning from zero to millions of users

Julien is a Global Technical Evangelist for AI & Machine Learning at [AWS](https://twitter.com/awscloud). Julien spoke about how to train machine learning models and how to take them from development to production. An extremely labour intensive task which seems to be a pain point for many teams running ML models in production.

_Advice no 1: Avoid ML if you can!_ See if your needs are satisfied by calling an existing API by a cloud provider that has pre-trained models. Save yourself a whole lot of pain!

If not, enter *ML*

*One User*

Working yourself you would train the model on your machine and after you have tested it you will end up deploying it on a Virtual Machine in the cloud. Good points: simple setup. Not so good points: does not scale, manual work, monolithic architecture. Julien then showed a demo of running an EC2 instance (AWS Virtual machine) with [AWS Deep Learning AMI](https://aws.amazon.com/machine-learning/amis/)

*More customers, more team members, more models*

Scalability, high availability & security are now a must. You opt to scale out and implement all the good DevOps practices, Infrastructure as Code, Continuous Integration, Continuous Deployment etc. Julien presented the following three options: 

1: _More Virtual Machines_  
First option you have is *more* Virtual Machines. Good points: might give you the scaling. Not so good points: Infrastructure setup requires a lot of effort.

2: _Docker Clusters_  
You can containerise your models using [Docker](https://www.docker.com/) and run them either on Elastic Container Service or Amazon Elastic Container Service for Kubernetes (Amazon EKS). Gives you options on scaling however it is still not fully managed so you will have to maintain the services. We then got to see a demo on ECS cluster that was running Tensorflow training and prediction.

3: _SageMaker_  
[SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html) is AWS' fully managed machine learning service. This service allows data scientists to build & train ML models and deploy them to production ready fully managed servers at any scale. We got to see SageMaker in action. This solution requires no infrastructure with minimal setup effort for ML. 

![Options Comparison](/content/images/2019/05/sagemakercomp.png)

Julien concluded with his thoughts saying that you should implement a solution that works for your requirements and should not over-engineer it for the future.

If you would like to learn more, head over to:
https://aws.amazon.com/sagemaker  
https://github.com/aws/sagemaker-python-sdk  
https://github.com/awslabs/amazon-sagemaker-examples   

### Jack Kelly ([@06kellyjac](https://twitter.com/06kellyjac))

### James Strachan ([@jstrachan](https://twitter.com/jstrachan)) & James Rawlings ([@jdrawlings](https://twitter.com/jdrawlings))


### Prizes

## Who is this for

We aim to build a community for discussion and support and will welcome anyone that wants to attend.

## Feedback / Content

Please contact either of the organisers if you want to:

* Give a talk
* Get more information regarding the Meetup
* Talk about sponsorship
* Any other suggestions or support

