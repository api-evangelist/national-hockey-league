# National Hockey League (national-hockey-league)

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

The National Hockey League (NHL) is the premier professional ice hockey league in North America, comprised of 32 franchises across the United States and Canada. The NHL produces the Stanley Cup playoffs and is one of the major North American professional sports leagues. The NHL does not publish an officially documented developer portal; the league operates undocumented JSON endpoints used by its first-party web and mobile apps (api-web.nhle.com) and provides advanced statistics through NHL EDGE. Commercial data feeds are licensed through SMT, Sportradar, and other approved partners.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/national-hockey-league/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/national-hockey-league/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Sports
- Hockey
- Entertainment
- Professional League

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-23

## APIs

### NHL Web API

Public but undocumented JSON API that powers NHL.com and the league's first-party web and mobile apps. Surfaces schedules, scores, play-by-play, standings, teams, players, draft, prospects, season standings, and franchise records. Widely consumed by the hockey-analytics and fan-tools community even though the NHL does not publish formal documentation or a rate-limit policy.

- **Human URL:** [https://api-web.nhle.com/](https://api-web.nhle.com/)
- **Base URL:** `https://api-web.nhle.com/`

#### Tags

- Sports
- Hockey
- Stats
- Scores
- Schedule

#### Properties

- [Postman Collection](collections/national-hockey-league.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/national-hockey-league.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NHL Stats API (Legacy)

Legacy statistics endpoint at api.nhle.com (and the older statsapi.web.nhl.com) used by community projects and analytics tools. Hosts deeper historical records, play-by-play, and shift data. Like the web API, this surface is undocumented and consumed via reverse-engineered conventions.

- **Human URL:** [https://api.nhle.com/](https://api.nhle.com/)
- **Base URL:** `https://api.nhle.com/`

#### Tags

- Sports
- Hockey
- Stats
- Historical Data
- Play-by-Play

#### Properties

- [Postman Collection](collections/national-hockey-league.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/national-hockey-league.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/national-hockey-league)
- [Website](https://www.nhl.com/)
- [Stats](https://www.nhl.com/stats/)
- [N H L Edge](https://edge.nhl.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
