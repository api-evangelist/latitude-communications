# Latitude Communications

Latitude Communications, Inc. was a Santa Clara, California enterprise conferencing company,
incorporated in April 1993 and venture-backed by Mayfield Fund, Menlo Ventures, Asset Management
Associates, and Canaan Ventures (Canaan Partners).

It developed, sold, and hosted **MeetingPlace**, an integrated voice and web conferencing system for
geographically dispersed enterprises. MeetingPlace shipped commercially in December 1994 and had been
sold to more than 430 enterprise customers by the end of 2002 — including Aetna, Cisco, Credit Suisse
First Boston, Fidelity Investments, Lockheed Martin, Oracle, and the U.S. Federal Reserve Bank. It was
offered both as an outsourced hosted service billed on usage and as an on-premises licensed platform.

The company IPO'd on the Nasdaq National Market under the symbol **LATD** at $12.00 per share in May
1999. Cisco Systems acquired Latitude in a cash merger at $3.95 per share, completed in late 2003;
Latitude filed a Form 15 terminating its SEC registration on 2004-01-13. MeetingPlace was absorbed
into Cisco's conferencing line as Cisco Unified MeetingPlace.

- **Status:** acquired (2003)
- **Acquired by:** [Cisco Systems, Inc.](https://www.cisco.com/) — $3.95 per share in cash
- **Backed by:** canaan-partners (verified — 5.0% pre-IPO holder in the 424B4)
- **Founded:** April 1993
- **Headquarters:** 2121 Tasman Drive, Santa Clara, CA 95054
- **SEC:** CIK 0001078425, file number 000-25475, SIC 7373 — deregistered 2004-01-13
- **Sector:** enterprise software / unified communications / conferencing

### Revenue (per SEC filings)

| Year | Revenue | Net result |
|---|---|---|
| 2000 | $43.4M | $1.7M net income |
| 2001 | $33.9M | $7.4M net loss |
| 2002 | $40.5M | $18.5M net loss |

## No API surface

This entity is defunct and never published a public API, developer portal, SDK, CLI, specification,
or machine-readable interface. Its 2002 10-K describes only *internally developed* APIs used to
integrate MeetingPlace with web servers, e-mail systems, and fax servers — there was no public
developer program.

The enrichment pipeline was run on 2026-07-19 and produced **no artifacts**. There is nothing to
harvest, and fabricating any would be unfaithful to the record. Critically, the company's original
hosts no longer belong to it, so they were **not** probed for well-known, domain-security, or
vulnerability-disclosure artifacts — doing so would attribute a third party's posture to Latitude.

| Probe (2026-07-19) | Status | Note |
|---|---|---|
| `https://latitude.com/` | 200 | Parked page embedding a Google Form. No company information. Not Latitude Communications. |
| `https://latitude.com/.well-known/security.txt` | 404 | |
| `https://latitude.com/llms.txt` | 404 | |
| `https://latitude-communications.com/` | 403 | Unverified; not a Latitude Communications property. |
| `https://meetingplace.net/` | — | TLS failure, no matching certificate subject. The former MeetingPlace product site (live in 2002 per the Internet Archive) is no longer operated. |

## Name collisions — this is not the same company

| Name | URL | Relationship |
|---|---|---|
| Latitude.sh | https://www.latitude.sh/ | **Unrelated.** Global bare-metal and GPU cloud infrastructure provider across 25 locations. It *does* publish a real public API, developer portal, Go and Node SDKs, a CLI, and a Terraform provider (probed 2026-07-19: site and `docs.latitude.sh` both HTTP 200). Founded decades later. Do not merge these profiles or attribute latitude.sh artifacts here. |
| latitude.com (present day) | https://latitude.com/ | **Domain changed hands.** Latitude Communications used this domain through at least 2002 (Internet Archive snapshot 2002-05-29 shows the MeetingPlace marketing site). It now serves a bare Google Form page with no company identification, registered through GoDaddy. |

## Sources

- SEC EDGAR filing history — [CIK 0001078425](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001078425&type=&dateb=&owner=include&count=40) (71 filings, 1999-02-25 through 2004-02-10)
- [Form 10-K for FY2002](https://www.sec.gov/Archives/edgar/data/1078425/000104746903010827/a2106667z10-k.htm) — business description, revenue, customers, internal APIs
- [424B4 IPO prospectus, 1999-05-07](https://www.sec.gov/Archives/edgar/data/1078425/0001012870-99-001455.txt) — founding date, LATD listing, $12.00 offering price, principal stockholders
- [DEFM14A merger proxy, 2003-12-03](https://www.sec.gov/Archives/edgar/data/1078425/000104746903039065/a2123881zdefm14a.htm) — Cisco merger at $3.95 per share
- [Form 15, 2004-01-13](https://www.sec.gov/Archives/edgar/data/1078425/000119312504003452/d1512g.htm) — deregistration
- [Internet Archive, latitude.com 2002-05-29](http://web.archive.org/web/20020529230735/http://latitude.com:80/)
