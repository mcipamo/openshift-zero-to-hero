# 🚀 OpenShift Zero to Hero

![License](https://img.shields.io/github/license/<your-user>/openshift-zero-to-hero?color=red)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-green.svg)
![OpenShift](https://img.shields.io/badge/OpenShift-4.x-red)
![ROSA HCP](https://img.shields.io/badge/ROSA-HCP-blue)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

> **A complete hands-on learning path to master OpenShift — from zero to expert.**  
> Covers containers, Kubernetes, OpenShift administration, Operators, GitOps, and Red Hat OpenShift Service on AWS (ROSA HCP).

---

## 🧭 Overview

This repository is a **comprehensive, modular course** designed to guide learners from foundational container concepts to advanced OpenShift operations.  
Each module combines **theory, hands-on labs, and real-world scenarios** based on Red Hat best practices.

The course evolves through **progressive complexity**:
1. **Container Fundamentals**
2. **Kubernetes Core**
3. **OpenShift Administration**
4. **Operators & GitOps**
5. **ROSA Hosted Control Planes (HCP)**

---

## 🧱 Repository Structure

```bash
openshift-zero-to-hero/
├── syllabus/       # Theory modules in Markdown
├── labs/           # Hands-on exercises and guided labs
├── examples/       # YAMLs, manifests, and templates
├── assets/         # Images, diagrams, and media
├── scripts/        # Utility scripts for lab automation
├── docs/           # Extra documentation and glossary
└── .github/        # GitHub Actions and templates
````

---

## 📘 Learning Path

| Module                                                   | Title                                | Description                                                                       |
| -------------------------------------------------------- | ------------------------------------ | --------------------------------------------------------------------------------- |
| 🧩 [00](syllabus/module-00-environment-setup.md)         | **Introduction & Environment Setup** | Install required tools, configure your workspace, and prepare your environment.   |
| 🐳 [01](syllabus/module-01-containers-basics.md)         | **Container Basics**                 | Understand what containers are and build your first images using Podman.          |
| 📦 [02](syllabus/module-02-images-and-tools.md)          | **Images & Registries**              | Learn about image layers, tagging, pushing to registries, and multi-stage builds. |
| ☸️ [03](syllabus/module-03-kubernetes-fundamentals.md)   | **Kubernetes Fundamentals**          | Explore pods, deployments, services, and core orchestration concepts.             |
| 🏗️ [04](syllabus/module-04-openshift-core-concepts.md)  | **OpenShift Core Concepts**          | Dive into Projects, Routes, Builds, and SCCs.                                     |
| 🌩️ [05](syllabus/module-05-rosa-hcp-basics.md)          | **ROSA Hosted Control Planes (HCP)** | Understand the architecture and lifecycle of HCP clusters.                        |
| 🛡️ [06](syllabus/module-06-security-rbac-networking.md) | **Security, RBAC & Networking**      | Manage users, policies, and secure cluster communication.                         |
| ⚙️ [07](syllabus/module-07-observability-monitoring.md)  | **Observability & Monitoring**       | Metrics, logging, alerts, and troubleshooting practices.                          |
| 🧬 [08](syllabus/module-08-operators-and-olm.md)         | **Operators & OLM**                  | Automate lifecycle management through Operators.                                  |
| 🔁 [09](syllabus/module-09-gitops-and-ci-cd.md)          | **GitOps & CI/CD**                   | Implement automation pipelines using ArgoCD and Tekton.                           |
| 🧠 [10](syllabus/module-10-advanced-troubleshooting.md)  | **Advanced Troubleshooting**         | Deep dive into cluster health, node recovery, and incident response.              |
| 🏁 [11](syllabus/module-11-certifications-and-labs.md)   | **Final Labs & Certification Guide** | Practice and prepare for real OpenShift certifications.                           |

---

## 🧪 Labs

Hands-on exercises are located under the [`/labs`](labs/) directory.
Each lab includes:

* Step-by-step commands
* Validation outputs
* Cleanup instructions
* Real OpenShift scenarios (deployments, networking, scaling, etc.)

Example:

```bash
labs/lab01-podman-intro/
├── README.md
├── Containerfile
└── app.py
```

---

## 🧰 Requirements

Ensure your environment includes:

| Tool               | Description             | Install                                                                             |
| ------------------ | ----------------------- | ----------------------------------------------------------------------------------- |
| `git`              | Version control         | `sudo dnf install git -y`                                                           |
| `podman`           | Container engine        | `sudo dnf install podman -y`                                                        |
| `oc`               | OpenShift CLI           | [Install here](https://mirror.openshift.com/pub/openshift-v4/clients/oc/latest/)    |
| `crc` *(optional)* | Local OpenShift cluster | [CodeReady Containers](https://developers.redhat.com/products/codeready-containers) |

---

## 🧑‍💻 Contributing

Contributions are welcome!
If you'd like to improve or expand a module:

1. Fork this repository
2. Create a feature branch
3. Submit a pull request following our [contribution guidelines](CONTRIBUTING.md)

---

## 🧩 References

* [OpenShift Documentation](https://docs.openshift.com/)
* [ROSA HCP Documentation](https://docs.redhat.com/en/documentation/red_hat_openshift_service_on_aws/)
* [Podman Documentation](https://podman.io/)
* [Kubernetes Documentation](https://kubernetes.io/docs/)
* [GitHub Pages Docs](https://docs.github.com/en/pages)

---

## 📜 License

This repository is licensed under the [MIT License](LICENSE).
Feel free to use, share, and contribute — attribution appreciated.

---

> “Learning OpenShift is not about memorizing commands — it’s about understanding how Kubernetes becomes enterprise-ready.”
> — *From 0 to Hero*

