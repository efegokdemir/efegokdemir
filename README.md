<h1 align="center">Efe Gökdemir</h1>

<p align="center">
  <strong>Founder & Director — <a href="https://github.com/RexCode-Digital">RexCode Digital Ltd</a></strong>
</p>

<p align="center">
  Building commerce software, Shopify developer tooling and open-source products.<br>
  Contributing production fixes upstream across database systems, developer infrastructure and data tooling.
</p>

<p align="center">
  <a href="https://www.rexcode.co.uk"><img src="https://img.shields.io/badge/RexCode-db9803?style=for-the-badge&logo=googlechrome&logoColor=white" alt="RexCode website" /></a>
  <a href="https://github.com/RexCode-Digital"><img src="https://img.shields.io/badge/RexCode%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="RexCode Digital on GitHub" /></a>
  <a href="https://www.linkedin.com/in/gokdemirefe"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=fff" alt="LinkedIn" /></a>
  <a href="https://www.instagram.com/t7caret/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="mailto:efe@rexcode.co.uk"><img src="https://img.shields.io/badge/Email-2b2b2b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## Building at RexCode

| Project | What it is |
| --- | --- |
| **[Nami](https://github.com/RexCode-Digital/nami)** | A calm, flexible and open-source Shopify theme built for real commerce. |
| **[Shopify App ChangeGuard](https://github.com/RexCode-Digital/shopify-app-changeguard)** | Offline semantic review for Shopify app configuration changes — CLI + GitHub Action. [npm](https://www.npmjs.com/package/shopify-app-changeguard) · [Marketplace](https://github.com/marketplace/actions/changeguard-shopify-app-config-review) |
| **[Shopify Upgrade Guard](https://github.com/RexCode-Digital/shopify-upgrade-guard)** | Detects Shopify API upgrade and deprecation risks in CI — offline CLI + GitHub Action. [npm](https://www.npmjs.com/package/shopify-upgrade-guard) · [Marketplace](https://github.com/marketplace/actions/shopify-upgrade-guard) |
| **[Shopify Scope Guard](https://github.com/RexCode-Digital/shopify-scope-guard)** | Offline static analysis for Shopify access scopes and permission evidence — CLI + GitHub Action. [npm](https://www.npmjs.com/package/shopify-scope-guard) · [Marketplace](https://github.com/marketplace/actions/shopify-scope-guard) |
| **[Shopify App Review Guard](https://github.com/RexCode-Digital/shopify-app-review-guard)** | Deterministic offline preflight checks for Shopify App Store submission and production readiness. [npm](https://www.npmjs.com/package/shopify-app-review-guard) · [Marketplace](https://github.com/marketplace/actions/shopify-app-review-guard) |

## Open source

Selected merged contributions across database systems, GPU/data tooling and developer infrastructure.

| Project | Selected work |
| --- | --- |
| **Basekick Arc** | Fixed WAL checkpoint recovery to prevent already-flushed entries being replayed after recovery. **[PR #998](https://github.com/Basekick-Labs/arc/pull/998)** · Improved full-queue ingest flush behaviour in **[PR #997](https://github.com/Basekick-Labs/arc/pull/997)** · Added compaction deadline and cancellation handling in **[PR #922](https://github.com/Basekick-Labs/arc/pull/922)** |
| **NVIDIA CCCL** | Fixed structured NumPy dtype handling in `cuda.compute` by treating field titles as aliases rather than members. **[PR #11578](https://github.com/NVIDIA/cccl/pull/11578)** |
| **NVIDIA structured-data-models** | Preserved buffer dtype while loading processor state instead of silently changing the underlying representation. **[PR #1035](https://github.com/NVIDIA/structured-data-models/pull/1035)** |
| **Apache Arrow ADBC** | Added fallback to the standard driver entrypoint for the C# driver loading path. **[PR #4815](https://github.com/apache/arrow-adbc/pull/4815)** |
| **Apache Arrow / nanoarrow** | Made validation of unaligned C Data Interface offset buffers safe. **[PR #946](https://github.com/apache/arrow-nanoarrow/pull/946)** |
| **Apache Maven Resolver** | Synchronized IPC stream access in **[PR #2163](https://github.com/apache/maven-resolver/pull/2163)** and ensured fatal JVM errors from Jetty request content propagate correctly in **[PR #2161](https://github.com/apache/maven-resolver/pull/2161)** |

<p align="center">
  <sub>Founder @ RexCode Digital Ltd · Commerce software · Open source</sub>
</p>
