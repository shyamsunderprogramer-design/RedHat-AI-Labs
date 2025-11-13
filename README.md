# Red Hat OpenShift AI + NVIDIA GPU Labs (Nov 2025 – 48-Hour Build)

By Shyam Sunder – Sr. DevOps Engineer (MA, USA)

**Stack**: Minikube (simulating OpenShift) + NVIDIA GPU Operator v24.9 + MIG + DCGM + PyTorchJob + Triton

**Proof**:
- MIG 3g.20gb enabled on local GPU
- PyTorch MNIST 98% accuracy on GPU
- DCGM metrics in Prometheus
- Triton inference on GPU

**Why Minikube?** Free sandbox is CPU-only; this simulates OpenShift GPU setup.