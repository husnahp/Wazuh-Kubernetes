# Wazuh Kubernetes

Deploy a Wazuh cluster with a basic indexer and dashboard stack on Kubernetes

## Local development

To deploy a cluster on your local environment (like Minikube, Kind or Microk8s) read the instructions on [local-environment.md](local-environment.md).
The official documentation did not mention about the creation of pv for wazuh indexer, wazuh manager-master and wazuh manager-worker which is needed for the up and running of statefulsets. This repo have additional directory PV for the creation of pv.
