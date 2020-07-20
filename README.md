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
1. [Getting started](#getting-started)
1. [Running the tests](#running-the-tests)
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

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```bash
dnf install wget
wget http://www.example.com/install.sh
bash install.sh
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, for example

```bash
export TOKEN="fffd0923aa667c617a62f5A_fake_token754a2ad06cc9903543f1e85"
export EMAIL="jane@example.com"
dnf install npm
node samplefile.js
Server running at http://127.0.0.1:3000/
```

And repeat

```bash
curl localhost:3000
Thanks for looking at Code-and-Response!
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why, if you were using something like `mocha` for instance

```bash
npm install mocha --save-dev
vi test/test.js
./node_modules/mocha/bin/mocha
```

### And coding style tests

Explain what these tests test and why, if you chose `eslint` for example

```bash
npm install eslint --save-dev
npx eslint --init
npx eslint sample-file.js
```

## Project Svādhyāya

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/)

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

