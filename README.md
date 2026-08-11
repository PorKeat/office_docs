# <img src="https://icongr.am/feather/cloud.svg?size=24&color=3b82f6" width="24" height="24" align="top"> Nextcloud Sovereign Workspace

Welcome to your central documentation hub! This vault contains everything you need to evaluate, present, and deploy a high-performance, fully sovereign Nextcloud architecture.

---

## <img src="https://icongr.am/feather/target.svg?size=24&color=3b82f6" width="24" height="24" align="top"> Phase 1: Strategy & Decision Making
Before touching any code, use these documents to understand the landscape and present the options to your team.

* <img src="https://icongr.am/feather/bar-chart-2.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[Office Suites Comparison](Guides/office_suites_comparison.md)**: A plain-English breakdown comparing Collabora, ONLYOFFICE, and Euro-Office.

---

## <img src="https://icongr.am/feather/tool.svg?size=24&color=3b82f6" width="24" height="24" align="top"> Phase 2: Core Infrastructure (Performance & Security)
Nextcloud requires robust storage and caching to perform at an enterprise level.

* <img src="https://icongr.am/feather/database.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[MinIO Encryption Configuration](Guides/minio_encryption.md)**: How we use a "Defense-in-Depth" strategy with HashiCorp Vault to guarantee your documents are mathematically secure.
* <img src="https://icongr.am/feather/zap.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[Redis Setup Guide](Guides/setup_redis_with_nextcloud.md)**: How to eliminate lag and prevent "stuck" documents by routing heavy traffic into super-fast RAM.

---

## <img src="https://icongr.am/feather/server.svg?size=24&color=3b82f6" width="24" height="24" align="top"> Phase 3: Office Suite Deployment
Once your core infrastructure is ready, pick one of the office suites below and deploy it to your cluster. Each guide contains the exact Kubernetes manifests (YAML) you need.

* <img src="https://icongr.am/feather/box.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[Deploy Nextcloud Office (Collabora)](Guides/setup_collabora.md)** - *Recommended for maximum privacy and older hardware.*
* <img src="https://icongr.am/feather/box.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[Deploy ONLYOFFICE](Guides/setup_onlyoffice.md)** - *Recommended for flawless Microsoft Office compatibility.*
* <img src="https://icongr.am/feather/box.svg?size=24&color=3b82f6" width="24" height="24" align="top"> **[Deploy Euro-Office](Guides/setup_euro_office.md)** - *A fully sovereign, European open-source fork of ONLYOFFICE.*
