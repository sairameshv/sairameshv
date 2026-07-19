# Sai Ramesh Vanka (@sairameshv)

**Senior Software Engineer at Red Hat | Kubernetes Contributor**

Platform engineer working on Kubernetes infrastructure, focusing on Dynamic Resource Allocation for GPU/accelerator scheduling, AI inference platform enablement, and node-level platform configuration. Contributing to upstream Kubernetes, CNCF projects, and OpenShift platform components.

---

## Key Projects

### Dynamic Resource Allocation (DRA) for Kubernetes
Contributing to upstream Kubernetes DRA implementation and downstream OpenShift enablement for GPU multi-tenancy.

**Upstream (kubernetes/kubernetes):**
- KEP-5004 (DRAExtendedResources): upgrade/downgrade e2e tests ([#136568](https://github.com/kubernetes/kubernetes/pull/136568)), race condition fix in quota test ([#139085](https://github.com/kubernetes/kubernetes/pull/139085))
- Global cache for DeviceClass-to-extended-resource mapping ([#134326](https://github.com/kubernetes/kubernetes/pull/134326))
- DRA integration test fixes ([#137432](https://github.com/kubernetes/kubernetes/pull/137432))
- KEP-5004 test planning for rollout/upgrade/rollback ([kubernetes/enhancements#5751](https://github.com/kubernetes/enhancements/pull/5751))

**Downstream (OpenShift):**
- Enabled DRA featuregate by default in OpenShift API ([openshift/api#2498](https://github.com/openshift/api/pull/2498))
- DRA e2e tests for NVIDIA GPU hardware ([openshift/origin#30758](https://github.com/openshift/origin/pull/30758))
- KEP-4815 Partitionable Devices e2e tests ([openshift/origin#31230](https://github.com/openshift/origin/pull/31230))
- CI infrastructure for DRA validation on NVIDIA GPU

### InstaSlice (DAS) Operator
Core contributor to production GPU slicing operator enabling multiple AI/ML workloads to share GPU hardware through fine-grained MIG-based resource allocation.

- Operator maintenance: CVE remediation, libnvidia-ml updates, production hardening
- Release pipeline management via Konflux/Tekton across OCP 4.18-4.21
- E2E testing infrastructure across KIND, OpenShift SNO, and multi-GPU clusters
- Repository: [openshift/instaslice-operator](https://github.com/openshift/instaslice-operator)

### DRA OCP Validator Plugin
Building a Claude Code plugin for automated DRA validation on OpenShift clusters.
- Repository: [openshift-eng/ai-helpers#520](https://github.com/openshift-eng/ai-helpers/pull/520)

### OpenShift Node Infrastructure
Drove node-level platform features across Machine Config Operator, Cluster Node Tuning Operator, CRI-O, and OpenShift API.

- **Cgroups v1 to v2 migration:** Built controller support for cgroup mode switching and led the platform-wide migration (2022-2026)
- **Cgroups v1 deprecation:** Removed cgroupv1 code paths across MCO, NTO, and OpenShift API ([MCO#5399](https://github.com/openshift/machine-config-operator/pull/5399), [NTO#1428](https://github.com/openshift/cluster-node-tuning-operator/pull/1428), [API#2579](https://github.com/openshift/api/pull/2579))
- **Worker Latency Profiles:** Node configuration controller for latency-sensitive edge computing deployments
- **Evented PLEG:** CRI-O and kubelet integration for event-driven Pod Lifecycle Event Generator, replacing the polling-based approach

---

## Open Source Contributions

**169+ merged PRs** across upstream Kubernetes, CRI-O, and OpenShift platform components.

Member of: [kubernetes](https://github.com/kubernetes) | [kubernetes-sigs](https://github.com/kubernetes-sigs) | [openshift](https://github.com/openshift) | [cri-o](https://github.com/cri-o)

| Repository | Focus |
|------------|-------|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) | DRA e2e testing, KEP-5004, performance improvements |
| [kubernetes/enhancements](https://github.com/kubernetes/enhancements/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) | KEP-5004 test planning |
| [kubernetes-sigs/jobset](https://github.com/kubernetes-sigs/jobset/pulls?q=is%3Apr+author%3Asairameshv) | DRA integration documentation |
| [openshift/origin](https://github.com/openshift/origin/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) | DRA & GPU e2e testing |
| [openshift/instaslice-operator](https://github.com/openshift/instaslice-operator/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) | GPU slicing operator |
| [cri-o/cri-o](https://github.com/cri-o/cri-o/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) | Evented PLEG, CI improvements |

---

## Conference Demos

| Event | Topic |
|-------|-------|
| **KubeCon + CloudNativeCon India 2026** (Mumbai) | Multi-Tenancy of AI Inference Workloads on OpenShift using llm-d and DRA — Red Hat Booth Demo |
| **KubeCon India 2025** | InstaSlice (DAS) - GPU Slicing for AI/ML Workloads — Red Hat Booth Demo |

---

## Technologies

`Go` `Kubernetes` `OpenShift` `DRA` `NVIDIA MIG` `llm-d` `vLLM` `GPU Operator` `CRI-O` `Helm` `Kustomize` `Prow` `Tekton` `Konflux` `GCP`

---

## Connect

- **GitHub**: [@sairameshv](https://github.com/sairameshv)
- **LinkedIn**: [linkedin.com/in/sai-ramesh-vanka](https://linkedin.com/in/sai-ramesh-vanka)
- **Email**: svanka@redhat.com

---

*Building production infrastructure for Kubernetes platforms and contributing to the cloud-native ecosystem.*

---

*Last updated: July 19, 2026*
