# Always-On Security

> A research and engineering project focused on building a container-native, multi-layer security platform for high-performance computing (HPC) and air-gapped environments.

The **Always-On Security** organization contains the source code and supporting resources for a complete security monitoring and automated response platform designed around modern containerized infrastructure.

The platform combines telemetry from multiple independent security layers—including container runtime events, kernel activity, passive network monitoring, and infrastructure integrity—to provide real-time threat detection, risk correlation, automated enforcement, and security operations visibility.

---

## Repositories

### 🚀 Always-On-Security

The primary project repository containing the complete platform implementation.

Features include:

* Multi-source security telemetry collection
* Runtime threat detection
* Risk scoring and correlation engine
* Automated response and remediation
* Human-in-the-loop approval workflow
* Next.js SOC dashboard
* Build-time security pipeline
* Attack simulation framework

This repository contains everything required to build, deploy, and run the platform.

---

### 📚 Always-On-Security-Resources

Supporting documentation and reference material for contributors.

Contents include:

* Project documentation
* Design notes
* Architecture references
* Setup guides
* Development resources
* Research material
* Learning resources used throughout development

This repository exists to keep supporting material separate from the production codebase.

---

## Repository Structure

```text
Always-On Security Organization
│
├── Always-On-Security
│   ├── Platform source code
│   ├── Dashboard
│   ├── Risk Engine
│   ├── Controller
│   ├── Security Monitor
│   ├── Host Observer
│   └── Deployment
│
└── Always-On-Security-Resources
    ├── Documentation
    ├── Architecture
    ├── Development Guides
    ├── Research
    └── Reference Material
```

---

## Getting Started

If you're new to the project:

1. Explore the **Always-On-Security-Resources** repository to understand the architecture and development workflow.
2. Clone the **Always-On-Security** repository.
3. Follow the setup instructions in its README.
4. Launch the platform using Docker Compose.
5. Begin exploring the dashboard and attack simulation features.

---

## Project Goals

The platform is built around several core principles:

* Defense in depth
* External, infrastructure-based monitoring
* Zero trust toward workload containers
* Automated threat detection and response
* Human-assisted decision making for high-impact incidents
* Secure-by-default development and deployment

---

## Contributing

Contributions are welcome.

Please:

* Open an issue before proposing major changes.
* Follow the project's coding standards.
* Ensure all CI checks pass before submitting a pull request.
* Keep documentation up to date alongside code changes.
