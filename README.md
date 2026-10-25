<h1 align="center">Efe Gökdemir</h1>

<p align="center">
  <strong>Founder & Director at <a href="https://github.com/RexCode-Digital">RexCode Digital Ltd</a></strong>
</p>

<p align="center">
  Building Shopify developer tooling, commerce software, and contributing upstream to open-source infrastructure.
</p>

<p align="center">
  <a href="https://www.rexcode.co.uk">Website</a>
  ·
  <a href="https://github.com/RexCode-Digital">RexCode</a>
  ·
  <a href="https://www.linkedin.com/in/gokdemirefe">LinkedIn</a>
  ·
  <a href="mailto:efe@rexcode.co.uk">Email</a>
</p>


---

## Building at RexCode

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>
        <a href="https://github.com/RexCode-Digital/shopify-app-changeguard">ChangeGuard</a>
      </strong>
      <br /><br />
      Review meaningful Shopify app configuration changes before deployment.
      <br /><br />
      <a href="https://www.npmjs.com/package/shopify-app-changeguard">npm</a>
      &nbsp;·&nbsp;
      <a href="https://github.com/marketplace/actions/changeguard-shopify-app-config-review">Marketplace</a>
    </td>
    <td width="50%" valign="top">
      <strong>
        <a href="https://github.com/RexCode-Digital/shopify-upgrade-guard">Upgrade Guard</a>
      </strong>
      <br /><br />
      Detect API deprecations and migration risks before upgrading.
      <br /><br />
      <a href="https://www.npmjs.com/package/shopify-upgrade-guard">npm</a>
      &nbsp;·&nbsp;
      <a href="https://github.com/marketplace/actions/shopify-upgrade-guard">Marketplace</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>
        <a href="https://github.com/RexCode-Digital/shopify-scope-guard">Scope Guard</a>
      </strong>
      <br /><br />
      Audit Shopify access scopes against repository evidence.
      <br /><br />
      <a href="https://www.npmjs.com/package/shopify-scope-guard">npm</a>
      &nbsp;·&nbsp;
      <a href="https://github.com/marketplace/actions/shopify-scope-guard">Marketplace</a>
    </td>
    <td width="50%" valign="top">
      <strong>
        <a href="https://github.com/RexCode-Digital/shopify-app-review-guard">App Review Guard</a>
      </strong>
      <br /><br />
      Run preflight checks for App Store submission and production readiness.
      <br /><br />
      <a href="https://www.npmjs.com/package/shopify-app-review-guard">npm</a>
      &nbsp;·&nbsp;
      <a href="https://github.com/marketplace/actions/shopify-app-review-guard">Marketplace</a>
    </td>
  </tr>
</table>

<br />

## Open Source Contributions

<p>
  <a href="https://github.com/NVIDIA/cccl/pull/11578">
    <img src="https://img.shields.io/badge/NVIDIA-24292F?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA" />
  </a>
  <a href="https://github.com/apache/arrow-java/pull/1309">
    <img src="https://img.shields.io/badge/Apache-24292F?style=flat-square&logo=apache&logoColor=white" alt="Apache" />
  </a>
  <a href="https://github.com/Shopify/checkout-sheet-kit-swift/pull/609">
    <img src="https://img.shields.io/badge/Shopify-24292F?style=flat-square&logo=shopify&logoColor=white" alt="Shopify" />
  </a>
  <a href="https://github.com/open-telemetry/opentelemetry-java/pull/8854">
    <img src="https://img.shields.io/badge/OpenTelemetry-24292F?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  </a>
</p>

The changes below were **merged upstream** after repository review. Each pull request links to the actual code, tests, and discussion; these are contributions to the respective projects, not RexCode-owned code.

| Upstream project | Selected engineering contribution |
| :--- | :--- |
| **[OpenTelemetry Java](https://github.com/open-telemetry/opentelemetry-java)** | Corrected retry decisions when gRPC status is returned in HTTP/2 trailers, including regression coverage for status handling and terminal failures. [#8854](https://github.com/open-telemetry/opentelemetry-java/pull/8854) |
| **[Apache Arrow Java](https://github.com/apache/arrow-java)** | Prevented invalid dictionary indices, including negative, out-of-range, and 64-bit truncation cases, with regression tests. [#1309](https://github.com/apache/arrow-java/pull/1309) |
| **[Apache Maven Resolver](https://github.com/apache/maven-resolver)** | Preserved transitive dependency discovery for version-range candidates; the added regressions reproduced the pre-fix failure. [#2208](https://github.com/apache/maven-resolver/pull/2208) |
| **[Basekick Arc](https://github.com/Basekick-Labs/arc)** | Improved atomic visibility of Raft manifest updates and WAL checkpoint recovery. [#910](https://github.com/Basekick-Labs/arc/pull/910) · [#998](https://github.com/Basekick-Labs/arc/pull/998) |
| **[NVIDIA CCCL](https://github.com/NVIDIA/cccl)** | Corrected NumPy structured-field handling in CUDA compute when fields include titles. [#11578](https://github.com/NVIDIA/cccl/pull/11578) |
| **[NVIDIA SkillSpector](https://github.com/NVIDIA/SkillSpector)** | Hardened TypeScript declaration-file classification to avoid trusting filenames and overlooking executable content. [#601](https://github.com/NVIDIA/SkillSpector/pull/601) |
| **[Apache Log4j](https://github.com/apache/logging-log4j2)** | Preserved HTTP log delivery when a dynamically evaluated header contains an invalid value. [#4360](https://github.com/apache/logging-log4j2/pull/4360) |
| **[Shopify Checkout Sheet Kit](https://github.com/Shopify/checkout-sheet-kit-swift)** | Improved Apple Pay sheet-presentation failure handling. [#609](https://github.com/Shopify/checkout-sheet-kit-swift/pull/609) |

<details>
  <summary><strong>More contributions</strong></summary>

  <br />

  <ul>
    <li>
      <strong><a href="https://github.com/Basekick-Labs/arc">Basekick Arc</a></strong> — Query cancellation on client disconnect.
      <a href="https://github.com/Basekick-Labs/arc/pull/982">#982</a>
    </li>
    <li>
      <strong><a href="https://github.com/NVIDIA/nodewright">NVIDIA NodeWright</a></strong> — Kubernetes status update conflict prevention.
      <a href="https://github.com/NVIDIA/nodewright/pull/651">#651</a>
    </li>
    <li>
      <strong><a href="https://github.com/NVIDIA/NVSentinel">NVIDIA NVSentinel</a></strong> — NIC health monitor completion metrics.
      <a href="https://github.com/NVIDIA/NVSentinel/pull/1983">#1983</a>
    </li>
    <li>
      <strong><a href="https://github.com/apache/logging-log4j2">Apache Log4j</a></strong> — Authentication encoding fallback fix.
      <a href="https://github.com/apache/logging-log4j2/pull/4358">#4358</a>
    </li>
  </ul>

</details>

<p>
  <a href="https://github.com/search?q=author%3Aefegokdemir+is%3Apr+is%3Amerged&type=pullrequests">
    <strong>View all merged contributions →</strong>
  </a>
</p>
