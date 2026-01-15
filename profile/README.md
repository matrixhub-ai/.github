# MatrixHub

**MatrixHub** is an open-source, private AI model registry. It acts as a drop-in Hugging Face replacement optimized for **vLLM** and **SGLang** at scale.

## 💡 Why MatrixHub?

* **Inference Speed**: "Pull-once, serve-all" caching enables **10Gbps+** distribution to 100+ GPU nodes.
* **Air-Gap Ready**: Seamless model "ferrying" into isolated networks via native `HF_ENDPOINT` support.
* **Private AI model registry**: Unified weight management with **Tag locking** and CI/CD for dev-to-prod consistency.
* **Geo-Sync**: Automated, resumable replication across global data centers for low-latency access.

## 🛠️ Core Features

* **🚀 Distribution**: Transparent HF Proxy, on-demand caching, and direct-to-GPU **NetLoader**.
* **🛡️ Governance**: Multi-tenant RBAC with SSO, audit logging, and malware scanning.
* **🌍 Infrastructure**: S3/NFS support, Kubernetes-native (Helm), and P2P-ready scaling.
  
## Status

Early stage. Core features are under active development.
