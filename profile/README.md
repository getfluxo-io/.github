# MAVULA

![MAVULA branding](mavula_branding.png)

[![Website](https://img.shields.io/badge/mavula.io-primary-111111.svg)](https://mavula.io)
[![Developers](https://img.shields.io/badge/mavula.dev-open-0A66C2.svg)](https://mavula.dev)
[![License: AGPL-3.0-only](https://img.shields.io/badge/core-AGPL--3.0--only-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Operations: Apache-2.0](https://img.shields.io/badge/operations-Apache--2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![TypeScript](https://img.shields.io/badge/TypeScript-runtime-3178C6.svg)](https://www.typescriptlang.org/)
[![Go](https://img.shields.io/badge/Go-planned-00ADD8.svg)](https://go.dev/)
[![Java](https://img.shields.io/badge/Java-planned-ED8B00.svg)](https://www.java.com/)
[![COBOL](https://img.shields.io/badge/COBOL-integration--ready-005CA5.svg)](https://en.wikipedia.org/wiki/COBOL)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-runtime-4169E1.svg)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-queues-DC382D.svg)](https://redis.io/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-operations-326CE5.svg)](https://kubernetes.io/)

Infrastructure for the next generation of finance.

MAVULA builds configurable financial infrastructure for institutions that need
ledger, lending, payments, workflow automation and operational controls behind
explicit contracts.

## Platform Modules

| Module | Responsibility |
| --- | --- |
| Ledger Core | Financial source of truth for products, accounts, ledger, lending, audit and projections. |
| Workbench | Durable jobs, queues, schedules, retries, status and metrics. |
| Settlements | Payment process state, webhook dedupe, reconciliation and guarded settlement events. |
| Operations | Docker, Kubernetes, local development, monitoring and deployment tooling. |

## Open Core

MAVULA uses an open core model:

- core runtime modules are AGPL-3.0-only;
- operations tooling is Apache-2.0;
- enterprise hosting, proprietary integrations, compliance packs and managed
  services may be licensed separately;
- the MAVULA name, logo, domains and product marks remain reserved.

## Governance

MAVULA uses owner-led governance with public contribution paths, RFCs for
cross-module changes and maintainer review for all code changes.

- Website: [mavula.io](https://mavula.io)
- Developers: [mavula.dev](https://mavula.dev)
- Discussions: [GitHub Discussions](https://github.com/orgs/getfluxo-io/discussions)
- Security: security@mavula.io
- Legal: legal@mavula.io
