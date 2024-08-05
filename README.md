## Deploy a java image using a Helm chart ⚡

To use this repo:
- Modify the values-myapp.yaml to use the image, ports and IPs you want. ArgoCD should point that values-myapp.yaml file.
- The rolebinding is not necessary when ArgoCD has access to the whole cluster. In case of using it, make sure that it addresses the namespace where ArgoCD is installed.

