# Samothrace

An experiment building a microservices framework to build dashboard application on Kubernetes, Docker, Envoy, etc.

## Notes

Design: build on single-node Kubernetes cluster (master and worker is the same node, which is on the local machine) to use Kubernetes pods orchestration mechanism to manage different processes (packaged as containers). Process (i.e. service) is the primary mean for abstraction.
