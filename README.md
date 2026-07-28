# HEDNA (hedna)

HEDNA (Hotel Electronic Distribution Network Association) is a not-for-profit trade association founded in 1991 and headquartered in Forest Hill, Maryland, United States, that convenes the hotel distribution industry — hotel chains, GDS operators, OTAs, switches, channel managers, payment providers and connectivity vendors — around shared best practice for hospitality electronic distribution. It sits alongside rather than inside the distribution chain: it moves no inventory and processes no bookings, but its Disciplines (Connectivity, Content Distribution, Payments, Data & Analytics, Revenue Optimization) produce recommendation documents, and it co-authored the Open Payments Alliance Standards Specification with HTNG and OpenTravel. HEDNA publishes no developer portal, no API, and no machine-readable specification on hedna.org; every probe of developer./developers./docs./api. subdomains and of /developers, /api, /docs, /openapi.json, /swagger.json, /api-docs and /.well-known/ failed (DNS failure or HTTP 404). Its publications library, research reports and HEDNA U courseware are gated behind paid membership at members.hedna.org (HTTP 403 Cloudflare challenge unauthenticated) and pathlms.com/hedna. Honest posture: member-gated documents, no public API, no exit path published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hedna/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hedna/refs/heads/main/apis.yml)

## Tags

- Travel
- United States
- Hospitality
- Hotels
- Distribution
- Booking
- GDS
- Standards
- Trade Association

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

No public APIs are published by HEDNA. As a trade association it publishes prose recommendations and member-gated research rather than a developer surface. See [review.yml](review.yml) for the full probe record, including the incidental WordPress REST API at `https://www.hedna.org/wp-json/` that was confirmed live but deliberately not listed as a HEDNA API offering.

## Switching Cost

- **Interface shape:** none-published — no API contract of any kind.
- **Second source:** alternatives-with-migration — OpenTravel Alliance, AHLA, HSMAI and Phocuswright cover adjacent ground; HTNG, the closest peer, no longer resolves independently.
- **Exit path:** no-export-published — access/correct/delete on request in the privacy policy, no portability or export commitment.
- **Identifier portability:** HEDNA issues no industry identifiers; its guidance sits over GDS chain and property codes minted by others. Only an opaque YourMembership member record is HEDNA-controlled.
- **Contractual lock-in:** published annual dues $50–$1,950 across seven categories; no minimum term, exclusivity or termination notice published.
- **Access gate:** none-published for developers; paid annual membership (plus Board approval for three categories) for the document library.
- **Distribution model:** not-applicable. **NDC posture:** not applicable — NDC is an air standard, HEDNA's remit is hotels.

## Artifacts

- [llms/hedna-llms.txt](llms/hedna-llms.txt) — generated llms.txt, written mainly as a negative signal so agents do not hallucinate a HEDNA API.
- [security/hedna-domain-security.yml](security/hedna-domain-security.yml) — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC posture (TLSv1.3, SPF present; no HSTS, DNSSEC, CAA or DMARC).
- [well-known/hedna-well-known.yml](well-known/hedna-well-known.yml) — recorded absence: every `/.well-known/` path returns 404. Deliberately not wired as a `WellKnown` pointer, because there is nothing to point at.

No `openapi/`, `asyncapi/`, `mcp/`, `skills/`, `scopes/`, `authentication/`, `errors/`, `lifecycle/`, `conventions/`, `sandbox/`, `cli/` or `components/` artifacts exist here — each requires an API contract HEDNA does not publish. See [review.yml](review.yml) `enrichment:` for the round-2 probe record.

## Common Properties

- [Website](https://www.hedna.org/)
- [About](https://www.hedna.org/who-we-are/)
- [Blog](https://www.hedna.org/blog/)
- [Blog RSS](https://www.hedna.org/feed/)
- [Membership](https://www.hedna.org/membership/)
- [HEDNA U](https://www.hedna.org/hedna-u/)
- [Committees and Disciplines](https://www.hedna.org/hednacommittees/)
- [Events](https://www.hedna.org/events/)
- [Global Conferences](https://www.hedna.org/global-conferences/)
- [Sponsorship](https://www.hedna.org/sponsorship/)
- [Insights](https://www.hedna.org/insights/)
- [Members-Only Portal](https://members.hedna.org/)
- [Member Registration](https://members.hedna.org/general/register_member_type.asp)
- [Member Login](https://members.hedna.org/login.aspx)
- [Get Involved](https://www.hedna.org/get-involved/)
- [HEDNA Conferences (iOS)](https://apps.apple.com/ca/app/hedna-conferences/id6749077685)
- [HEDNA Conferences (Android)](https://play.google.com/store/apps/details?id=com.xcdsystem.hedna)
- [Privacy Policy](https://www.hedna.org/privacy-user-consent/)
- [Code of Conduct](https://www.hedna.org/code-of-conduct/)
- [LinkedIn](https://www.linkedin.com/groups/79116)
- [YouTube](https://www.youtube.com/channel/UCr5sBUgES3SZkMVgC7E5k_A)
- [Email](mailto:info@hedna.org)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
