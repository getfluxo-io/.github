# MAVULA

![MAVULA branding](mavula_branding.png)

[![Website](https://img.shields.io/badge/mavula.io-primary-111111.svg)](https://mavula.io)
[![Developers](https://img.shields.io/badge/mavula.dev-open-0A66C2.svg)](https://mavula.dev)
[![Core license](https://img.shields.io/badge/core-AGPL--3.0--only-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Operations license](https://img.shields.io/badge/operations-Apache--2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![TypeScript](https://img.shields.io/badge/TypeScript-runtime-3178C6.svg)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-runtime-4169E1.svg)](https://www.postgresql.org/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-operations-326CE5.svg)](https://kubernetes.io/)

Infrastructure for the next generation of finance.

MAVULA is an open core financial infrastructure project for institutions that
need ledger, lending, payments, workflow automation and operational controls
behind explicit contracts.

## Platform

| Repository | Purpose |
| --- | --- |
| [`finance-platform`](https://github.com/mavulahq/finance-platform) | Main workspace and cross-module contracts. |
| [`ledger-core`](https://github.com/mavulahq/ledger-core) | Financial source of truth for products, accounts, ledger and lending. |
| [`workbench`](https://github.com/mavulahq/workbench) | Durable jobs, queues, schedules, retries, status and metrics. |
| [`settlements`](https://github.com/mavulahq/settlements) | Payment process state, webhook dedupe, reconciliation and settlement events. |
| [`operations`](https://github.com/mavulahq/operations) | Docker, Kubernetes, local development, monitoring and deployment tooling. |
| [`governance`](https://github.com/mavulahq/governance) | Governance, security policy, RFCs and contribution process. |

## Open Core

Core runtime modules are licensed under `AGPL-3.0-only`. Operations tooling may
use `Apache-2.0`. Enterprise hosting, proprietary integrations, compliance
packs and managed services may be licensed separately.

The MAVULA name, logo, domains and product marks remain reserved.

## Links

- Website: <https://mavula.io>
- Developers: <https://mavula.dev>
- Discussions: <https://github.com/orgs/mavulahq/discussions>
- Security: security@mavula.io
- Legal and trademark: legal@mavula.io
