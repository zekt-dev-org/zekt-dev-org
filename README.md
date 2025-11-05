# zekt-dev-org
zekt.dev - the ambition is to orchestrate the future &amp; to ease workflow collaboration within or between different Github customer organizations using our offerings. Join the zekt - become a member!

<!-- Optional banner/logo -->
<p align="center">
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/github.svg" width="120" alt="Zekt.dev Logo"/>
</p>

<h1 align="center">🚀 Zekt.dev</h1>

<p align="center">
  <strong>Federated Infrastructure. Standardized Pipelines. Zero Credentials.</strong><br>
  Infrastructure as a Service for modern DevOps teams — secure, API-driven, and cloud-native.
</p>

---

### 🧭 About Us
**Zekt.dev** is redefining how teams provision infrastructure by offering a unified platform that exposes standardized **infrastructure pipelines via API or GitHub integration**.  
We leverage **federated identity (Azure AD / GitHub OIDC)** and **policy-driven automation** to make secure deployments effortless — without managing IaC credentials.

Our vision: **“Deploy anywhere. Govern everywhere.”**

---

### 🧩 What We Build
| Area | Description |
|------|--------------|
| 🧠 **Zekt Core** | The orchestration engine powering API-driven deployments |
| 🌐 **Zekt Portal** | A lightweight web portal for managing environments and tenants |
| ⚙️ **Zekt SDK** | TypeScript SDK for building custom workflows and integrations |
| 🔐 **Identity Mesh** | Secure federation between GitHub, Azure, and cloud-native identities |
| 💸 **FinOps Integration** | Cost visibility and usage insights per deployment and team |

---

### 🧰 Built With
<p align="left">
  <img src="https://img.shields.io/badge/Cloud-Azure-blue?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Node.js-green?logo=node.js" />
  <img src="https://img.shields.io/badge/Infrastructure-Bicep-purple?logo=azurepipelines" />
  <img src="https://img.shields.io/badge/Auth-Azure%20Entra%20ID-blueviolet?logo=microsoft" />
  <img src="https://img.shields.io/badge/CI/CD-GitHub%20Actions-black?logo=githubactions" />
</p>

---

### 🌍 Featured Repositories
| Repo | Description |
|------|--------------|
| [**zekt-core**](https://github.com/zekt-dev/zekt-core) | Core provisioning engine and API |
| [**zekt-portal**](https://github.com/zekt-dev/zekt-portal) | Frontend portal built with Next.js and Tailwind |
| [**zekt-sdk**](https://github.com/zekt-dev/zekt-sdk) | TypeScript SDK for API integration |
| [**zekt-examples**](https://github.com/zekt-dev/zekt-examples) | Quickstart templates and sample workflows |

---

### ⚡️ Quick Start
```bash
# Clone the SDK
git clone https://github.com/zekt-dev/zekt-sdk

# Authenticate using OIDC
zekt login --oidc

# Deploy a resource group
zekt deploy --template azure.bicep
