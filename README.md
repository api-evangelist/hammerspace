# Hammerspace

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Hammerspace, Inc. builds the Hammerspace Global Data Platform — a parallel file system and
software-defined data platform that unifies unstructured data across on-premises storage, edge
sites, AWS, Azure and Google Cloud into a single global namespace. Data is reached over NFS,
pNFS v4.2 with Flex Files, SMB, S3 and CSI, while placement, tiering, replication, snapshots and
retention are driven by declarative objectives. The 2026 AI Data Platform adds Tier-0 NVMe pooling
on GPU servers, an integrated Milvus vector database, and Model Context Protocol services for AI
agents and RAG pipelines.

## API surface

Hammerspace's programmatic control plane is the **Anvil management REST API** at the base path
`/mgmt/v1.2/rest`, served by each customer's own Anvil metadata server rather than from a
Hammerspace-hosted endpoint.

**Hammerspace publishes no OpenAPI, Swagger, or public API reference.** `/openapi.json`,
`/swagger.json` and `/api-docs` were probed on every Hammerspace host and the whole
`github.com/hammer-space` organization was searched; nothing exists publicly. Product documentation
ships with the software and through the gated customer support portal. Every convention recorded in
this repo is evidenced instead in Hammerspace's own Apache-2.0 open source clients — the Kubernetes
CSI driver's Go client and the Ansible operations playbooks.

- Website — https://hammerspace.com/
- GitHub organization — https://github.com/hammer-space
- Resources (incl. the AWS Marketplace Deployment Guide) — https://hammerspace.com/resources/
- Support portal (login required) — https://supportportal.hammerspace.com/

Surfaced via the API Evangelist harvest backlog (source: secondary-market —
https://forgeglobal.com/hammerspace_stock/).
