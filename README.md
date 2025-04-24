# workshop
# test-argo

Sample application for ArgoCD deployment

## Kubernetes Application

This application was created using the Backstage Kubernetes Application Template. 

## Deployment

The Kubernetes manifests are located in the `k8s` directory and will be deployed by ArgoCD.

## Configuration

- Application Name: test-argo
- Team: Edi
- Container Image: nginx:latest
- Replicas: 1
- Custom Label: my-awesome-app