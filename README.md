# Istio Kubernetes Gateway (k3d)

Demonstrates exposing the Istio **bookinfo** sample application through the **Istio
Gateway** on a local **k3d** (Kubernetes on Docker) cluster.

## What's inside

- `istio_kubernetes_gateway_k3d_guide.md` — step-by-step guide to deploying Istio
  and a Gateway on k3d.
- `bookinfo-gateway.yaml` — the Istio Gateway + VirtualService wiring.
- `bookinfo-versions.yaml` — the bookinfo workloads across v1/v2/v3 versions.
- `route-reviews-v1.yaml`, `route-reviews-v2.yaml`, `route-reviews-v3.yaml` —
  routing examples for each reviews version.
- `Istio_Bookinfo_Application.png` — architecture screenshot.

## Tools covered

- Istio service mesh — Gateway, VirtualService, DestinationRule
- bookinfo sample application
- k3d for a local Kubernetes cluster

## How to use

Follow `istio_kubernetes_gateway_k3d_guide.md` to bring up the k3d cluster and
deploy the manifests in this folder.
