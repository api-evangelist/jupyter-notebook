# Jupyter Notebook

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Jupyter Notebook is the original open-source web application for creating and sharing computational documents that contain live code, equations, visualizations, and narrative text. The Jupyter Notebook server exposes a REST API for managing notebooks, files, kernels, sessions, and terminals, and uses the WebSocket-based Jupyter messaging protocol to communicate with kernels.

**Areas:** Data Science · Interactive Computing · Jupyter · Machine Learning · Notebooks · Python · Real-Time

## Jupyter Notebook on APIs.io

Everything profiled for Jupyter Notebook is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/jupyter-notebook/](https://apis.io/providers/jupyter-notebook/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Jupyter Kernel Messaging Protocol](https://apis.io/apis/jupyter-notebook/jupyter-kernel-messaging/) — WebSocket-based messaging protocol for communication between Jupyter clients and computational kernels. Supports code execution, introspection, completion,…
- [Jupyter Notebook Authorization API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-authorization-api/) — Token verification and authorization checks.
- [Jupyter Notebook Config API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-config-api/) — Server configuration section management.
- [Jupyter Notebook Contents API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-contents-api/) — File and directory management including notebooks, files, directories, and checkpoints.
- [Jupyter Notebook General API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-general-api/) — General gateway information.
- [Jupyter Notebook Groups API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-groups-api/) — Group management for organizing users.
- [Jupyter Notebook Hub API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-hub-api/) — Hub lifecycle management.
- [Jupyter Notebook Kernels API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-kernels-api/) — Kernel lifecycle management on the gateway. The gateway may enforce kernel limits and seed kernels.
- [Jupyter Notebook Kernelspecs API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-kernelspecs-api/) — Kernel specification listing and retrieval.
- [Jupyter Notebook Proxy API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-proxy-api/) — Configurable HTTP proxy routing table management.
- [Jupyter Notebook Services API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-services-api/) — The Services API from Jupyter Notebook — 2 operation(s) for services.
- [Jupyter Notebook Sessions API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-sessions-api/) — Session management for associating notebooks with running kernels.
- [Jupyter Notebook Terminals API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-terminals-api/) — Terminal session management on the server.
- [Jupyter Notebook Users API](https://apis.io/apis/jupyter-notebook/jupyter-notebook-users-api/) — User management including creation, deletion, server management, and token management.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Jupyter Kernel Messaging Protocol](https://apis.io/asyncapis/jupyter-notebook/jupyter-kernel-messaging-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/api/kernels/{kernel_id}/channels](https://apis.io/channels/jupyter-notebook/api-kernels-kernel-id-channels/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Jupyter Notebook Agentic Access](https://apis.io/agentic-access/jupyter-notebook/jupyter-notebook-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Jupyter Contents Model](https://apis.io/schemas/jupyter-notebook/jupyter-contents-model/)
- [Jupyter Kernel Message](https://apis.io/schemas/jupyter-notebook/jupyter-kernel-message/)
- [Jupyter Kernel Specification](https://apis.io/schemas/jupyter-notebook/jupyter-kernel-spec/)
- [Jupyter Notebook Document](https://apis.io/schemas/jupyter-notebook/jupyter-notebook-document/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Jupyter Notebook Context](https://apis.io/jsonld/jupyter-notebook/jupyter-notebook-context/)

#### Collections (16)

Postman and Open Collection request collections.

- [Jupyter Notebook Jupyter Kernel Gateway API](https://apis.io/collections/jupyter-notebook/open-jupyter-kernel-gateway-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-authorization-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Config API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-config-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Contents API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-contents-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization General API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-general-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Groups API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-groups-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Hub API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-hub-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Kernels API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-kernels-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Kernelspecs API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-kernelspecs-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Proxy API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-proxy-api/)
- [Jupyter Notebook REST API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-rest-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Services API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-services-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Sessions API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-sessions-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Terminals API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-terminals-api/)
- [Jupyter Notebook Jupyter Kernel Gateway Authorization Users API](https://apis.io/collections/jupyter-notebook/open-jupyter-notebook-users-api/)
- [Jupyter Notebook JupyterHub REST API](https://apis.io/collections/jupyter-notebook/open-jupyterhub-rest-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Jupyter Notebook — asyncapi rules](https://apis.io/rules/jupyter-notebook/jupyter-notebook-asyncapi-spectral-rules/)
- [Jupyter Notebook — jsonschema rules](https://apis.io/rules/jupyter-notebook/jupyter-notebook-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Jupyter Notebook Authentication](https://apis.io/security/jupyter-notebook/jupyter-notebook-authentication/)
- [Jupyter Notebook Domain Security](https://apis.io/security/jupyter-notebook/jupyter-notebook-domain-security/)
- [Jupyter Notebook Vulnerability Disclosure](https://apis.io/security/jupyter-notebook/jupyter-notebook-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Jupyter Notebook Plans Pricing](https://apis.io/plans/jupyter-notebook/jupyter-notebook-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Jupyter Notebook Rate Limits](https://apis.io/rate-limits/jupyter-notebook/jupyter-notebook-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Jupyter Notebook Finops](https://apis.io/finops/jupyter-notebook/jupyter-notebook-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://jupyter.org)
- [Documentation](https://docs.jupyter.org/en/latest/)
- [Getting started](https://docs.jupyter.org/en/latest/start/index.html)
- [Support](https://discourse.jupyter.org/)
- [Blog](https://blog.jupyter.org/)
- [Security](https://jupyter.org/security)
- [GitHub](https://github.com/jupyter)

## API Evangelist rating

**Kin Score 40.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 64.8 |
| Contract governance | 13.6 |
| Operational transparency | 34.2 |
| Developer ergonomics | 40.5 |
| Access clarity | 5.3 |

**Agent readiness 20.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/jupyter-notebook/](https://apis.io/providers/jupyter-notebook/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Jupyter Notebook: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/jupyter-notebook/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
