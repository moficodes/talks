---
title: "Knative Serverless Computing on K8s"
date: 2019-07-21T12:50:10-04:00
draft: false
---

## Pitch

Wouldn’t it be nice if as developers we could just focus on our code? That is the promise of serverless. But what if we wanted to leverage our existing kubernetes service and developers? Knative focuses on building these tools and services in a way that elevates the existing Kubernetes experience.

## Description

Kubernetes excels at container scheduling, and offers useful primitives for automating infrastructure. But we’ve noticed that development teams often struggle when they use vanilla Kubernetes for application deployments. By all means, use Kubernetes to push containers all day long. But if you want to push application code — or a function — Kubernetes on its own isn’t enough.

Knative is an open source software layer that helps cloud service providers and enterprise platform operators deliver a serverless experience to developers on any cloud. It’s a way to abstract the operational overhead of deploying and managing workloads that run on K8s and provides a consistent approach so that developers can focus on writing cool code. It also gives build primitives that allows for creating pipelines for building and deploying on Kubernetes from Kubernetes.

In this talk we will learn what Knative is, why it was created and how you can get started.
