# Business Model: Independent MLIT Construction-Business Licensing Compliance Service — Japan (MLIT)

## Classification

- Repository: `cloud-itonami-iso3166-jpn-mlit`
- ISO 3166 (agency-level): `JPN-MLIT`, parent `JPN`
- Ooyake cross-reference: `gov.jpn.mlit` (Ministry of Land, Infrastructure, Transport and Tourism / 国土交通省)
- Activity: construction-business licensing (建設業許可) under the Construction Business Act (建設業法) for an operator bidding on public-works infrastructure contracts, and building-code (建築基準法) compliance for a delivered structure
- Social impact: [:construction-license-clarity :infrastructure-market-access :public-spend-transparency]

## Customer

- an operator bidding on a public-works infrastructure contract that requires a construction-business license (建設業許可)
- an operator whose delivered structure must comply with the Building Standards Act (建築基準法)
- a foreign construction/engineering firm confirming Japanese licensing prerequisites before bidding

## Offer

- construction-business license (建設業許可) classification and application checklist
- building-code (建築基準法) compliance walkthrough for the delivered structure
- ongoing regulatory-change monitoring for MLIT licensing-rule updates
- compliance-audit export package for the operator's own records

## Revenue

- per-engagement compliance-review fee
- recurring regulatory-change monitoring subscription
- compliance-audit export package

## Trust Controls

- any actual filing, registration, or compliance-program submission
  requires Construction-Licensing Compliance Governor clearance and always escalates to human
  sign-off (`:filing/submit` is never automated at any phase)
- a false or fabricated regulatory-requirement claim is a HARD hold that
  cannot be overridden by human approval alone — it must be corrected
  against a cited MLIT source first
- this service does **not** provide legal or tax advice; characterization
  and filing on the client's behalf beyond checklist/draft assistance
  routes to Japan-licensed counsel or a registered agent
- every requirement cites the official MLIT source or
  regulation, never invented

## Boundary with adjacent actors (read before forking)

- **`cloud-itonami-iso3166-jpn`**: the COUNTRY-level coordinator (general
  Japan public-sector market entry). This repo is a narrower, deeper
  AGENCY-level leaf — most operators need the country-level blueprint plus
  only the agency-level blueprints that actually apply to their contract.
- **`com-etzhayyim-ooyake`** (etzhayyim/root): read-only civic-wayfinding
  mirror of government structure, non-commercial, barred from acting as or
  for the government (G3 impersonation ban). This blueprint is commercial
  and never claims to be Ministry of Land, Infrastructure, Transport and Tourism or an official channel.
- **`matsurigoto`** (etzhayyim/root): sovereign e-government statecraft —
  literally the government. This blueprint is an independent operator that
  engages with MLIT under its public rules — never the
  agency itself.
- **`com-etzhayyim-toritsugi`** (etzhayyim/root): guides a consenting
  INDIVIDUAL citizen through their OWN procedure, non-profit,
  donation-only. This blueprint's client is a business operator, not an
  individual citizen, and it is commercial.
- **`cloud-itonami-M6910`**: helps a client BECOME a legal entity
  (incorporation, ISIC 6910) — a prior, different regulatory phase (company
  law). This blueprint assumes incorporation is already done and handles
  MLIT-specific compliance (a different regulatory domain).
- **`cloud-itonami-cofog-05.1`** (Independent Municipal Waste Collection
  Robotics, MOE blueprint only): a jurisdiction-agnostic LOCAL operator
  template for the waste-collection function itself. This blueprint is the
  NATIONAL regulatory-agency side (MOE permits) an operator needs
  regardless of which municipality it serves.
