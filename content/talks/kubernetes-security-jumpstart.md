---
title: "Kubernetes Security Jumpstart"
date: 2020-02-08T12:50:59-04:00
draft: false
---

## Pitch

Kubernetes helps with microservice based app problems like scaling, deployment and discovery. But k8s is not a container security tool, and it would be a big mistake to assume that it can defend your apps from security vulnerabilities. We will explore steps we can take towards k8s security.

## Description

Kubernetes makes it possible to run containerized application at scale. It solves many problems of microservice architecture by abstracting away things like container deployment, container-to-container communication, load balancing. While Kubernetes is great at it many things, it seems to be lacking in terms of security. It has some security features but in most respect it is not production grade security, at least not by default.

If you are thinking about or already started with Kubernetes for your production workload, there are some steps you could follow to make sure your environments sand applications is secure.

In this talk we will discuss some best practices for Kubernetes security. From container image to secret management, we will try to cover it all. And after this talk hopefully we will all be in a better position to harden and secure our Kubernetes cluster.
