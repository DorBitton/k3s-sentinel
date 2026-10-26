# k3s-sentinel

A lightweight, cloud-native diagnostic agent and automation service written in Go for local Kubernetes (k3s) clusters.

## Overview

`k3s-sentinel` runs as an in-cluster platform agent to inspect cluster health, monitor workload conditions, and provide triage insights. It is developed iteratively to study Go systems programming and Kubernetes operational internals.

## Repository Layout

* `cmd/sentinel/`: Entry point for the main sentinel daemon.
* `deploy/k8s/`: Kubernetes manifests (Pods, Services, ConfigMaps, PVCs).
* `pkg/`: Internal Go packages for health checking, storage, and cluster inspection.

## Quickstart

Run locally:
```bash
go run ./cmd/sentinel
```

Run tests:
```bash
go test ./...
```
