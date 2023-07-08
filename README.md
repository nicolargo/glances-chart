# Glances Helm Chart

This Helm chart deploys Glances as a web service on a Kubernetes cluster.

## Prerequisites

- Kubernetes 1.12+
- Helm 3+

## Installation

To install the Glances Helm chart, use the following commands:

```shell
# Add the Helm repository
helm repo add glances https://github.com/nicolargo/glances-chart

# Update the Helm repositories
helm repo update

# Install the Glances chart
helm install glances glances/glances-chart

