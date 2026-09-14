# Argo CD Bootstrap

Argo CD provides the GitOps delivery layer for this repository by comparing the Kubernetes cluster with the configuration stored here.

Git is the source of truth for the desired state. The voting application is deployed from the Helm chart in `helm/voting-app`.

The Application manifest in `applications/voting-app.yaml` is intentionally configured for manual synchronization; it does not install Argo CD or deploy the application by itself.
