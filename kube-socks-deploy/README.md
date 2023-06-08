# Project Description

## Deployment on kubernetes
You'll need to access sock shop open source software which is publicly available [Here](https://microservices-demo.github.io)

### Using a cloud provider of your choice then:

- Create a Kubernetes cluster on
- Configure Kubernetes worker instances to use preemptive instances
- Configure Kubernetes autoscaler to keep preemptive instances alive
- Deploy Helm+Tiller onto cluster
- Deploy ingress controller of choice with a Load Balancer
- Deploy socks shop into the Kubernetes cluster
- Configure ingress domain for sock's shop (does not need to use real DNS, just working ingress domain)
- Deploy and configure Prometheus with Kubernetes service discovery to monitor container CPU/memory/network usage and ingress traffic
- Show system health with Grafana

### Bonus points:

- Use of CI/CD solution to deploy the application onto cluster from a Git repo

- Use of Terraform to deploy infrastructure

Let me know if you have any Qs. Thanks! 

## Documentation to use : 

[![Build Status](https://travis-ci.org/microservices-demo/microservices-demo.svg?branch=master)](https://travis-ci.org/microservices-demo/microservices-demo)

# Sock Shop : A Microservice Demo Application

The application is the user-facing part of an online shop that sells socks. It is intended to aid the demonstration and testing of microservice and cloud native technologies.

It is built using [Spring Boot](http://projects.spring.io/spring-boot/), [Go kit](http://gokit.io) and [Node.js](https://nodejs.org/) and is packaged in Docker containers.

You can read more about the [application design](./internal-docs/design.md).

## Deployment Platforms

The [deploy folder](./deploy/) contains scripts and instructions to provision the application onto your favourite platform. 

Please let us know if there is a platform that you would like to see supported.

## Bugs, Feature Requests and Contributing

We'd love to see community contributions. We like to keep it simple and use Github issues to track bugs and feature requests and pull requests to manage contributions. See the [contribution information](.github/CONTRIBUTING.md) for more information.

## Screenshot

![Sock Shop frontend](https://github.com/microservices-demo/microservices-demo.github.io/raw/master/assets/sockshop-frontend.png)

## Visualizing the application

Use [Weave Scope](http://weave.works/products/weave-scope/) or [Weave Cloud](http://cloud.weave.works/) to visualize the application once it's running in the selected [target platform](./deploy/).

![Sock Shop in Weave Scope](https://github.com/microservices-demo/microservices-demo.github.io/raw/master/assets/sockshop-scope.png)

## 