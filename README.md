# Project Svādhyāya

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Slack](https://img.shields.io/badge/Join-Slack-blue)](https://callforcode.org/slack)

This cloud based solution aims to help young learners, particularly during their self-study sessions. While in doubt on a topic of study, the application enables them to  access reliable information. This also enables them to reach out to their favourite teacher for a more detailed answer.Students can publish their queries or respond to queries posted by other students within their study circle. Moreover, an adaptive BOT(IBM Watson Assistant) is always ready to clarify their doubts on-demand. The BOT learns from student-teacher and student-student interactions over the time. Being part of parent-teacher community, parents can also participate in the process as content approver that are filtered for review by the system. Thus, ensuring students always see a moderated content to avoid any distractions due to profanity.

In a nutshell, objective of Project Svādhyāya is to provide a continuous and an uninterrupted learning experience to students by means of a hyper-localized learning system.

## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The Workflow](#the-architecture)
1. [Long description](#long-description)
1. [Project roadmap](#project-roadmap)
1. [System Overview](#getting-started)
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Contributing](#contributing)
1. [Versioning](#versioning)
1. [Authors](#authors)
1. [License](#license)
1. [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

Part of the World Health Organization's guidance on limiting further spread of COVID-19 is to practice social distancing. As a result, schools in most affected areas are taking precautionary measures by closing their facilities. With school-aged children at home for an indeterminate amount of time,  keeping them engaged, entertained, and on top of their education is important. Most importantly an uninterrupted learning experirnce will help them continue their learning on a dissruptive environment. A teacher best understands its students need. Connecting students with their favourite teacher often helpful during their self-study sessions.

### How can technology help?

Schools and teachers can continue to engage with their students through virtual classrooms, and even create interactive spaces for classes. As parents face a new situation where they may need to homeschool their children, finding appropriate online resources is important as well to ensure contineous learning.

### The idea

It's imperative that learning and creating can continue when educational institutions have to shift the way they teach in times of crises, such as the COVID-19 pandemic. Providing a set of open source tools, backed by IBM Cloud and Watson Services, will enable students to get their queries clarified by experts which causes a roadblock to their study at home.

## Demo video

[![Watch the video](https://github.com/aswinimahanta/Project-Svadhyaya/blob/master/images/Project%20Sv%C4%81dhy%C4%81ya%20-%20Learning%20Continues_Moment.jpg)](https://youtu.be/3YTJAsY6rXc)

## The architecture

![Project Svādhyāya - Student BOT Ineractions](https://github.com/aswinimahanta/Project-Svadhyaya/blob/master/images/Project%20Sv%C4%81dhy%C4%81ya%20-%20Flow%20Diagram.png)

1. The student(user) navigates to website and post their question.
2. Watson Assistant reponds to the questions through its skills
3. Watson Assistant directs the questions to experts(user)
4. Experts(user) communicates to student(user)

## Long description

[More detail is available here](DESCRIPTION.md)

## Project roadmap

![Roadmap](https://github.com/aswinimahanta/Project-Svadhyaya/blob/master/images/Project%20Sv%C4%81dhy%C4%81ya%20Time%20Line.png)

## System Overview

High-level system overview of Project Svādhyāya

### The Concept

![Behind Concepts](https://github.com/aswinimahanta/Project-Svadhyaya/blob/master/images/Project%20Sv%C4%81dhy%C4%81ya%20-%20The%20Concept.png)

### The Technology Stack

![Planned Technology Stack](https://github.com/aswinimahanta/Project-Svadhyaya/blob/master/images/Project%20Sv%C4%81dhy%C4%81ya%20-%20Technology%20Stack.png)

## Live Demo

You can find a running system to test at [project-svadhyaya-simple-client](https://project-svadhyaya-simple-client.us-south.cf.appdomain.cloud/)

## Built with

* [IBM Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - The intelligent chatbot engine
* [IBM Cloud Foundary](https://cloud.ibm.com/cloudfoundry/overview) - The deployment server or cluster
* [Node js](https://cloud.ibm.com/catalog/starters/cloud-foundry?runtime=sdk-for-nodejs) - The web framework used

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [GitHub](https://github.com/) for versioning. For the versions available, see the [tags on this repository](https://github.com/aswinimahanta/Project-Svadhyaya).

## Authors

* **Aswini Mahanta** - *Initial work* - [aswinimahanta](https://github.com/aswinimahanta/)
* **Abinash Ray** - *Initial work* - 

See also the list of [contributors](https://github.com/aswinimahanta/Project-Svadhyaya/graphs/contributors) who participated in this project.

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).

