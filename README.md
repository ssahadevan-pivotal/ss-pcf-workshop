# Pivotal Cloud Foundry (PCF) & Spring Workshop
## Pivotal Software and Perficient St. Louis
Join Pivotal for a hands-on workshop to introduce key concepts in modern cloud-native application development and delivery. This workshop will introduce concepts of cloud-native, Spring and .Net application development, container workload deployments with [Pivotal Cloud Foundry](https://pivotal.io/platform), as well as application monitoring with PCF Metrics and platform monitoring with PCF Healthwatch. The labs will leverage Spring Boot 2.0, Spring Actuator, Spring Cloud Data Flow for PCF, and other PCF 2.0 topics.

## Topics
- PCF 2.0 with Pivotal Application Service (PAS) and Pivotal - Container Service (PKS) Overview
- Spring Boot 2.0 apps dev and Spring Actuator
- Application deployment on PAS

_This workshop is intended for: Managers, Architects, Developers, Operators and Infrastructure teams to learn about cloud-native architecture and Pivotal Cloud Foundry._

## Events of Interest
- [SpringOne Tour by Pivotal](https://springonetour.io/), [St. Louis May 30-31 at T-Rex](https://springonetour.io/2018/st-louis). Cloud-Native Java From the Source: The SpringOne Tour brings the best Cloud-Native Java content from our flagship conference directly to you. In 2 days, you’ll learn about both traditional monolithic and modern, Cloud-Native Java from the source. Experience valuable facetime with expert Pivotal speakers in both traditional presentation and informal open space discussions about modern Application Development, DevOps, CI/CD, Cloud and more.
- Stay informed for the [2018 SpringOne Platform by Pivotal](https://springoneplatform.io/) to be held in Sept. 24-27 in Washington, D.C.
- Join Perficient and Pivotal at [Gateway to Innovation](https://www.g2iconference.com).  
Meet the team and hear from our clients at our co-sponsored session: [Unleash Innovation with Application Modernization](https://www.g2iconference.com/agenda/session/186985).  
*Topic*: Find out how leading enterprise organizations are shifting their traditional business practices by leveraging cloud-based platforms to extend the value of legacy applications, accelerate speed to market, increase profits, and unleash innovation.  
*With Speakers*: Vijay Sankaran (CIO, TD Ameritrade), Dormain Drewitz (Senior Director of Product and Customer Marketing, Pivotal), Steve Helms (Director of Enterprise Integration, First National Bank - FNBO), Mark Munsell (Deputy CIO, National Geospatial-Intelligence Agency - NGA)
- ...

https://www.g2iconference.com/agenda/session/186985

## Agenda

Time | Session
---- | -------
11:00AM - 12:00 AM | _Introductions, Voice of the Customer
12:00PM - 1:00 PM  | _Lunch_
01:00PM - 2:00 PM  | _Session 1: PCF 2.0 Overview*_
02:00PM - 3:00 PM  | _Session 2: Labs
03:00PM - 4:00 PM  | _Session 3: Spring Boot and Actuator with Lab_
4:10 PM - 4:30 PM | _Wrap-up, Q&A

_*with Pivotal Application Service (PAS) and Pivotal Container Service (PKS)_

**Notes** 

> See [Course Materials](#course-materials) section below for slides and labs
>
> This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material.
>
> The lectures for this workshop are generally light and are only intended to set the stage for the hands-on labs.
> The overwhelming majority of our time will be spent engaging with the technology directly!

## Getting started

**Prerequisites**

Start by downloading and installing the appropriate prerequisite tools.
- [Cloud Foundry CLI](https://goo.gl/M0pH4i) to interact with a cloud foundry instance
- [Apache Maven](http://info.pivotal.io/HI002010A6ZlRJR1NeU00eC) to build labs using Maven
- [Gradle](https://services.gradle.org/distributions/gradle-3.1-all.zip) to build labs using Gradle
- [Git Client](https://git-scm.com/downloads) to clone Github repo or download and unzip
- An IDE, like [Spring Tool Suite](https://spring.io/tools/sts/all) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Java SE Development Kit](http://info.pivotal.io/n0I60i3021AN0JU0le10CRR)

**Download materials**

Next, download the course materials.  This can be accomplished either through the GitHub website by downloading a repository zip and unzipping locally, or if you have Git installed, use the following commands:

```
$ git clone https://github.com/cbusch-pivotal/pivotal-perficient-stl-workshop
$ cd pivotal-perficient-stl-workshop/
```

**PCF Environments**

Finally, in order to perform the labs, you must be connected or logged into a live PCF environment. Initially you were asked to create a Pivotal Web Services (PWS) account for use in labs and afterwards. Two other environments have also been made available for use. Please see the [Pivotal Cloud Foundry Environment document](common/env_info.md) for details. You should have been assigned a student number and PCF instance at registration. Otherwise the instructors will provide that information for your use.

## Course Materials

#### _Session 1: PCF 2.0 Overview with PAS and PKS_ [(Slides)](session_01/PCF-PAS-PKS-Overview.pptx)

#### _Session 2: PCF Application Deployment Labs_
  - [Lab 1 - From Zero to Pushing Your First Application](session_02/lab_01/lab_01.adoc)
  - [Lab 2 - Binding to Cloud Foundry Services](session_02/lab_02/lab_02.adoc)
  - [Lab 3 - Scaling Applications with Apps Manager](session_02/lab_03/lab_03.adoc)


#### _Session 3: Spring Boot 2.0 and Actuator_ [(Slides)](session_03/Spring-Boot-20-and-Actuator.pptx)
  - [Lab 4 - Spring Boot Actuator Lab](session_03/lab_04/lab_04.adoc) 

#### _Wrap-up, Q&A, Course evaluation_ [(Slides)](session_wrapup/Session_Wrap-Up.pptx)

## The Team

### Instructors
- **Sharath Sahadevan** - Pivotal - Platform Achitect, ssahadevan@pivotal.io

### Hosts
- **Jason Foster** - Pivotal Account Executive, jfoster@pivotal.io
...
