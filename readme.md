
# Java Tomcat GitOps

Kubernetes deployment configuration for the Java/Tomcat CI/CD learning project.

## Components

- Deployment: java-tomcat-app
- Service: java-tomcat-service
- Namespace: java-tomcat
- Image registry: Docker Hub
- Delivery controller: Argo CD

## Deployment management

Argo CD monitors this repository and reconciles the Kubernetes
resources with the desired state defined in manifests/.
