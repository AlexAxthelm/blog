---
comments: false
subtitle: Hi, I'm Alex!
title: About me
---

I'm Alex Axthelm. this is my space on the internet.

You can also find me at:

- [https://github.com/AlexAxthelm](https://github.com/AlexAxthelm)
- [https://fosstodon.org/@AlexAxthelm](https://fosstodon.org/@AlexAxthelm)
- [https://linkedin.com/in/aaxthelm](https://linkedin.com/in/aaxthelm)

## Current Work

Professionally, I'm a software engineer, with a history of helping small teams move their data science pipelines along the Software Development lifecycle.

Currently, I do DevOps, System Design, and some data engineering for the [PACTA](https://pacta.rmi.org/) project at [RMI](https://rmi.org/).
Most of my day is some combination of R, shell programming (generally POSIX compliant), with a bit of SQL thrown in for fun.

Some of the interesting work I've been doing there (all ongoing, and in-progress):

- [actions](https://github.com/RMI-PACTA/actions) A collection of reusable Github workflows, mostly centered around R package maitenence, and building docker images that run R packages.
- A collection of R packages that orchestrate our anaysis pipeline, and the docker containers that wrap them.
  - [workflow.pacta.webapp](https://github.com/RMI-PACTA/workflow.pacta.webapp)
  - [workflow.pacta](https://github.com/RMI-PACTA/workflow.pacta),
  - [workflow.pacta.report](https://github.com/RMI-PACTA/workflow.pacta.report)
- [factset_data_loader](https://github.com/RMI-PACTA/factset_data_loader/) (shell-only) A docker image to run FactSet's `FDSLoader64` application, and handle some basic DB maitenence (restore from last backup, dump a new backup after loading). Comes with an Azure Deploy template for quick setup of container instance and a PostgreSQL server.

## Past Work

Previously I worked for the [Indiana Commission for Higher Education](https://www.in.gov/che/) in a mixed role where I did data analysis supporting policy decisions, built dashboards, maintained our longitudinal database, and led a small development team in improving and maintaining a webapp that met FERPA standards.
In that role, I also introduced and championed a transition to Agile methodolgies.

After that, I worked with a contractor for the [US Department of Health and Human Services](https://www.hhs.gov/) on the [Quality Payment Program](https://qpp.cms.gov/about/qpp-overview) as a data engineer. In that role, I was able to establish a containerized development environment, and implemented a transition from PostgreSQL databases to Amazon Redshift.

## Current interests

- Abstraction
  - Services
  - OOP
- Validation
  - JSON Schema
- Reproducibility
  - Docker
