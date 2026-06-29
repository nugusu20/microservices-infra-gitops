# Microservices Infra GitOps

This repository contains the infrastructure and GitOps configuration for the DevOps Voting GitOps Lab.

## Planned Structure

- k8s: raw Kubernetes manifests
- helm: Helm charts for the application
- argocd: ArgoCD application definitions
- environments: environment-specific configuration

## Purpose

This repository represents the desired state of the platform.
ArgoCD will later use this repository to deploy and sync the application into Kubernetes.
