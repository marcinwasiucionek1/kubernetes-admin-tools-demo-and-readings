# kubernetes-admin-tools-demo-and-readings

This repository was created as part of the presentation **Bezpieczeństwo Kubernetesa: Kluczowe narzędzia dla admina do zabezpieczania K8s – must-know w praktyce**, delivered at **Sekurak Cyberstarter 2025**.

It contains a curated collection of resources, tools, and a demo application to help Kubernetes administrators better understand and improve the security posture of their Kubernetes clusters.

> 🌀 **Note:** This is a living repository. It will continue to evolve over time as new tools, practices, and insights emerge in the Kubernetes security space. It is not at its final state yet.

## Repository Structure

### 📚 `readings/`
A curated list of high-quality articles, papers, and documentation focused on Kubernetes security. This collection covers a wide range of topics including:

- Kubernetes and Docker security
- Kubernetes best practices
- Cybersecurity reports
- Attacks analysis

### ⚙️ `tools/`
A list of useful Kubernetes-related tools grouped by security-related categories:

- **Application Code Analysis**  
  (SAST, DAST, dependency checking) — tools for static and dynamic security analysis of code and vulnerability detection in dependencies.

- **Image Security**  
  (image signing, vulnerability scanning) — tools for verifying and securing container images.

- **Kubernetes Manifest Validation**  
  (YAML validation, centralized security policy enforcement) — tools for checking correctness and compliance of Kubernetes configurations and enforcing policies.

- **Secrets Management**  
  (Vault, SOPS, SealedSecret) — tools for securely storing and managing sensitive data.

- **Runtime Security**  
  (threat detection and blocking, cluster configuration validation against best practices, centralized logging and monitoring, CI/CD) — tools for protecting running applications and clusters in real time.

Each tool comes with a brief description and links to documentation or installation instructions.

### 🚀 `demo/`
A simple demo application to illustrate the use of selected Kubernetes security tools in practice. Includes:

- `Dockerfile` for building the container image
- Helm charts for deploying the application
- Vulnerable application code

---

## Contributing

Feel free to explore, use the code, suggest improvements, or contribute new tools, readings, or demos. Contributions are welcome and appreciated!
