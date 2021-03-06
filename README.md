[![Logo][jhipster-image]][jhipster-url]

[![NPM version][npm-image]][npm-url] [![Travis Build Status][travis-image]][travis-url-main] [![Azure DevOps Build Status][azure-devops-image]][azure-devops-url-main] [![Dependency Status][daviddm-image]][daviddm-url]

Greetings, Java Hipster!

本项目 fork 自 generate-jhipster ，用于个性化jhipster 满足一些自定义的需求

完整文档请参考 [https://www.jhipster.tech/][jhipster-url]

在你提交issue之前，请阅读用户指南 [guidelines](/CONTRIBUTING.md#submitting-an-issue)。 如果你提交的issue是一个bug， 在发布之前请使用bug模板。 功能issue或其他issue你可以使用此模板[this template][feature-template].

## 开发使用指南
```bash
git clone https://github.com/XIAOMIOPPO/generator-jhipster.git
npm install
npm link //npm link 会在全局注册软链接链接到 package.json 中的 bin 属性指定的二进制文件的路径
```

##  赞助商
               
               Support this project by becoming a sponsor! [Become a sponsor](https://opencollective.com/generator-jhipster) or [learn more about sponsoring the project](https://www.jhipster.tech/sponsors/).
               
               **Thank you to our sponsors!**
               
               **Gold sponsors**
               
               [![Okta][okta-image]][okta-url]
               
               **Bronze sponsors**
               
               [![ForsysLab][forsyslab-image]][forsyslab-url]
               
               [![CUBA Platform][cubaplatform-image]][cubaplatform-url]
               
               [![Intesys][intesys-image]][intesys-url]
               
               [![CodeFirst][codefirst-image]][codefirst-url]
               
               **Thank you to all our backers!**
               
               [![Backers][backers-image]][backers-url]
               
               ## Azure Builds

Additional builds at [hipster-labs/jhipster-daily-builds](https://github.com/hipster-labs/jhipster-daily-builds)

| Type                 | Status                                                 |
|:---------------------|:-------------------------------------------------------|
| Docker               | [![Build Status][img-docker]][azure-url]               |
| Angular.Maven        | [![Build Status][img-angular-maven]][azure-url]        |
| Angular.Maven.NoSQL  | [![Build Status][img-angular-maven-nosql]][azure-url]  |
| Angular.Gradle       | [![Build Status][img-angular-gradle]][azure-url]       |
| Angular.Gradle.NoSQL | [![Build Status][img-angular-gradle-nosql]][azure-url] |
| React.Maven          | [![Build Status][img-react-maven]][azure-url]          |
| React.Maven.NoSQL    | [![Build Status][img-react-maven-nosql]][azure-url]    |
| React.Gradle         | [![Build Status][img-react-gradle]][azure-url]         |
| React.Gradle.NoSQL   | [![Build Status][img-react-gradle-nosql]][azure-url]   |
| Elasticsearch        | [![Build Status][img-elasticsearch]][azure-url]        |
| Microservices.JWT    | [![Build Status][img-ms-jwt]][azure-url]               |
| Microservices.OAuth2 | [![Build Status][img-ms-oauth2]][azure-url]            |
| Microservices.UAA    | [![Build Status][img-ms-uaa]][azure-url]               |

## Analysis of the sample JHipster project

[![sonar-quality-gate][sonar-quality-gate]][sonar-url] [![sonar-coverage][sonar-coverage]][sonar-url] [![sonar-bugs][sonar-bugs]][sonar-url] [![sonar-vulnerabilities][sonar-vulnerabilities]][sonar-url]

[azure-url]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_build
[img-docker]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Docker.Image
[img-angular-maven]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Angular.Maven
[img-angular-maven-nosql]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Angular.Maven.NoSQL
[img-angular-gradle]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Angular.Gradle
[img-angular-gradle-nosql]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Angular.Gradle.NoSQL
[img-react-maven]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/React.Maven
[img-react-maven-nosql]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/React.Maven.NoSQL
[img-react-gradle]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/React.Gradle
[img-react-gradle-nosql]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/React.Gradle.NoSQL
[img-elasticsearch]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Elasticsearch
[img-ms-jwt]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Microservices.JWT
[img-ms-oauth2]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Microservices.OAuth2
[img-ms-uaa]: https://dev.azure.com/hipster-labs/jhipster-daily-builds/_apis/build/status/Microservices.UAA

[sonar-url]: https://sonarcloud.io/dashboard?id=io.github.jhipster.sample%3Ajhipster-sample-application
[sonar-quality-gate]: https://sonarcloud.io/api/project_badges/measure?project=io.github.jhipster.sample%3Ajhipster-sample-application&metric=alert_status
[sonar-coverage]: https://sonarcloud.io/api/project_badges/measure?project=io.github.jhipster.sample%3Ajhipster-sample-application&metric=coverage
[sonar-bugs]: https://sonarcloud.io/api/project_badges/measure?project=io.github.jhipster.sample%3Ajhipster-sample-application&metric=bugs
[sonar-vulnerabilities]: https://sonarcloud.io/api/project_badges/measure?project=io.github.jhipster.sample%3Ajhipster-sample-application&metric=vulnerabilities
[jhipster-image]: https://raw.githubusercontent.com/jhipster/jhipster-artwork/master/logos/JHipster%20RGB-small100x25px.png
[jhipster-url]: https://www.jhipster.tech/
[npm-image]: https://badge.fury.io/js/generator-jhipster.svg
[npm-url]: https://npmjs.org/package/generator-jhipster
[travis-image]: https://travis-ci.org/jhipster/generator-jhipster.svg?branch=master
[azure-devops-image]: https://dev.azure.com/jhipster/generator-jhipster/_apis/build/status/jhipster.generator-jhipster?branchName=master
[travis-url-main]: https://travis-ci.org/jhipster/generator-jhipster
[azure-devops-url-main]: https://dev.azure.com/jhipster/generator-jhipster/_build
[daviddm-image]: https://david-dm.org/jhipster/generator-jhipster.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/jhipster/generator-jhipster
[backers-image]: https://opencollective.com/generator-jhipster/tiers/backer.svg?avatarHeight=40&width=890
[backers-url]: https://opencollective.com/generator-jhipster
[okta-image]: https://www.jhipster.tech/images/open-collective/okta.png
[okta-url]: https://developer.okta.com/signup?utm_source=JHipster&utm_medium=logo&utm_campaign=Gold-Sponsor
[forsyslab-image]: https://www.jhipster.tech/images/open-collective/forsyslab.jpg
[forsyslab-url]: https://forsyslab.com/
[cubaplatform-image]: https://www.jhipster.tech/images/open-collective/cubaplatform.png
[cubaplatform-url]: https://www.cuba-platform.com/
[intesys-image]: https://www.jhipster.tech/images/open-collective/intesys.png
[intesys-url]: https://www.intesys.it/
[codefirst-image]: https://www.jhipster.tech/images/open-collective/codefirst.png
[codefirst-url]: https://www.codefirst.co.uk
[issue-template]: https://github.com/jhipster/generator-jhipster/issues/new?template=BUG_REPORT.md
[feature-template]: https://github.com/jhipster/generator-jhipster/issues/new?template=FEATURE_REQUEST.md
