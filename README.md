# 🏛️ Web3 DevContainer Hub

A comprehensive collection of secure Web3 development environments designed for different security requirements and use cases.

## 🚀 Quick Selection

| Need | Security Level | Repository | Deploy |
|------|---------------|------------|--------|
| **Learning & Prototyping** | Basic | [MINIMAL](https://github.com/theredguild/web3-devcontainer-minimal) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-minimal) |
| **Production Development** | Standard | [SECURE](https://github.com/theredguild/web3-devcontainer-secure) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-secure) |
| **Enterprise/Compliance** | Enterprise | [HARDENED](https://github.com/theredguild/web3-devcontainer-hardened) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-hardened) |
| **Security Analysis** | Forensic | [AUDITOR](https://github.com/theredguild/web3-devcontainer-auditor) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-auditor) |
| **Malware Analysis** | Maximum | [ISOLATED](https://github.com/theredguild/web3-devcontainer-isolated) | [![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&template_repository=theredguild/web3-devcontainer-isolated) |

## 🎯 Decision Matrix

### 🟢 MINIMAL - Quick Start
**Perfect for:** Learning, education, simple prototypes
- ✅ Beginner-friendly setup
- ✅ Essential Web3 tools only
- ✅ Fast setup and deployment
- ❌ No advanced security features
- ❌ Not suitable for production

**Tools:** Foundry, Hardhat, OpenZeppelin, basic VS Code extensions

### 🟡 SECURE - Production Ready
**Perfect for:** Professional development, team projects, production contracts
- ✅ Industry-standard security practices
- ✅ Comprehensive security toolchain
- ✅ CI/CD ready
- ✅ Team collaboration features
- ⚠️ Moderate security overhead

**Tools:** Full security suite (Slither, Mythril, Manticore), production tooling

### 🟠 HARDENED - Enterprise Grade
**Perfect for:** Financial institutions, high-value protocols, corporate compliance
- ✅ Maximum security hardening
- ✅ Enterprise compliance features
- ✅ Audit logging and traceability
- ✅ Read-only filesystem protection
- ⚠️ Strict security restrictions

**Tools:** Enterprise security suite, compliance monitoring, hardened container runtime

### 🔴 AUDITOR - Read-Only Fortress
**Perfect for:** Security auditors, code analysis, vulnerability research
- ✅ Forensic-grade analysis environment
- ✅ Complete air-gapping
- ✅ Read-only workspace integrity
- ✅ Professional audit toolchain
- ❌ No development capabilities

**Tools:** Static analysis tools, symbolic execution, visual analysis, reporting templates

### ⚫ ISOLATED - Maximum Security
**Perfect for:** Malware analysis, exploit research, zero-trust environments
- ✅ Maximum isolation and containment
- ✅ Resource-restricted environment
- ✅ Complete network isolation
- ✅ Ephemeral analysis workspace
- ❌ Extremely limited functionality

**Tools:** Basic analysis utilities, Python for scripting, minimal forensic tools

## 🔒 Security Comparison

| Feature | MINIMAL | SECURE | HARDENED | AUDITOR | ISOLATED |
|---------|---------|--------|----------|---------|----------|
| **Container Hardening** | ❌ | ✅ | ✅✅ | ✅✅ | ✅✅✅ |
| **Network Restrictions** | ❌ | ❌ | ⚠️ | ✅✅ | ✅✅✅ |
| **Read-only Filesystem** | ❌ | ❌ | ✅ | ✅✅ | ✅✅✅ |
| **Capability Dropping** | ❌ | ✅ | ✅✅ | ✅✅ | ✅✅✅ |
| **Syscall Filtering** | ❌ | ❌ | ✅ | ✅✅ | ✅✅✅ |
| **Resource Limits** | ❌ | ❌ | ⚠️ | ✅ | ✅✅✅ |
| **Development Tools** | ✅✅ | ✅✅ | ✅✅ | ❌ | ❌ |
| **Security Analysis** | ❌ | ✅✅ | ✅✅ | ✅✅✅ | ⚠️ |

## 🛠️ Tool Comparison

| Category | MINIMAL | SECURE | HARDENED | AUDITOR | ISOLATED |
|----------|---------|--------|----------|---------|----------|
| **Core Web3** | Foundry, Hardhat | Full stack | Full stack | Analysis tools | Basic utilities |
| **Security Analysis** | None | Slither, Mythril | Full suite | Professional | Minimal |
| **VS Code Extensions** | 4 basic | 8 security-focused | Enterprise suite | Analysis suite | 4 minimal |
| **Development** | Full capability | Full capability | Full capability | Read-only | None |
| **Deployment** | Yes | Yes | Yes | No | No |

## 📊 Use Case Guide

### 👨‍🎓 **Learning & Education**
- **Choose:** 🟢 MINIMAL
- **Why:** Simple setup, no security complexity, focus on learning fundamentals

### 👨‍💻 **Individual Development**
- **Choose:** 🟡 SECURE
- **Why:** Professional tools with security best practices, production-ready

### 🏢 **Enterprise/Corporate**
- **Choose:** 🟠 HARDENED
- **Why:** Compliance features, audit trails, maximum security hardening

### 🔍 **Security Auditing**
- **Choose:** 🔴 AUDITOR
- **Why:** Forensic integrity, comprehensive analysis tools, read-only protection

### 🦠 **Malware Research**
- **Choose:** ⚫ ISOLATED
- **Why:** Maximum containment, zero-trust analysis, complete air-gapping

## 🚀 Getting Started

1. **Select your tier** using the decision matrix above
2. **Click the deploy button** for instant launch
3. **Follow the README** in your chosen repository
4. **Start developing** with confidence

## ⚡ Alternative Deployment Methods

All repositories support multiple deployment options:

- **GitHub Codespaces**: One-click browser-based development
- **Gitpod**: Alternative cloud development environment  
- **Local VS Code**: Clone and open with Dev Containers extension
- **Docker**: Direct docker run commands (advanced users)

## 🔄 Migration Path

Start with any tier and easily migrate up or down based on changing requirements:

```
MINIMAL → SECURE → HARDENED
                ↙
             AUDITOR ← → ISOLATED
```

Each repository includes migration guides and compatibility notes.

## 🤝 Contributing

This project is maintained by [The Red Guild](https://github.com/the-red-guild). 

- **Security issues**: Report via security@redguild.org
- **Feature requests**: Open issues in the specific repository
- **General questions**: Use discussions in this hub repository

## 📄 License

All repositories are licensed under MIT License, Copyright (c) 2025 The Red Guild.

---

🛡️ **Built for the Web3 security community by The Red Guild** 🛡️