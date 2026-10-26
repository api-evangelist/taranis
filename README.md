# Taranis (taranis)

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

Taranis is an AI-powered crop intelligence company that delivers full-service, leaf-level aerial scouting for agricultural advisors, retailers, and growers. Its AcreForward platform captures submillimeter drone and satellite imagery and applies computer vision and generative AI (Ag Assistant) to detect weeds, pests, disease, nutrient deficiencies, and stand counts, turning insights into measurable yield outcomes. Taranis is delivered as a closed SaaS platform (web dashboard and mobile apps); no public or partner developer API is documented as of this writing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/taranis/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/taranis/refs/heads/main/apis.yml)

## Tags

- Agriculture
- AgTech
- Crop Intelligence
- Computer Vision
- Aerial Scouting
- Precision Agriculture

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Taranis Crop Intelligence

Leaf-level crop intelligence delivered through the AcreForward platform using submillimeter aerial imagery and computer vision to detect weeds, insect damage, disease pressure, nutrient deficiencies, and stand counts. Delivered as a SaaS product surface, not a documented public API.

- **Human URL:** [https://www.taranis.com/](https://www.taranis.com/)

#### Tags

- Crop Intelligence
- Aerial Scouting
- Computer Vision

#### Properties

- [Documentation](https://www.taranis.com/)
- [Documentation](https://go.taranis.com/acreforward/)
- [OpenAPI](openapi/taranis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taranis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taranis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taranis Imagery and Insights

Field health imagery, agronomic insights, and Yield Impact reporting that convert leaf-level observations into measurable bushel and yield outcomes, surfaced through the Taranis web dashboard and mobile apps. No documented public API exposes these insights programmatically.

- **Human URL:** [https://go.taranis.com/acreforward/](https://go.taranis.com/acreforward/)

#### Tags

- Imagery
- Insights
- Yield Impact

#### Properties

- [Documentation](https://go.taranis.com/acreforward/)
- [Documentation](https://knowledge.taranis.ag/portal/en/kb)
- [OpenAPI](openapi/taranis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taranis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taranis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taranis Ag Assistant

Generative AI agronomy engine that contextualizes Taranis leaf-level data with weather, machinery, and research data to generate product, nutrient, and input recommendations. Exposed as an in-platform assistant feature, not a documented developer API.

- **Human URL:** [https://go.taranis.com/ag-assistant/](https://go.taranis.com/ag-assistant/)

#### Tags

- Generative AI
- Agronomy
- Recommendations

#### Properties

- [Documentation](https://go.taranis.com/ag-assistant/)
- [Documentation](https://www.taranis.com/newsroom/ag-assistant/)
- [OpenAPI](openapi/taranis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taranis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taranis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taranis Platform Integrations

Channel and data partnerships (e.g., Syngenta Crop Protection, Ag Partners / Nutrien) and ingestion of machinery and weather data that power AcreForward. These are commercial and operational integrations; no self-serve partner API or developer program is publicly documented.

- **Human URL:** [https://go.taranis.com/ag-partners/](https://go.taranis.com/ag-partners/)

#### Tags

- Integrations
- Partners
- Data

#### Properties

- [Documentation](https://go.taranis.com/ag-partners/)
- [OpenAPI](openapi/taranis-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taranis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taranis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/taranis-visual)
- [Website](https://www.taranis.com/)
- [Documentation](https://knowledge.taranis.ag/portal/en/kb)
- [Plans](plans/taranis-plans-pricing.yml)
- [Rate Limits](rate-limits/taranis-rate-limits.yml)
- [Fin Ops](finops/taranis-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
