# Kuehne+Nagel

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

Kuehne+Nagel International AG is a Swiss freight forwarder and contract logistics provider headquartered in Schindellegi, Switzerland, and one of the largest forwarders in the world across sea logistics, air logistics, road logistics and contract logistics. As a forwarder it sits in the intermediation layer of the supply chain — between shippers on one side and ocean carriers, airlines, hauliers, terminals and customs authorities on the other — and most of the data it exposes is carrier and terminal data it aggregates rather than originates. Its API posture is honest but conditional: a real WSO2-based developer portal at portal.api.kuehne-nagel.com lists 17 published APIs and serves every OpenAPI definition anonymously, but every subscription is customer-contract gated — a myKN account, a Kuehne+Nagel customer ID (CID) and an account manager who completes the "customer setup" are stated pre-requisites, so nobody outside a commercial relationship can call the gateway. Underneath the REST veneer the company's own connectivity page still advertises EDIFACT, ANSI X.12, Tradacoms, RosettaNet, iDOC, GS1 and CargoImp over AS2, OFTP-2, (S)FTP and VAN as the primary integration path, and its one customs "EDI" API is an unschematized pass-through. One surface — OceanEventInbox v1 — is explicitly built to the DCSA equipment-event standard, which makes Kuehne+Nagel a non-member implementer of a carrier standards body; the other sixteen APIs are proprietary Kuehne+Nagel contracts.

**Areas:** Logistics · Supply Chain · Switzerland · Freight Forwarding · Ocean Freight · Container Shipping · Air Cargo · Road Freight · Customs · Trade Compliance · Track and Trace · Contract Logistics

## Kuehne+Nagel on APIs.io

Everything profiled for Kuehne+Nagel is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kuehne-nagel/](https://apis.io/providers/kuehne-nagel/)** — or go straight to one of the APIs or properties below.

### APIs (48)

- [Kuehne+Nagel Administration Layer API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-administration-layer-api/) — The administration-layer API from Kuehne+Nagel — 1 operation(s) for administration-layer.
- [Kuehne+Nagel API Keys API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-api-keys-api/) — Management of API keys for workspace authentication.
- [Kuehne+Nagel Assigned Consignments API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-assigned-consignments-api/) — The Assigned Consignments API from Kuehne+Nagel — 1 operation(s) for assigned consignments.
- [Kuehne+Nagel Background Tasks API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-background-tasks-api/) — Monitor and manage background scheduled tasks.
- [Kuehne+Nagel Booking API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-booking-api/) — The booking API from Kuehne+Nagel — 2 operation(s) for booking.
- [Kuehne+Nagel Booking Requests API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-booking-requests-api/) — The Booking Requests API from Kuehne+Nagel — 1 operation(s) for booking requests.
- [Kuehne+Nagel Cargo Items API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-cargoitems-api/) — Assets (possible types are PACKAGE, CONTAINER and UNKNOWN) belonging to a shipment.
- [Kuehne+Nagel Config API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-config-api/) — API configuration and metadata endpoints.
- [Kuehne+Nagel Container API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-container-api/) — The container API from Kuehne+Nagel — 2 operation(s) for container.
- [Kuehne+Nagel Delete API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-delete-api/) — Operations to delete shipment documents.
- [Kuehne+Nagel Document API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-document-api/) — The Document API from Kuehne+Nagel — 1 operation(s) for document.
- [Kuehne+Nagel Document Request API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-document-request-api/) — The Document Request API from Kuehne+Nagel — 1 operation(s) for document request.
- [Kuehne+Nagel Documents API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-documents-api/) — The documents API from Kuehne+Nagel — 4 operation(s) for documents.
- [Kuehne+Nagel Download API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-download-api/) — Operations to download shipment documents.
- [Kuehne+Nagel Esp Order Track API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-esp-order-track-api/) — The esp-order-track API from Kuehne+Nagel — 1 operation(s) for esp-order-track.
- [Kuehne+Nagel Events API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-events-api/) — Event operations
- [Kuehne+Nagel Export API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-export-api/) — The export API from Kuehne+Nagel — 1 operation(s) for export.
- [Kuehne+Nagel External Shipment API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-externalshipment-api/) — The ExternalShipment API from Kuehne+Nagel — 1 operation(s) for externalshipment.
- [Kuehne+Nagel GPS Tracking API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-gps-tracking-api/) — The GPS Tracking API from Kuehne+Nagel — 1 operation(s) for gps tracking.
- [Kuehne+Nagel Health API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-health-api/) — The Health API from Kuehne+Nagel — 1 operation(s) for health.
- [Kuehne+Nagel Healthz API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-healthz-api/) — The Healthz API from Kuehne+Nagel — 1 operation(s) for healthz.
- [Kuehne+Nagel Job Documents API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-job-documents-api/) — The Job Documents API from Kuehne+Nagel — 1 operation(s) for job documents.
- [Kuehne+Nagel Job Status API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-job-status-api/) — The Job Status API from Kuehne+Nagel — 1 operation(s) for job status.
- [Kuehne+Nagel Jobs API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-jobs-api/) — Operations for monitoring and managing asynchronous extraction jobs.
- [Kuehne+Nagel List API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-list-api/) — Operations to list shipment documents.
- [Kuehne+Nagel Master Data API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-master-data-api/) — The Master Data API from Kuehne+Nagel — 3 operation(s) for master data.
- [Kuehne+Nagel Metrics API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-metrics-api/) — The Metrics API from Kuehne+Nagel — 1 operation(s) for metrics.
- [Kuehne+Nagel Order API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-order-api/) — The Order API from Kuehne+Nagel — 1 operation(s) for order.
- [Kuehne+Nagel Post event API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-post-event-api/) — Post event description
- [Kuehne+Nagel Process File API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-process-file-api/) — Process individual files using LLM extraction with prompt templates.
- [Kuehne+Nagel Process State API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-process-state-api/) — The process-state API from Kuehne+Nagel — 1 operation(s) for process-state.
- [Kuehne+Nagel Process Zip API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-process-zip-api/) — Process ZIP archives containing multiple files using LLM extraction.
- [Kuehne+Nagel Prompt Tags API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-prompt-tags-api/) — Assign and manage tags for specific prompt versions.
- [Kuehne+Nagel Prompts API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-prompts-api/) — Manage prompts for workspaces.
- [Kuehne+Nagel Proof of Delivery API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-proof-of-delivery-api/) — The Proof of Delivery API from Kuehne+Nagel — 1 operation(s) for proof of delivery.
- [Kuehne+Nagel Purchase Order Layer API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-purchase-order-layer-api/) — The purchase-order-layer API from Kuehne+Nagel — 3 operation(s) for purchase-order-layer.
- [Kuehne+Nagel Quotas API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-quotas-api/) — Manage workspace processing quotas and limits.
- [Kuehne+Nagel Schemas API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-schemas-api/) — Manage schemas for workspaces.
- [Kuehne+Nagel Shipment API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-shipment-api/) — The shipment API from Kuehne+Nagel — 4 operation(s) for shipment.
- [Kuehne+Nagel Tags API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-tags-api/) — Manage tags for workspaces and prompts.
- [Kuehne+Nagel Telemetry API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-telemetry-api/) — Telemetry assigned to a cargo item (PACKAGE/CONTAINER/UNKNOWN).
- [Kuehne+Nagel Test Cases API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-test-cases-api/) — Manage test cases for prompt evaluation.
- [Kuehne+Nagel Test Sets API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-test-sets-api/) — The test-sets API from Kuehne+Nagel — 8 operation(s) for test-sets.
- [Kuehne+Nagel Tools API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-tools-api/) — Manage and discover available LLM tools for function calling. Includes both local tools and tools from registered MCP servers.
- [Kuehne+Nagel Upload API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-upload-api/) — Operations to upload shipment documents.
- [Kuehne+Nagel Usage Statistics API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-usage-statistics-api/) — The usage-statistics API from Kuehne+Nagel — 1 operation(s) for usage-statistics.
- [Kuehne+Nagel Users API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-users-api/) — The users API from Kuehne+Nagel — 4 operation(s) for users.
- [Kuehne+Nagel Workspaces API](https://apis.io/apis/kuehne-nagel/kuehne-nagel-workspaces-api/) — Manage workspaces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Collections (17)

Postman and Open Collection request collections.

- [B2B-CustomsEDI](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-b2b-customs-edi-v1/)
- [BookingAir](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-booking-air-v2/)
- [BookingRoad](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-booking-road-v1/)
- [ContainerTracking](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-container-tracking-v2/)
- [eSOPPurchaseOrderConfiguration](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-esop-purchase-order-configuration-v1/)
- [ExternalShipmentIntegration](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-external-shipment-integration-v1/)
- [IntermodalTransportExecution](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-intermodal-transport-execution-v1/)
- [B2B-OldKAIExtractAPI](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-kai-document-extract-v0-1-0/)
- [OceanEventInbox](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-ocean-event-inbox-v1/)
- [OrderBooking](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-order-booking-v1/)
- [OrderTracking](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-order-tracking-v2/)
- [PurchaseOrderManagement](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-purchase-order-management-v3/)
- [RealTimeVisibility-Tracking](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-real-time-visibility-tracking-v1/)
- [ShipmentDocumentManagement](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-shipment-document-management-v2/)
- [ShipmentDocumentManagement](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-shipment-document-management-v3/)
- [ShipmentEventIntegration](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-shipment-event-integration-v1/)
- [ShipmentTracking](https://apis.io/collections/kuehne-nagel/open-kuehne-nagel-shipment-tracking-v2/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kuehne-nagel.com/)
- [Documentation](https://www.kuehne-nagel.com/digital-services/data-integration)
- [Sign up](https://www.kuehne-nagel.com/contact/digital-data-integration)
- [Blog](https://www.kuehne-nagel.com/stories)
- [GitHub](https://github.com/kuehne-nagel)

## API Evangelist rating

**Kin Score 21.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 47.0 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 11.9 |
| Access clarity | 13.2 |

**Agent readiness 28.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | verified |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 0.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kuehne-nagel/](https://apis.io/providers/kuehne-nagel/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kuehne+Nagel: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kuehne-nagel/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
