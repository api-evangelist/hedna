# HEDNA (hedna)

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
