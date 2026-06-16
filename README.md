# Charter Communications (charter)

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

### Bryte IQ Network-as-a-Service API

Bryte IQ is Charter Communications' NaaS developer platform built on the Linux Foundation's CAMARA open API framework. Launched in September 2024, it provides secure, privacy-friendly APIs for third-party developers to build services that interact with Charter's internet and mobile networks, including connected device visibility, CPE management, home network optimization, and subscriber service controls. Access is provided through an authenticated developer portal with application registration and onboarding.

- **Human URL:** [https://corporate.charter.com/newsroom/charter-and-cablelabs-launch-bryte-iq-network-as-a-service-platform](https://corporate.charter.com/newsroom/charter-and-cablelabs-launch-bryte-iq-network-as-a-service-platform)
- **Base URL:** `https://bryteiq.spectrum.com`

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
