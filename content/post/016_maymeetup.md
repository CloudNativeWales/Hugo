---
author: Salman Iqbal
categories:
- meetup
- devopsgroup
- ai wales
- aws south wales
- cardiff
- julien simon
- james strachan
- james rawlings
date: 2019-05-16T09:00:00Z
description: The one when we did a joint meetup with AI Wales & AWS South Wales...
draft: false
featured_image: /images/2019/05/header.jpg
slug: 016_maymeetup
title: 016_MayMeetup.md
---

# OUR THIRTEENTH MEETUP

> Thursday, May 9th, 6pm at Tramshed Tech, Cardiff.

* [Meetup Page](https://www.meetup.com/Cloud-Native-Wales/events/csxbwqyzhbmb/)
* Video (Will be added soon)
* Follow us on twitter [@CloudNativeWal](https://twitter.com/CloudNativeWal)

# The Meetup

For this epic meetup we joined forces with [AI Wales](https://twitter.com/ai_wales) and [AWS South Wales User Group](https://twitter.com/AWSSWalesUG). For the action packed evening we had:
* [Louise Harris](https://twitter.com/louiseharris33)
* [Julien Simon](https://twitter.com/julsimon)
* [Jack Kelly](https://twitter.com/06kellyjac)
* [James Strachan](https://twitter.com/jstrachan) & [James Rawlings](https://twitter.com/jdrawlings)

# Acknowledgements

We have to say a massive thanks to [DevOpsGroup](https://www.devopsgroup.com/) for supporting us and helping us grow the Cloud Native Community in Wales for over a year! They have provided us with a stunning venue for our meetups. All the drinks and food provided by them also goes down well! Head over to their [careers page](https://www.devopsgroup.com/careers/) to check out exciting vacancies.

The organisers of [AI Wales](https://twitter.com/ai_wales) and [AWS South Wales User Group](https://twitter.com/AWSSWalesUG) helped a lot in putting this evening together. So a special thanks to [Jaymie Thomas](https://twitter.com/jaymiethomas), [Matt Lewis](https://twitter.com/m_lewis), [Toby White](https://twitter.com/TobyARTIMUS) and [David Pugh](https://twitter.com/DavidPugh_DPA). 

Thanks also to [DevOpsGroup](https://www.devopsgroup.com/), [Yolk Recruitment](https://twitter.com/Yolk_Recruit), [Tramshed Tech](https://twitter.com/TramshedTech), [Artimus](https://twitter.com/ARTIMUS_UK) and [Mobilise.Cloud](https://twitter.com/MobiliseCloud) for sponsoring the evening.

### Louise Harris ([@louiseharris33](https://twitter.com/louiseharris33))
#### Free Digital Apprenticeships in Cardiff

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

Working yourself you would train the model on your machine and after you have tested it you will end up deploying it on a Virtual Machine in the cloud. Good points: simple setup. Not so good points: does not scale, manual work, monolithic architecture. Julien then showed a demo of running an EC2 instance (AWS Virtual machine) with [AWS Deep Learning AMI](https://aws.amazon.com/machine-learning/amis/).

*More customers, more team members, more models*

Scalability, high availability & security are now a must. You opt to scale out and implement all the good DevOps practices, Infrastructure as Code, Continuous Integration, Continuous Deployment etc. Julien presented the following three options: 

1: _More Virtual Machines_  
First option you have is *more* Virtual Machines. Good points: might give you the scaling. Not so good points: Infrastructure setup requires a lot of effort.

2: _Docker Clusters_  
You can containerise your models using [Docker](https://www.docker.com/) and run them either on Elastic Container Service or Amazon Elastic Container Service for Kubernetes (Amazon EKS). Gives you options on scaling however it is still not fully managed so you will have to maintain the services. We then got to see a demo on ECS cluster that was running Tensorflow training and prediction.

3: _SageMaker_  
[SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html) is AWS' fully managed machine learning service. This service allows data scientists to build & train ML models and deploy them to production ready fully managed servers at any scale. We got to see SageMaker in action. This solution requires no infrastructure with minimal setup effort for ML. 

![Options Comparison](/static/images/2019/05/sagemakercomp.png)

Julien concluded with his thoughts saying that you should implement a solution that works for your requirements and should not over-engineer it for the future.

If you would like to learn more, head over to:  
https://aws.amazon.com/sagemaker  
https://github.com/aws/sagemaker-python-sdk  
https://github.com/awslabs/amazon-sagemaker-examples   

### Jack Kelly ([@06kellyjac](https://twitter.com/06kellyjac))
#### Rust & a brand new [Meetup](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/) in Cardiff!

Jack Kelly is a graduate engineer at [DevOpsGroup](https://twitter.com/DevOpsGroup). Jack gave a lightning talk on [Rust](https://www.rust-lang.org/). He spoke about its in increasing popularity in the tech community and highlighted a number of project on the [CNCF Landscape](https://landscape.cncf.io/) that are use Rust. 

Jack highlighted some of the features of the languages such as performance and reliability and how it compares to other languages. 

Jack also announced the newly formed Rust & C++ Cardiff meetup! Head over to their [meetup page](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff/), join and show them some love!

Head over to Jack's [GitLab](https://gitlab.com/06kellyjac) & [GitHub](https://github.com/06kellyjac) repos to see the projects that he is working on. 

![Rust C++ Meetup](/static/images/2019/05/rust.jpeg)


### James Strachan ([@jstrachan](https://twitter.com/jstrachan)) & James Rawlings ([@jdrawlings](https://twitter.com/jdrawlings))

What is happening when you see two men, both named James, crossing their arms over their chests to make 'X' sign :no_good:

![JenkinsX time](/static/images/2019/05/jamesx.jpeg)

*That's right, it's [**Jenkins X**](https://jenkins-x.io/) time!*

We were lucky to have [James Strachan]((https://twitter.com/jstrachan)) and [James Rawlings](https://twitter.com/jdrawlings)), co-creators of [*Jenkins X*](https://jenkins-x.io/). Jenkins X is a next generation native Continuous Integration/Continuous Deployment platform for Kubernetes. It should be noted that James Strachan is also the creator of [Apache Camel](https://camel.apache.org/) and [Apache Groovy](http://groovy-lang.org/). The latter language is most commonly dubbed as the *grooviest* language of them all!

James R spoke about the history of [Jenkins](https://jenkins.io/) that there are around 200,000 Jenkins servers running with 15,000,000 Jenkins users. Great tool, however it has some limitations. It can be a single point of failure, the server is memory intensive and is always running. Scaling jobs can lead to issues in Jenkins.

The James' mentioned that if you have worked with [Kubernetes](https://kubernetes.io/), you will have realised that Kubernetes deployments are not straight forwards. Jenkins X is created to abstract Kubernetes and even deployment pipelines. So as a developer, you can focus delivering business functionality. 

James S talked about how according to [2018 State of DevOps Report](https://puppet.com/resources/whitepaper/state-of-devops-report), high performing teams make full use of CI/CD to deliver faster to market and spend less time remediating issues.

That is where Jenkins X steps in to automate your CI+CD, so you can focus on building applications. With Jenkins X all your artifacts are in version control and you can use trunk-based development. 

James S & James R showed Jenkins X in action. Jenkins X can be installed on an existing or new Kubernetes cluster.

To show how easy it is to create an application and deploy to Kubernetes cluster, James R ran the following command:

`$ jx create quickstart`

With a single command, James was able to:
- create a simple node application
- configure github repository for it
- add `Dockerfile` for the app
- add `Jenkinsfile` to implement CI/CD
- [Helm Charts](https://helm.sh/) for Kubernetes deployment

As soon as James pushed the code to Github repository, it deployed to Kubernetes cluster and provided a preview link. You can see the repository [here](https://github.com/cb-kubecd/welovewalesxxx).

James then made a change locally, created a pull request which kicked off a deployment and provided a preview link. Idea being that the team can review and if happy, merge it to a branch of their choice. This would then automatically kick-off a deployment to their production Kubernetes cluster. We got to see how Jenkins X implements a [GitOps](https://www.weave.works/blog/what-is-gitops-really) approach. Some seriously good stuff here! 

Jenkins X is an Open source project and both James encouraged everyone to join the community, learn and contribute to the project. 

If you would like more information head over to the following links:

- [Get started](https://jenkins-x.io/)
- [Feedback](https://jenkins-x.io/community/)
- [Jenkins X Pipelines](https://jenkins-x.io/architecture/jenkins-x-pipelines/)
- [Serverless Apps](https://jenkins-x.io/developing/knative/)

And it seemed like that (pretty much) everyone caught the Jenkins X fever:

![JenkinsX fever](/static/images/2019/05/jenkinsxfever.jpeg)

## Prizes

We were able to give away the following prizes:

- 4 tickets to [Infiniteconf 2019](https://skillsmatter.com/conferences/11187-infiniteconf-2019-the-conference-on-big-data-and-ai), thanks to [Skills Matter](https://skillsmatter.com/)
- 2 JetBrains licenses, thanks to [JetBrains](https://www.jetbrains.com/)
- Bottles of wine & gin, thanks to [Tramshed Tech](https://www.tramshedtech.co.uk/)

We would like to thank [JetBrains](https://twitter.com/jetbrains) for their continued support. 
We would also like to thank [Skills Matter](https://twitter.com/skillsmatter) for providing us with tickets to their awesome conferences for every one of our meetups. Special thanks to [Carla](https://twitter.com/CarlaAtSM), [Sam](https://twitter.com/SamSkillsMatter) & [Nicole](https://twitter.com/NicoleAtSM) from Skills Matter for their support! 

## Feedback / Content

If you would like to:

* Give a talk
* Get more information regarding the Meetup
* Talk about sponsorship
* Any other suggestions or support

Please drop us a message on twitter [@CloudNativeWal](https://twitter.com/CloudNativeWal) or email us on info@cloudnativewales.io

