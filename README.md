# CloudEvents

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

CloudEvents is a CNCF graduated specification for describing event data in a common way. It provides a consistent format for event metadata across services, platforms, and systems, enabling interoperability between event producers and consumers. The specification includes protocol bindings for HTTP, AMQP, Kafka, MQTT, and NATS, along with SDKs in multiple languages.

**Areas:** CloudEvents · Cloud-Native · Event · Graduated · Interoperability · Messaging · Specification

## CloudEvents on APIs.io

Everything profiled for CloudEvents is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudevents/](https://apis.io/providers/cloudevents/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [CloudEvents Specification](https://apis.io/apis/cloudevents/cloudevents-spec/) — The CloudEvents specification defines a set of metadata attributes that must be present in every event, including source, type, id, and specversion. It…
- [CloudEvents HTTP Protocol Binding](https://apis.io/apis/cloudevents/cloudevents-http-binding/) — The HTTP protocol binding defines how CloudEvents are transported using HTTP, including structured content mode where the entire event is in the HTTP body,…
- [CloudEvents Kafka Protocol Binding](https://apis.io/apis/cloudevents/cloudevents-kafka-binding/) — The Kafka protocol binding for CloudEvents defines how events are mapped to Apache Kafka messages. It specifies how CloudEvents attributes are encoded as…
- [CloudEvents AMQP Protocol Binding](https://apis.io/apis/cloudevents/cloudevents-amqp-binding/) — The AMQP protocol binding for CloudEvents defines how events are mapped to OASIS AMQP 1.0 messages. In structured content mode, event attributes and data…
- [CloudEvents MQTT Protocol Binding](https://apis.io/apis/cloudevents/cloudevents-mqtt-binding/) — The MQTT protocol binding for CloudEvents defines how events are mapped to MQTT 3.1.1 and MQTT 5.0 messages. It supports both structured and binary content…
- [CloudEvents NATS Protocol Binding](https://apis.io/apis/cloudevents/cloudevents-nats-binding/) — The NATS protocol binding for CloudEvents defines how events are mapped to NATS messages. It enables CloudEvents to be produced and consumed over the NATS…
- [CloudEvents SQL (CESQL)](https://apis.io/apis/cloudevents/cloudevents-cesql/) — CloudEvents SQL (CESQL) is a v1.0 specification that defines a standardized query language for filtering and routing CloudEvents based on their attributes.…
- [CloudEvents Go SDK](https://apis.io/apis/cloudevents/cloudevents-sdk-go/) — The official Go SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Go applications. It supports all CloudEvents protocol…
- [CloudEvents JavaScript SDK](https://apis.io/apis/cloudevents/cloudevents-sdk-javascript/) — The official JavaScript SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Node.js and browser environments. It supports…
- [CloudEvents Java SDK](https://apis.io/apis/cloudevents/cloudevents-sdk-java/) — The official Java SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Java applications. It includes support for HTTP, Kafka,…
- [CloudEvents Python SDK](https://apis.io/apis/cloudevents/cloudevents-sdk-python/) — The official Python SDK for CloudEvents provides libraries for producing and consuming CloudEvents in Python applications. It supports HTTP transport…
- [CloudEvents Subscriptions API](https://apis.io/apis/cloudevents/cloudevents-subscriptions-api/) — Operations for creating and managing event delivery subscriptions. Each subscription specifies a source of events, optional filter criteria, and a sink…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [CloudEvents HTTP Delivery](https://apis.io/asyncapis/cloudevents/cloudevents-http-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/batch](https://apis.io/channels/cloudevents/batch/)
- [/](https://apis.io/channels/cloudevents/untitled/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cloudevents Agentic Access](https://apis.io/agentic-access/cloudevents/cloudevents-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Error](https://apis.io/schemas/cloudevents/cloudevents-error/)
- [CloudEvent](https://apis.io/schemas/cloudevents/cloudevents-event/)
- [Filter](https://apis.io/schemas/cloudevents/cloudevents-filter/)
- [ProtocolSettings](https://apis.io/schemas/cloudevents/cloudevents-protocolsettings/)
- [Subscription](https://apis.io/schemas/cloudevents/cloudevents-subscription/)
- [SubscriptionRequest](https://apis.io/schemas/cloudevents/cloudevents-subscriptionrequest/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Cloudevents Structure](https://apis.io/json-structure/cloudevents/cloudevents-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloudevents Context](https://apis.io/jsonld/cloudevents/cloudevents-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [CloudEvents Domain Vocabulary](https://apis.io/vocabularies/cloudevents/cloudevents-vocabulary/)

#### Collections (2)

Postman and Open Collection request collections.

- [CloudEvents Subscriptions API](https://apis.io/collections/cloudevents/open-cloudevents-subscriptions/)
- [CloudEvents Subscriptions API](https://apis.io/collections/cloudevents/open-cloudevents-subscriptions-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [CloudEvents — asyncapi rules](https://apis.io/rules/cloudevents/cloudevents-asyncapi-spectral-rules/)
- [CloudEvents — jsonschema rules](https://apis.io/rules/cloudevents/cloudevents-jsonschema-spectral-rules/)
- [CloudEvents API Rules](https://apis.io/rules/cloudevents/cloudevents-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudevents Domain Security](https://apis.io/security/cloudevents/cloudevents-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudevents Plans Pricing](https://apis.io/plans/cloudevents/cloudevents-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudevents Rate Limits](https://apis.io/rate-limits/cloudevents/cloudevents-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudevents Finops](https://apis.io/finops/cloudevents/cloudevents-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cloudevents.io)
- [Documentation](https://github.com/cloudevents/spec)
- [Getting started](https://github.com/cloudevents/spec/blob/main/cloudevents/primer.md)
- [Changelog](https://github.com/cloudevents/spec/releases)
- [Blog](https://cloudevents.io/blog/)
- [GitHub](https://github.com/cloudevents)

## API Evangelist rating

**Kin Score 36.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 65.4 |
| Contract governance | 13.6 |
| Operational transparency | 23.7 |
| Developer ergonomics | 38.1 |
| Access clarity | 5.3 |

**Agent readiness 16.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
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

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudevents/](https://apis.io/providers/cloudevents/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CloudEvents: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudevents/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
