# Sai Ramesh Vanka (@sairameshv)

**Software Engineer at Red Hat | Kubernetes Contributor**

Platform engineer working on Kubernetes infrastructure, focusing on node configuration management, GPU/accelerator resource allocation, and container runtime integration. Contributing to both upstream Kubernetes and OpenShift platform components.

---

## Key Projects

### InstaSlice (DAS) Operator
Core contributor to production GPU slicing operator enabling multiple AI/ML workloads to share expensive GPU hardware through fine-grained resource allocation.

- Core operator implementation and production hardening (security, RBAC, node reboot support)
- E2E testing infrastructure across KIND, OpenShift SNO, and multi-GPU clusters
- **KubeCon India 2025** - Selected for Gold Sponsor In-Booth Demo
- Repository: [openshift/instaslice-operator](https://github.com/openshift/instaslice-operator)

### Dynamic Resource Allocation (DRA) for Kubernetes
Contributing to upstream Kubernetes DRA implementation with focus on testing and quality.

- Upgrade/downgrade e2e test scenarios ([kubernetes/kubernetes#136568](https://github.com/kubernetes/kubernetes/pull/136568))
- Performance optimizations through global caching ([kubernetes/kubernetes#134326](https://github.com/kubernetes/kubernetes/pull/134326))
- Test planning for KEP-5004 ([kubernetes/enhancements#5751](https://github.com/kubernetes/enhancements/pull/5751))

### OpenShift Node Configuration Controller
Built controller infrastructure in Machine Config Operator for centralized management of node-level platform configurations.

- Custom resource controller for cgroup modes, worker latency profiles, and kubelet settings
- Enabled platform-wide features including cgroups v2 migration (2022-2026) and edge computing support
- Repository: [openshift/machine-config-operator](https://github.com/openshift/machine-config-operator/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged)

### Container Runtime Integration
- CRI-O integration for event-driven Pod Lifecycle Event Generator (Evented PLEG)
- Contributed to container runtime support for upstream Kubernetes features
- Repository: [cri-o/cri-o](https://github.com/cri-o/cri-o/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged)

---

## Open Source Contributions

**100+ merged PRs** across upstream Kubernetes, CRI-O, and OpenShift platform components with focus on GPU management, node configuration, and container runtime integration.

- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) - DRA e2e testing, performance improvements
- [kubernetes/enhancements](https://github.com/kubernetes/enhancements/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) - KEP-5004 test planning
- [cri-o/cri-o](https://github.com/cri-o/cri-o/pulls?q=is%3Apr+author%3Asairameshv+is%3Amerged) - PLEG integration, CI improvements

**[Detailed Contribution Analysis](https://gist.github.com/sairameshv/f74ec713a04acd045dc244736a98f4cb)** - Comprehensive technical breakdown and impact summary

---

## Connect

- **GitHub**: [@sairameshv](https://github.com/sairameshv)
- **LinkedIn**: [linkedin.com/in/sai-ramesh-vanka](https://linkedin.com/in/sai-ramesh-vanka)
- **Email**: v.sairamesh1@gmail.com

---

*Building production infrastructure for Kubernetes platforms and contributing to the cloud-native ecosystem.*
