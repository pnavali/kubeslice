# Kubeslice Worker Helm Charts

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


The Slice Operator, also known as a Kubeslice Worker is a Kubernetes Operator component that manages the life-cycle of the KubeSlice related Custom Resource Definitions (CRDs). Please refer to the [documentation](https://kubeslice.io/documentation/open-source/1.3.0/overview/architecture) for more details.

# Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add kubeslice https://kubeslice.github.io/kubeslice/
```

You can then run `helm search repo kubeslice` to see the charts.

## Setting Up Kubeslice Worker

### Install Chart


See [Kubeslice Worker Installation](https://kubeslice.io/documentation/open-source/1.3.0/playground/sandbox) for instructions on istalling worker operator on [`kind`](https://kind.sigs.k8s.io/) for non-production use.

For setting up Worker Operator on other cloud platforms, refer to the [Kubeslice Worker Installation on Cloud](https://kubeslice.io/documentation/open-source/1.3.0/install-kubeslice/yaml/yaml-register-worker-clusters).
For setting up Worker Operator on other cloud platforms, refer to the [Kubeslice Worker Installation on Cloud](https://kubeslice.io/documentation/open-source/1.3.0/install-kubeslice/yaml/yaml-register-worker-clusters).

### Uninstall Chart

Please refer the following Kubeslice Worker [uninstallation](https://kubeslice.io/documentation/open-source/1.3.0/uninstall-kubeslice/) steps.
Please refer the following Kubeslice Worker [uninstallation](https://kubeslice.io/documentation/open-source/1.3.0/uninstall-kubeslice/) steps.

### Upgrading Chart

```console
helm upgrade [RELEASE_NAME] kubeslice/kubeslice-worker [flags]
```

Guide
---
A full and comprehensive documentation is available on our opensource [documentation](https://kubeslice.io/documentation/open-source/) website.
