# Contacts - Kubernetes Dashboard

"The lens-free view of your clusters."

Contacts is a Docker-based web application that provides a Kubernetes dashboard inspired by Lens, but browser-based and less laggy.

## Key Features

- View Kubernetes resources (namespaces, pods, services, deployments)
- Support for both local kubeconfig and in-cluster modes
- Multi-cluster support via kubeconfig contexts
- Dockerized deployment using Docker Compose
- RBAC setup for secure access

## Tech Stack

- Frontend: Angular
- Backend: .NET 9 Web API
- Kubernetes Client: KubernetesClient (C#)
- Deployment: Docker + Docker Compose

## Project Structure

```
contacts/
├── frontend/          # Angular application
├── backend/           # .NET 9 Web API
├── k8s/               # Kubernetes manifests
├── docker-compose.yml # Docker Compose configuration
└── README.md
```

## Getting Started

Coming soon...

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
