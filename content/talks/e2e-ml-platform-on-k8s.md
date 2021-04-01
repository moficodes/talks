---
title: "E2e Ml Platform on K8s"
date: 2021-04-01T12:33:22-04:00
draft: false
---

## Pitch

ML is becoming a core part of our development lifecycle. As such the DevOps days of tomorrow will need to manage these ML platforms. Kubeflow is an open source solution for ML platform. In this talk I will share how to get an E2E ML platform setup using Kubeflow and DevOps practices

## Description

Kubeflow is a machine learning toolkit for Kubernetes where users can develop, deploy, and manage ML workflows in a scalable and portable manner. Deploying and maintaining it can be a bit tricky since Kubeflow is composed of many components such as notebooks and pipelines and their potential configurations. This makes the barrier to entry to Kubeflow very high and make it difficult for teams to adopt Kubeflow.To help alleviate some of these deployment woes the Kubernetes Kubeflow Operator was created. It automates the deployment, monitoring, and management of Kubeflow as a whole. In this session, users will learn how they can best leverage the Kubeflow Operator to quickly get Kubeflow up and running on their Kubernetes clusters.