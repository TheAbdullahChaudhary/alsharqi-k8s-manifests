# Alsharqi Kubernetes Manifests

This repository contains all Kubernetes deployment manifests for Alsharqi services.

## Structure

- `services/` - Application service deployments
- `infrastructure/` - Database and messaging infrastructure  
- `monitoring/` - Grafana, Loki, and monitoring stack

## Usage

Each service has its own YAML file named after the service (e.g., `email-service.yaml`, `workflow-service.yaml`).

## Deployment

Use `kubectl apply -f <service-name>.yaml` to deploy individual services.
