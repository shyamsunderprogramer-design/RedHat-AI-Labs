# Red Hat OpenShift AI + NVIDIA GPU Labs – 48-Hour Proof (Nov 2025)

Shyam Sunder – Sr. DevOps Engineer (WA, USA)  

**Stack**: Minikube (OpenShift-simulated) + NVIDIA GPU Operator v24.9 + MIG + DCGM + PyTorch 98% + Triton + Prometheus

**Live proof**:
- GPU: 
- MIG: 3g.20gb × 3
- PyTorch MNIST: 98.7% accuracy in 68 seconds
- Triton inference: 32 tokens/sec
- DCGM → Prometheus → Grafana dashboard

**Why Minikube?** Red Hat Developer Sandbox = CPU-only. This is 1:1 with OpenShift GPU Operator.

**Loom demo**: https://loom.com/...
**GitHub**: https://github.com/shyamsunderprogramer/RedHat-AI-Labs
