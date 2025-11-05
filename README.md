# zekt-dev-org
zekt.dev - the ambition is to orchestrate the future &amp; to ease workflow collaboration within or between different Github customer organizations using our offerings. Join the zekt - become a member!

<!-- Optional banner/logo -->
<p align="center">
  <img src="./zekt-black.png" width="120" alt="Zekt.dev Logo"/>
</p>

<h1 align="center">⟁ - Zekt.dev</h1>

<p align="center">
  <strong>Ease collaboration without having your worlds collide</strong><br>
  As developers, we know that acting programatically on events within an organization can be hard, but between organizations are even harder. With the isolation model that Github offers (which is awesome from a security perspective) it often hampers collaboration capabilities between disjointed teams or organizations - on a Github level. With Zekt - customers can overcome these roadblocks - by having zekt act as the trusted broker of events occuring on one side of the organization or repository - feeding them to their intended consumers.
</p>

---

### 🧭 About Us
**Zekt.dev** is redefining how teams interact with each other or their customers without having to create complex API frameworks or plumbing infrastructure in between companies. Zekt will with your consent (using Github app) gather meta-data on assigned repositories and feed that meta-data to your desired customers - which they can then act upon!
We leverage your **federated GitHub Identity)** and **Zekt Github Apps** to enable collaboration capabilities between intended targeted customers of those events.

Our vision: **“Collaborate through zekt - using github workflows across organizations”**

---

### 🧩 What We Build
| Area | Description |
|------|--------------|
| 🧠 **OrcheZekt** | The orchestration engine powering the brokering of events between providers and consumers |
| 🌐 **Zekt Portal** | A lightweight web portal for managing WHO you want to consume from or share events with |
| ⚙️ **Zekt Apps** | The Github Apps - for OAuth flows and consent of permissions - transparency is key |
| 🔐 **Zekt security** | Secure integration between GitHub & Azure (our computing backbone) & our customers |
| 💸 **Zekt Analytics** | Visibility and usage insights per deployment and team |

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
