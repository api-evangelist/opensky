# OpenSky Network (opensky)

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

Open-source flight tracking network with a REST API for accessing real-time and historical ADS-B aircraft state vectors, flight tracks, and airport arrivals and departures. The network is powered by a community of volunteer ADS-B receiver operators and is intended for non-commercial research and educational use.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/apis.yml)

## Tags

- Aviation
- Flight Tracking
- ADS-B
- Aircraft
- Airport
- Real-Time
- Historical Data

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### OpenSky Network REST API

REST API for retrieving real-time and historical ADS-B aircraft state vectors, flight tracks, and airport arrival and departure data from the OpenSky Network crowd-sourced receiver network.

- **Human URL:** [https://openskynetwork.github.io/opensky-api/rest.html](https://openskynetwork.github.io/opensky-api/rest.html)
- **Base URL:** `https://opensky-network.org/api`

#### Tags

- Aircraft State Vectors
- Flight Tracks
- Airport Arrivals
- Airport Departures
- ADS-B

#### Properties

- [Documentation](https://openskynetwork.github.io/opensky-api/rest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/openapi/opensky-rest-api.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://openskynetwork.github.io/opensky-api/rest.html#authentication)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/rate-limits/opensky-rest-api.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/plans/opensky-rest-api.yml)

### OpenSky Network Trino Historical Data API

SQL query interface powered by Trino for accessing the full OpenSky historical dataset including state vectors, raw Mode S messages, ADS-C and MLAT data, and flight records. Available to university-affiliated researchers, governmental organisations, and aviation authorities.

- **Human URL:** [https://openskynetwork.github.io/opensky-api/trino.html](https://openskynetwork.github.io/opensky-api/trino.html)
- **Base URL:** `https://trino.opensky-network.org`

#### Tags

- Historical Data
- State Vectors
- Mode S
- ADS-C
- MLAT
- SQL

#### Properties

- [Documentation](https://openskynetwork.github.io/opensky-api/trino.html)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/rate-limits/opensky-trino-api.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/plans/opensky-trino-api.yml)

## Common Properties

- [Git Hub](https://github.com/openskynetwork)
- [Git Hub  Repository](https://github.com/openskynetwork/opensky-api)
- [Documentation](https://openskynetwork.github.io/opensky-api/)
- [Terms of Service](https://opensky-network.org/about/terms-of-use)
- [Status](https://opensky-network.org/network/status)
- [Login](https://opensky-network.org/login)
- [Register](https://opensky-network.org/register)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/opensky/refs/heads/main/finops/opensky.yml)
- [Contact](https://opensky-network.org/about/contact)
- [Forum](https://community.opensky-network.org)
- [Twitter](https://twitter.com/openskynetwork)

## Maintainers

**FN:** API Evangelist
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
