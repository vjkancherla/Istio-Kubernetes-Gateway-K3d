# Istio with Kubernetes Gateway API on K3D

A guide to running **Istio** using the **Kubernetes Gateway API** on a local **k3d**
cluster, demonstrated with the classic polyglot **Bookinfo** application.

## What's inside

- `istio_kubernetes_gateway_k3d_guide.md` — the full step-by-step walkthrough.
- `bookinfo-gateway.yaml` — the Istio Gateway for Bookinfo.
- `bookinfo-versions.yaml` — the Bookinfo virtual service routing v1/v2/v3.
- `Istio_Bookinfo_Application.png` — architecture diagram.
- `TO-DELETE-istio-with-kubernetes-api.txt` — working notes.

## What you'll learn

- Installing the Istio base chart and `istiod` control plane.
- Installing the Kubernetes Gateway API CRDs.
- Configuring **MetalLB** so `LoadBalancer` services work on k3d.
- Deploying the Bookinfo app and routing through a Gateway.

## Tools covered

- Istio (istiod, Gateway API), MetalLB, Helm, k3d, Kubernetes.

## How to use

Follow `istio_kubernetes_gateway_k3d_guide.md`: install `istio-base` and `istiod`,
add the Gateway API CRDs, set up MetalLB with an IP pool, then deploy Bookinfo and
apply `bookinfo-gateway.yaml`.

## Related

- Istio docs: https://istio.io/latest/docs/
