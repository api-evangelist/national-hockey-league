# National Hockey League (national-hockey-league)

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
