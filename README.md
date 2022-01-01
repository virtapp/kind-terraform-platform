# kind-data-platform

[![Github commit activity](https://img.shields.io/github/commit-activity/w/feluelle/kind-data-platform)](https://github.com/feluelle/kind-data-platform/pulse)
[![Pre-commit.ci status](https://results.pre-commit.ci/badge/github/feluelle/kind-data-platform/main.svg)](https://results.pre-commit.ci/latest/github/feluelle/kind-data-platform/main)
![CodeQL workflow](https://github.com/feluelle/kind-data-platform/actions/workflows/codeql-analysis.yml/badge.svg)
![Docker workflow](https://github.com/feluelle/kind-data-platform/actions/workflows/docker.yml/badge.svg)
![Terraform workflow](https://github.com/feluelle/kind-data-platform/actions/workflows/terraform.yml/badge.svg)
[![License](https://img.shields.io/:license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

> A kind data platform on your local machine. 🤗

The objective of this project is to be able to quickly setup a data platform on your local machine via kind. It should also help you get familiar with production-ready setup and tools such as terraform, kubernetes and helm.

## 🏛️ Architecture

The following diagram shows the services currently being used, all running in a kind cluster:

![architecture](diagrams/kind-data-platform.png)

## 🚀 Get started

### Prerequisites

Install the following tools:
- [awscli](https://aws.amazon.com/cli/)
- [docker](https://www.docker.com/)
- [kind](https://kind.sigs.k8s.io/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [task](https://taskfile.dev/)
- [terraform](https://www.terraform.io/)



## 📜 Roadmap

You can find what is being worked on and what is to do in the [project](https://github.com/feluelle/kind-data-platform/projects/1).


