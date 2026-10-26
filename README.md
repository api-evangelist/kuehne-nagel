# Kuehne+Nagel (kuehne-nagel)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kuehne-nagel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kuehne-nagel/refs/heads/main/apis.yml)

## Tags

- Logistics
- Supply Chain
- Switzerland
- Freight Forwarding
- Ocean Freight
- Container Shipping
- Air Cargo
- Road Freight
- Customs
- Trade Compliance
- Track and Trace
- Contract Logistics
- Standards

## Timestamps

- **Created:** 2026-07-30
- **Modified:** 2026-07-30

## APIs

### Kuehne+Nagel ShipmentTracking API

Find and show details of the customer's shipments, with contents reflecting the visibility configured in myKN. Search shipments, load a single shipment by unique reference, and read history records. Read-only polling; no webhook or callback is published.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/6b98ae4c-ef06-4f72-acba-616584ee7f0f/overview](https://portal.api.kuehne-nagel.com/devportal/apis/6b98ae4c-ef06-4f72-acba-616584ee7f0f/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/track-trace/shipment/v2`

#### Tags

- Track and Trace
- Shipments
- Ocean Freight
- Air Cargo

#### Properties

- [OpenAPI](openapi/kuehne-nagel-shipment-tracking-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-shipment-tracking-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-shipment-tracking-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/6b98ae4c-ef06-4f72-acba-616584ee7f0f/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel ContainerTracking API

Find and show details of the customer's seafreight containers, reflecting myKN visibility. Container search plus a per-container read keyed on the Kuehne+Nagel unique shipment reference and container sequence number.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/bf506fea-4c34-4072-bc1c-aa6d1e6f0ca8/overview](https://portal.api.kuehne-nagel.com/devportal/apis/bf506fea-4c34-4072-bc1c-aa6d1e6f0ca8/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/track-trace/container/v2`

#### Tags

- Track and Trace
- Container Shipping
- Ocean Freight

#### Properties

- [OpenAPI](openapi/kuehne-nagel-container-tracking-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-container-tracking-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-container-tracking-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/bf506fea-4c34-4072-bc1c-aa6d1e6f0ca8/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel OrderTracking API

A service for consumers to receive order data information, searched by order attributes. Carries UN/LOCODE port fields, HS codes, EORI numbers and a GS1 global location number field on item attributes.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/24f13980-9857-41ef-a3e5-3cd7844da5d6/overview](https://portal.api.kuehne-nagel.com/devportal/apis/24f13980-9857-41ef-a3e5-3cd7844da5d6/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/track-trace/order/v2`

#### Tags

- Track and Trace
- Order Management
- Supply Chain

#### Properties

- [OpenAPI](openapi/kuehne-nagel-order-tracking-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-order-tracking-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-order-tracking-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/24f13980-9857-41ef-a3e5-3cd7844da5d6/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel RealTimeVisibility-Tracking API

Read cargo items and their telemetry readings for real-time visibility. Two GET operations, polled; no subscription or push channel is published.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/d17c2f11-d4db-4edf-b4e0-b78406cfbb7f/overview](https://portal.api.kuehne-nagel.com/devportal/apis/d17c2f11-d4db-4edf-b4e0-b78406cfbb7f/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/real-time-visibility/tracking/v1`

#### Tags

- Track and Trace
- Telematics
- Visibility

#### Properties

- [OpenAPI](openapi/kuehne-nagel-real-time-visibility-tracking-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-real-time-visibility-tracking-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-real-time-visibility-tracking-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/d17c2f11-d4db-4edf-b4e0-b78406cfbb7f/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel BookingAir API

A service for consumers to book an air shipment, optionally applying product prices supplied via the Airfreight Quote API. Carries IATA three-letter airport codes, air waybill and HAWB service types, HS codes and IATA dangerous-goods flags.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/bfc135f0-875b-4421-b203-e56f91aa0e66/overview](https://portal.api.kuehne-nagel.com/devportal/apis/bfc135f0-875b-4421-b203-e56f91aa0e66/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/booking/air/v2`

#### Tags

- Air Cargo
- Booking
- Freight Forwarding

#### Properties

- [OpenAPI](openapi/kuehne-nagel-booking-air-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-booking-air-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-booking-air-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/bfc135f0-875b-4421-b203-e56f91aa0e66/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel BookingRoad API

A service for consumers to book road shipments, with master-data category lookups and a document upload operation alongside booking creation.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/f3ca4f89-d159-4a5f-bedc-68a2eb7b483c/overview](https://portal.api.kuehne-nagel.com/devportal/apis/f3ca4f89-d159-4a5f-bedc-68a2eb7b483c/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/booking/road/v1`

#### Tags

- Road Freight
- Booking
- Freight Forwarding

#### Properties

- [OpenAPI](openapi/kuehne-nagel-booking-road-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-booking-road-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-booking-road-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/f3ca4f89-d159-4a5f-bedc-68a2eb7b483c/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel OrderBooking API

Create and update order bookings by shipper's reference and poll a process state. Discriminated booking bodies for AIR, FCL and LCL, with UN/LOCODE-typed ports and airports.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/e520b7b7-44ff-4546-ad46-5c75d35041cc/overview](https://portal.api.kuehne-nagel.com/devportal/apis/e520b7b7-44ff-4546-ad46-5c75d35041cc/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/order-management/order-booking/v1`

#### Tags

- Booking
- Order Management
- Ocean Freight
- Air Cargo

#### Properties

- [OpenAPI](openapi/kuehne-nagel-order-booking-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-order-booking-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-order-booking-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel PurchaseOrderManagement API

Create, patch, search and cancel purchase orders scoped to a Kuehne+Nagel customer code. UN/LOCODE ports, HS codes and EORI numbers appear on the order model.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/79670bfa-841d-4d9f-bbee-5a5d737f7d21/overview](https://portal.api.kuehne-nagel.com/devportal/apis/79670bfa-841d-4d9f-bbee-5a5d737f7d21/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/order-management/purchase-order/v3`

#### Tags

- Order Management
- Supply Chain
- Purchase Orders

#### Properties

- [OpenAPI](openapi/kuehne-nagel-purchase-order-management-v3-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-purchase-order-management-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-purchase-order-management-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/79670bfa-841d-4d9f-bbee-5a5d737f7d21/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel eSOPPurchaseOrderConfiguration API

Read the purchase-order configuration for a given Kuehne+Nagel customer code. The devportal publishes only an internal gateway environment for this API; no external endpoint URL is advertised.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/98eed3c9-1f7a-4d40-8852-f0eb452f315e/overview](https://portal.api.kuehne-nagel.com/devportal/apis/98eed3c9-1f7a-4d40-8852-f0eb452f315e/overview)

#### Tags

- Order Management
- Configuration

#### Properties

- [OpenAPI](openapi/kuehne-nagel-esop-purchase-order-configuration-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-esop-purchase-order-configuration-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-esop-purchase-order-configuration-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel OceanEventInbox API

Lets service providers submit container equipment events for shipments booked with Kuehne+Nagel, following Digital Container Shipping Association (DCSA) standards. Inbound only — Kuehne+Nagel receives events here rather than publishing them. Equipment references follow BIC ISO 6346, locations use UN/LOCODE, and carriers are identified by SCAC or SMDG code lists.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/ea0d3ea0-3825-4175-bb54-875068074dca/overview](https://portal.api.kuehne-nagel.com/devportal/apis/ea0d3ea0-3825-4175-bb54-875068074dca/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/integration/external/event/container/v1`

#### Tags

- Standards
- DCSA
- Container Shipping
- Events
- Track and Trace

#### Properties

- [OpenAPI](openapi/kuehne-nagel-ocean-event-inbox-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-ocean-event-inbox-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-ocean-event-inbox-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/ea0d3ea0-3825-4175-bb54-875068074dca/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel ShipmentEventIntegration API

Validates and accepts incoming shipment event entries from third parties. Inbound only; the specification names a third-party application as the intended publisher.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/fe5ed9e7-67cb-471f-a679-7bdade8d6850/overview](https://portal.api.kuehne-nagel.com/devportal/apis/fe5ed9e7-67cb-471f-a679-7bdade8d6850/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/integration/event/shipment/event-integration/v1`

#### Tags

- Events
- Integration
- Track and Trace

#### Properties

- [OpenAPI](openapi/kuehne-nagel-shipment-event-integration-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-shipment-event-integration-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-shipment-event-integration-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/fe5ed9e7-67cb-471f-a679-7bdade8d6850/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel ExternalShipmentIntegration API

Upsert or delete an externally-sourced shipment against a Kuehne+Nagel customer code and shipment number — the surface through which non-Kuehne+Nagel shipments are fed into Kuehne+Nagel visibility.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/e4e7a568-9c87-4346-ae85-50e6a9ad0b00/overview](https://portal.api.kuehne-nagel.com/devportal/apis/e4e7a568-9c87-4346-ae85-50e6a9ad0b00/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/integration/external/shipment/v1`

#### Tags

- Integration
- Shipments
- Visibility

#### Properties

- [OpenAPI](openapi/kuehne-nagel-external-shipment-integration-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-external-shipment-integration-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-external-shipment-integration-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/e4e7a568-9c87-4346-ae85-50e6a9ad0b00/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel IntermodalTransportExecution API

Carrier-facing pickup-and-delivery execution for sea intermodal legs — list assigned consignments, pull job documents, post job status, post GPS tracking and post proof of delivery per waypoint. Uses UN/LOCODE ports of loading and discharge and SCAC carrier codes.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/d2822b95-abc5-40f8-b8a6-62e3914a844a/overview](https://portal.api.kuehne-nagel.com/devportal/apis/d2822b95-abc5-40f8-b8a6-62e3914a844a/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/transport/execution/pickup-and-delivery/sea/v1`

#### Tags

- Road Freight
- Ocean Freight
- Telematics
- Proof of Delivery

#### Properties

- [OpenAPI](openapi/kuehne-nagel-intermodal-transport-execution-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-intermodal-transport-execution-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-intermodal-transport-execution-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal.api.kuehne-nagel.com/devportal/apis/d2822b95-abc5-40f8-b8a6-62e3914a844a/documents)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel ShipmentDocumentManagement API v3

List, download, add and delete shipment-related documents against a Kuehne+Nagel unique shipment reference, plus a lookup of uploadable document types. The current version for new integrations.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/e25ce18f-bfe5-47f7-ba14-b6d4acb0c085/overview](https://portal.api.kuehne-nagel.com/devportal/apis/e25ce18f-bfe5-47f7-ba14-b6d4acb0c085/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/transport/execution/documentation/shipment/v3`

#### Tags

- Documents
- Shipments
- Trade Compliance

#### Properties

- [OpenAPI](openapi/kuehne-nagel-shipment-document-management-v3-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-shipment-document-management-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-shipment-document-management-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel ShipmentDocumentManagement API v2

Legacy document management for shipment documents, limited to adding and downloading documents. Marked in the developer portal as legacy and intended for existing integrations only; v3 is directed for new work.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/76b61307-7289-474d-a2e7-06b6ee10ab12/overview](https://portal.api.kuehne-nagel.com/devportal/apis/76b61307-7289-474d-a2e7-06b6ee10ab12/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/transport/execution/documentation/shipment/v2`

#### Tags

- Documents
- Shipments
- Deprecated

#### Properties

- [OpenAPI](openapi/kuehne-nagel-shipment-document-management-v2-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-shipment-document-management-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-shipment-document-management-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel B2B-CustomsEDI API

Described in the developer portal as being for bespoke customs integrations with customers. The published OpenAPI declares two POST operations, /order and /document, with no request schemas, no response schemas and no operation descriptions — an unschematized EDI pass-through rather than a modelled customs API.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/d687d921-913e-429b-a95e-e7bbbd16658c/overview](https://portal.api.kuehne-nagel.com/devportal/apis/d687d921-913e-429b-a95e-e7bbbd16658c/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/b2b/customs/edi/v1`

#### Tags

- Customs
- Trade Compliance
- EDI

#### Properties

- [OpenAPI](openapi/kuehne-nagel-b2b-customs-edi-v1-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-b2b-customs-edi-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-b2b-customs-edi-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

### Kuehne+Nagel KAI Document Extract API

Published in the developer portal as B2B-OldKAIExtractAPI — extract structured information from documents, with workspace management, synchronous and asynchronous file and zip processing, prompt-driven extraction and per-workspace API keys. The largest published surface at 92 paths.

- **Human URL:** [https://portal.api.kuehne-nagel.com/devportal/apis/84ffd55f-61ba-4918-8105-887fdcb88ff6/overview](https://portal.api.kuehne-nagel.com/devportal/apis/84ffd55f-61ba-4918-8105-887fdcb88ff6/overview)
- **Base URL:** `https://gateway.api.kuehne-nagel.com/oldkaiextractapi/0.1.0`

#### Tags

- Documents
- AI
- Document Extraction

#### Properties

- [OpenAPI](openapi/kuehne-nagel-kai-document-extract-v0-1-0-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kuehne-nagel-kai-document-extract-v0-1-0.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kuehne-nagel-kai-document-extract-v0-1-0.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)

## Common Properties

- [Website](https://www.kuehne-nagel.com/)
- [Developer Portal](https://portal.api.kuehne-nagel.com/devportal/)
- [Documentation](https://www.kuehne-nagel.com/digital-services/data-integration)
- [Documentation](https://mykn.kuehne-nagel.com/help-center/connectivity)
- [Portal](https://mykn.kuehne-nagel.com/)
- [Sign Up](https://www.kuehne-nagel.com/contact/digital-data-integration)
- [GitHub Organization](https://github.com/kuehne-nagel)
- [LinkedIn](https://www.linkedin.com/company/kuehne-nagel)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
