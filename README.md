# neodash-kind-helm-workflow

GitHub workflow to test the NeoDash Helm chart using Kind cluster

In the workflow, we are using an open-source step that creates a local Kubernetes cluster to test the NeoDash helm chart. To confirm the web app's status, we are using an ingress controller to expose the NeoDash locally within the pipeline and a CURL command to test the URL.
