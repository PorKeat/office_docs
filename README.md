# ☁️ Nextcloud Sovereign Workspace

Welcome to your central documentation hub! This vault contains everything you need to evaluate, present, and deploy a high-performance, fully sovereign Nextcloud architecture.

---

## 🎯 Phase 1: Strategy & Decision Making
Before touching any code, use these documents to understand the landscape and present the options to your team.

* 📊 **[Office Suites Comparison](Guides/office_suites_comparison.md)**: A plain-English breakdown comparing Collabora, ONLYOFFICE, and Euro-Office.

---

## 🏗️ Phase 2: Core Infrastructure (Performance & Security)
Nextcloud requires robust storage and caching to perform at an enterprise level.

* 🗄️ **[MinIO Encryption Configuration](Guides/minio_encryption.md)**: How we use a "Defense-in-Depth" strategy with HashiCorp Vault to guarantee your documents are mathematically secure.
* ⚡ **[Redis Setup Guide](Guides/setup_redis_with_nextcloud.md)**: How to eliminate lag and prevent "stuck" documents by routing heavy traffic into super-fast RAM.

---

## 🏢 Phase 3: Office Suite Deployment
Once your core infrastructure is ready, pick one of the office suites below and deploy it to your cluster. Each guide contains the exact Kubernetes manifests (YAML) you need.

* 🟦 **[Deploy Nextcloud Office (Collabora)](Guides/setup_collabora.md)** - *Recommended for maximum privacy and older hardware.*
* 🟧 **[Deploy ONLYOFFICE](Guides/setup_onlyoffice.md)** - *Recommended for flawless Microsoft Office compatibility.*
* 🟩 **[Deploy Euro-Office](Guides/setup_euro_office.md)** - *A fully sovereign, European open-source fork of ONLYOFFICE.*
