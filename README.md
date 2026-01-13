# Ansible Enterprise Hardening Platform
An enterprise-grade Ansible automation platform for Linux server provisioning, security hardening, compliance auditing, and drift detection — built with production best practices and CI-enforced quality gates.
This project focuses on clean automation design, security-first configuration, and SRE-level reliability, rather than simple playbook demos.

## Architecture Overview
```
Control Node
        |
        |  SSH (Key-based)
        v
Managed Linux Server
```
