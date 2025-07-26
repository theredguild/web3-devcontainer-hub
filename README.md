# Web3 DevContainer Hub

Choose the right Web3 development environment for your security needs.

## Quick Selection

| Need | Repository | Launch |
|------|------------|--------|
| **Learning & Prototyping** | [Minimal](https://github.com/theredguild/web3-devcontainer-minimal) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-minimal) |
| **Production Development** | [Secure](https://github.com/theredguild/web3-devcontainer-secure) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-secure) |
| **Enterprise/Compliance** | [Hardened](https://github.com/theredguild/web3-devcontainer-hardened) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-hardened) |
| **Security Analysis** | [Auditor](https://github.com/theredguild/web3-devcontainer-auditor) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-auditor) |
| **Malware Analysis** | [Isolated](https://github.com/theredguild/web3-devcontainer-isolated) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-isolated) |

## What's the Difference?

**Minimal**: Basic setup for learning Solidity. Foundry + Hardhat + OpenZeppelin.

**Secure**: Production-ready with security tools (Slither, Mythril, Manticore). For professional development.

**Hardened**: Enterprise-grade with maximum security hardening. Read-only filesystem, compliance features.

**Auditor**: Forensic analysis environment. Read-only, air-gapped, comprehensive analysis tools.

**Isolated**: Maximum security for analyzing potentially malicious code. Completely air-gapped with severe restrictions.

## Security Comparison

| Feature | Minimal | Secure | Hardened | Auditor | Isolated |
|---------|---------|--------|----------|---------|----------|
| **Development** | Full | Full | Full | None | None |
| **Security Tools** | None | Complete | Complete | Professional | Basic |
| **Container Security** | Basic | Standard | Maximum | Maximum | Extreme |
| **Network Access** | Full | Full | Limited | None | None |
| **File Modification** | Yes | Yes | Limited | No | No |

## Getting Started

1. Pick your environment from the table above
2. Click the launch badge or visit the repository
3. Everything is pre-configured and ready to use

Each environment includes comprehensive documentation and deployment guides.