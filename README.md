# Lootbot.cloud GitOps Workload Repository
This repository contains the GitOps workload definitions for the Lootbot.cloud platform. 
The workloads are defined using [Kustomize](https://kustomize.io/), and are deployed using [Flux](https://fluxcd.io/).
## Workloads
The workloads are defined in the `workloads` directory. Each workload is defined in a separate directory, and contains a `kustomization.yaml` file that defines the workload.
## Environments
The workloads are deployed to different environments, which are defined in the `environments` directory. Each environment is defined in a separate directory, and contains a `kustomization.yaml` file that defines the environment.
## Deploying Workloads
The workloads are deployed using [Flux](https://fluxcd.io/). Flux is configured to deploy the workloads in the `main` branch of this repository.
Pointing Flux to this repository will cause Flux to deploy the workloads defined in this repository.
