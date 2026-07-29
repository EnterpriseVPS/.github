# Enterprise VPS Solutions

**Advanced WHMCS modules, infrastructure automation, and hosting-management software.**

Enterprise VPS Solutions LLC builds commercial WHMCS modules and automation tooling for
hosting providers — provisioning, billing, security, and support, engineered for
production use and sold with license-controlled delivery.

🌐 **Website:** <https://enterprisevpssolutions.com/> · 📧 **Support:** support@enterprisevpssolutions.com · 📍 Brandon, Florida, USA

---

## Products

| Module | What it does |
|---|---|
| **ProxmoxCloud (VE · PBS · PDM)** | Full KVM/LXC provisioning for Proxmox — order automation, cloud-init, backups, per-GB metering, and a managed **Cloudflare** reseller layer. |
| **AI Assistant** | AI-assisted ticket handling and support automation inside WHMCS. |
| **IPAM Manager** | IP address management with federated authorities and reverse-DNS control. |
| **Fraud Prevention Suite** | Order-fraud scoring, bot/headless detection, and step-up (3DS2/SCA) orchestration. |
| **cPanel Extended Suite** | Extended cPanel/WHM control-centre features for WHMCS. |
| **OpenProject SOW Bridge** | Statement-of-work bridge between WHMCS and OpenProject. |
| **QuickBooks Center** | Accounting/QuickBooks integration for WHMCS billing. |
| **Abuse Feedback Center** | Structured abuse reporting and feedback-loop handling. |
| **EVPS-1000X Theme** | A premium WHMCS client theme and order-form experience. |

Product pages, pricing, compatibility and changelogs live on the
[website](https://enterprisevpssolutions.com/). Purchases and downloads are handled through
the WHMCS client area under license — **not** through GitHub.

## How our code is delivered

- **Source of truth:** a private, self-hosted GitLab instance holds the canonical commercial
  source and runs the primary CI/CD and release pipeline.
- **This GitHub organization** is the company's public developer identity and a **private,
  one-way mirror** of selected release artifacts. Commercial source is never published
  publicly here.
- **Customer packages** are **ionCube-encoded**, checksummed, and delivered through the WHMCS
  client area with license enforcement. Every release ships a manifest (version, commit,
  build, supported PHP/WHMCS, checksums).

## Support

- **Customers:** open a ticket from your Enterprise VPS Solutions client area — that route is
  license-aware and fastest.
- **General / pre-sales:** support@enterprisevpssolutions.com

## Security

Please report suspected vulnerabilities privately — see [SECURITY.md](./SECURITY.md). Do not
open public issues for security matters.

## Compatibility (current baseline)

- **WHMCS** 8.13.x (9.x under validation)
- **PHP** 8.2 / 8.3 (ionCube Loader required for encoded builds)
- **Proxmox VE** 9.x (8.3–8.4 best-effort), **PBS** 4.x, **PDM** 1.x

---

<sub>© Enterprise VPS Solutions LLC. Product and company names are trademarks of their
respective owners.</sub>
