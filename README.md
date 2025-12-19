# Skupper unofficial Helm Chart

This is an unofficial Helm chart for deploying [Skupper](https://skupper.io/) in a Kubernetes cluster.

This chart has been built from the original Skupper chart found at [skupper-helm-chart](https://github.com/skupperproject/skupper/tree/main/charts/skupper) with some modifications to extend functionality and improve usability.

## Features

- Ability to specify image tags for controller, kube-adaptor, and router images.
- Option to set the scope of Skupper deployment (cluster or namespace).

## Installation

To install the chart, use the following command:

```bash
helm install skupper oci://ghcr.io/eryalito/skupper-chart/skupper
```

## Configuration

To customize the installation, you can provide a `values.yaml` file or use `--set` flags. Check the [readme](charts/skupper/README.md) in the `charts/skupper` directory for detailed configuration options.
