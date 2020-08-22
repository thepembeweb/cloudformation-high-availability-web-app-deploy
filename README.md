# Deploy a High-Availability Web App using CloudFormation

> This project demonstrates the deployment of web servers for a highly available web app using CloudFormation. It showcases code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. The project began with deploying the networking components, followed by servers, security roles and software - following best practices and scripting as much as possible.

![](aws-cloudformation.jpg)

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)

## Project Infrastructure Diagram

![](udagram-diagram.jpeg)

## Getting Setup

### Installing project dependencies

```bash
$ pip3 install awscli --upgrade --user
```

### Deployment Instruction for the Infrastructure

```bash
$ ./create.sh stackName infrastructure-params.yml infrastructure-params.json
```

## Built With

* [AWS CloudFormation](https://aws.amazon.com/cloudformation/) - AWS cloud infrastructure resource provisioning service used

## Authors

* **[Pemberai Sweto](https://github.com/thepembeweb)** - *Initial work* - [Deploy a High-Availability Web App using CloudFormation](https://github.com/thepembeweb/cloudformation-high-availability-web-app-deploy)

## License

[![License](http://img.shields.io/:license-mit-green.svg?style=flat-square)](http://badges.mit-license.org)

- This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
- Copyright 2020 © [Pemberai Sweto](https://github.com/thepembeweb).






