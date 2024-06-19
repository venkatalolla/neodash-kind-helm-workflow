# neodash-kind-helm-workflow
Github workflow to test the NeoDash Helm chart using Kind cluster

In the workflow, we are using a kind opensource step that creates a local Kubernetes cluster to test the NeoDash helm chart. In order to confirm the web app status, we are using ingress controller to expose the NeoDash locally within the pipeline and using CURL command to test the URL.