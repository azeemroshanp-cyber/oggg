# Quote Generator API

A lightweight cloud-native service for the IPSR DevOps Hackathon.

## Features
- Cloud-native architecture
- CI/CD pipeline ready
- Auto-scaling simulation
- Observability metrics
- OpenShift deployment

## OpenShift Deployment

### Quick Deploy:
```bash
oc new-app https://github.com/yourusername/quote-generator --strategy=docker
oc expose svc/quote-generator
