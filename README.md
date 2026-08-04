# Charter Communications (charter)

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

Charter Communications, operating under the Spectrum brand, is the second-largest cable operator in the United States serving more than 32 million customers across 41 states. Charter offers REST APIs for enterprise network provisioning, service account management, broadband diagnostics, customer support ticket automation, and circuit serviceability. The Spectrum Enterprise Open API enables B2B integrations for ticketing, circuit management, and network operations. Charter's Bryte IQ platform, built on the Linux Foundation's CAMARA framework, provides NaaS (Network-as-a-Service) APIs enabling third-party developers to build services that interact with Charter's wired and wireless networks, including connected device visibility, CPE management, and home network support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/charter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/charter/refs/heads/main/apis.yml)

## Tags

- Telecommunications
- Internet Service Provider
- Cable
- Network Provisioning
- Broadband
- Spectrum
- NaaS
- Enterprise

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Spectrum Enterprise Client API

The Spectrum Enterprise Open API provides B2B REST API access for enterprise clients to integrate directly with the Spectrum Enterprise portal. It supports automated ticket creation and management, circuit and site account retrieval, network alarm submission, and serviceability lookups. Authentication uses OAuth 2.0 client credentials via the PiNxt onboarding platform.

- **Human URL:** [https://enterprise.spectrum.com/support/faqs/api-faqs.html](https://enterprise.spectrum.com/support/faqs/api-faqs.html)
- **Base URL:** `https://apis.spectrum.net`

#### Tags

- Enterprise
- Ticketing
- Circuit Management
- Network Alarms
- OAuth 2.0

#### Properties

- [Documentation](https://enterprise.spectrum.com/content/dam/spectrum/enterprise/en/pdfs/support/SE-B2B-API-Guide-v1.905.pdf)
- [Terms of Service](https://enterprise.spectrum.com/legal/terms-and-conditions/customer-api-terms-and-conditions-for-enterprise-services.html)


#### Tags

- NaaS
- CAMARA
- Network
- IoT
- Home Network
- Broadband

#### Properties

- [Documentation](https://corporate.charter.com/newsroom/charter-and-cablelabs-launch-bryte-iq-network-as-a-service-platform)

### Spectrum Carrier Serviceability API

The Spectrum Carrier Serviceability API enables carrier partners to submit address serviceability requests to determine Charter network coverage. Supports both single-address and batch address serviceability lookups. Authentication uses OAuth 2.0 and the API follows REST conventions with JSON payloads.

- **Human URL:** [https://enterprise.spectrum.com/support.html](https://enterprise.spectrum.com/support.html)
- **Base URL:** `https://eli-ws-carrier.charter.com`

#### Tags

- Serviceability
- Carrier
- Address Lookup
- OAuth 2.0

#### Properties

- [Documentation](https://enterprise.spectrum.com/support.html)

## Common Properties

- [Website](https://www.spectrum.com)
- [Corporate Website](https://corporate.charter.com)
- [Enterprise Website](https://enterprise.spectrum.com)
- [Documentation](https://enterprise.spectrum.com/support/faqs/api-faqs.html)
- [Git Hub Org](https://github.com/charter)
- [LinkedIn](https://www.linkedin.com/company/charter-communications)
- [Blog](https://corporate.charter.com/newsroom)
- [Pricing](plans/charter-plans-pricing.yml)
- [Rate Limits](rate-limits/charter-rate-limits.yml)
- [Fin Ops](finops/charter-finops.yml)
- [Status Page](https://statusgator.com/services/charter-communications)
- [X (Twitter)](https://x.com/CharterNewsroom)
- [Plans](plans/charter-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
