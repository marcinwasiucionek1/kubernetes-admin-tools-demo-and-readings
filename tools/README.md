# Kubernetes Security Tools

A curated list of essential Kubernetes tools for securing your clusters and workloads, organized by key security categories.  

> 🚀 [**k9s**](https://k9scli.io/) — A terminal-based UI to interact with your Kubernetes clusters. While not a security tool per se, k9s is invaluable for navigating, inspecting, and troubleshooting Kubernetes resources quickly.

---

## 1. Application Code Analysis  
Tools for Static Application Security Testing (SAST) and dependency vulnerability scanning:

- [**SonarQube**](https://www.sonarqube.org/)  
  A widely-used platform for continuous inspection of code quality and security vulnerabilities through static analysis.

- [**Snyk**](https://snyk.io/)  
  Focuses on finding and fixing vulnerabilities in application dependencies with integrated SAST and container scanning.


Dynamic Application Security Testing:
- [**OWASP ZAP**](https://www.zaproxy.org/)  
  Open-source DAST tool that helps detect runtime security vulnerabilities in web applications.

---

## 2. Image Security  
Tools for container image signing:

- [**Docker Content Trust**](https://docs.docker.com/engine/security/trust/)  
  Provides image signing and verification to ensure the integrity and publisher of container images.

Vulnerability scanning:
- [**Clair**](https://github.com/quay/clair)  
  Static vulnerability scanner for container images that detects known CVEs.

- [**Trivy**](https://github.com/aquasecurity/trivy)  
  Simple and comprehensive vulnerability scanner for container images, filesystem, and Git repositories.

---

## 3. Kubernetes Manifest Validation  
Tools for validating YAML manifests:

- [**kubeval**](https://www.kubeval.com/)  
  Validates Kubernetes YAML files against the Kubernetes JSON schema to catch invalid specs early.

Enforcing security policies: 

- [**OPA (Open Policy Agent) + Gatekeeper**](https://open-policy-agent.org/docs/latest/kubernetes-introduction/)  
  Policy engine for Kubernetes that enforces custom policies via admission controllers.

- [**Kyverno**](https://kyverno.io/)  
  Kubernetes-native policy engine designed specifically for validating, mutating, and generating resources.

---

## 4. Secrets Management  
Tools for securely storing, encrypting, and managing sensitive data:

- [**HashiCorp Vault**](https://www.vaultproject.io/)  
  Centralized secrets management tool with dynamic secrets, encryption as a service, and access control.

- [**SOPS (Secrets OPerationS)**](https://github.com/mozilla/sops)  
  Encrypts files such as YAML and JSON with support for AWS KMS, GCP KMS, and PGP.

- [**Sealed Secrets (Bitnami)**](https://github.com/bitnami-labs/sealed-secrets)  
  Encrypts Kubernetes Secrets into “sealed secrets” which are safe to store publicly and decrypted only by the cluster controller.

---

## 5. Runtime Security  
Tools for real-time threat detection:

- [**Falco**](https://falco.org/)  
  Runtime security tool that detects anomalous behavior in Kubernetes environments using kernel-level auditing.

Cluster configuration auditing:
- [**Kube-bench**](https://github.com/aquasecurity/kube-bench)  
  Checks Kubernetes clusters against the CIS Kubernetes Benchmark for security best practices.

- [**Kube-hunter**](https://github.com/aquasecurity/kube-hunter)  
  Security auditing tool that actively hunts for security weaknesses in Kubernetes clusters.

---

This list aims to give Kubernetes administrators and security engineers a solid foundation of tools to secure their clusters end-to-end.  

## Contributing
Contributions and suggestions are welcome! 
