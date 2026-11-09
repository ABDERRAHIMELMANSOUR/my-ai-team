# Target Audience & Acquisition Strategy — ALM Assurances / CPA Assurances

**Version:** 1.0  
**Date:** 9 November 2026  
**Scope:** French insurance brokerage lead generation through Google Ads and Meta Ads, supported by SEO and reliable CRM delivery.  
**Contributors:** Paid Ads Specialist, Web Developer, and SEO Expert; consolidated by the Team Lead.

## 1. Strategic brief and evidence status

The objective is to acquire **contactable, eligible prospects who progress to quotations and issued, retained policies**, at a sustainable acquisition cost. Raw form volume is an intermediate metric.

The business owner identifies ALM Assurances ([alm-assurances.fr](https://alm-assurances.fr/)) and CPA Assurances ([groupe-cpa.fr](https://groupe-cpa.fr/)) as the two brands, and specifies this operating architecture:

**Google / Meta → product landing page → form → Assurpilot → Make.com webhooks → AZUR for Santé / ProAssur for Auto.**

This document defines the proposed operating strategy around that architecture. It does not establish that integrations, account permissions, CRM mappings, advertising verification, or consent configurations have been tested.

Public-page review on the document date found product and callback/quote forms on ALM. The Auto card contained habitation savings wording, and Auto/Habitation contact disclosures referred to Santé. Correct these product-copy inconsistencies before reusing the content; this observation alone is not a legal or technical audit. CPA could not be retrieved through the research tool, which does not establish that the site is unavailable to users. Neither site's forms were submitted. [Source: ALM homepage](https://alm-assurances.fr/)

No ad-account, conversion, commission, or retention data was provided. ICPs, campaign priorities, and experiments below are hypotheses to validate. Numerical CPL, sales, ROI, and budget promises would be premature.

## 2. Target market and geography

### Core market

French-speaking customers seeking insurance for risks that the brokerage's partner insurers can actually cover:

- **Particuliers:** individuals and households comparing complementary health, vehicle, or home insurance.
- **TNS:** independent workers, artisans, merchants, and liberal professionals seeking suitable complementary health cover and practical adviser support.
- **Building professionals:** a separate professional audience for Décennale, including eligible independent tradespeople and businesses. Do not merge this journey with household insurance.

Use French copy, French contact conventions, EUR reporting, and Europe/Paris for business reporting and callback scheduling. Store technical timestamps in UTC.

### Geographic operating rules

Treat metropolitan France, including Corsica, as a **candidate service area subject to insurer eligibility**, rather than an automatic nationwide coverage promise. Check overseas departments and collectivities separately; include them only when carrier coverage, pricing, and adviser operations support them.

Before activation, maintain an eligibility matrix by product, postcode/department, insurer, and brand. Use available location-presence targeting to focus paid media on serviceable areas, verify the current platform settings, and validate the insured risk's location in the form. Ad location is not proof of insurance eligibility.

Start with regions where underwriting availability and adviser capacity are established. Expand using qualified-lead economics and operational capacity, not assumed regional purchasing power. Avoid dozens of thin location pages without a distinct local service.

### Brand roles

Keep brand identity visible from ad to landing page, privacy notice, adviser contact, and CRM record. Preserve the originating brand even if both brands use shared operations.

Before launch, assign a preferred brand and landing page to each non-brand product/intent cluster. This is a planning decision, not an assertion that ALM or CPA currently owns a particular segment. Coordinate shared auctions and query coverage rather than letting two accounts bid against each other without a deliberate reason. Preserve legitimate branded navigational demand; brand ownership does not imply blanket cross-brand negative keywords. Any transfer between entities needs transparent handling and appropriate authorization.

## 3. Ideal customer profiles

Segment by expressed need, insurable situation, and buying intent. These are service-design profiles, not permission to infer sensitive traits for advertising audiences.

| ICP | Situation and pain points | Value proposition and objection handling | Useful qualification |
| --- | --- | --- | --- |
| Santé: price-conscious individual or household | Premium feels expensive; benefits are difficult to compare; wants savings without losing essential protection | Compare suitable guarantees, reimbursement limits, exclusions, and cost; explain trade-offs without promising a fixed saving | Individual/family, broad coverage priorities, postcode, desired start date, optional budget range |
| Santé: changing household needs | Coverage no longer seems aligned with household composition or priorities; concerned about gaps and complexity | Clear explanation and adviser-led comparison; understandable choices and next steps | People to cover, broad benefit priorities, timing; detailed information only when justified |
| Santé TNS | Self-employed person balancing budget, household protection, administrative time, and professional constraints | Suitable cover and simple adviser support; predictable comparison process | TNS status, people to cover, postcode, start date, contact preference |
| Auto: standard value seeker | Existing premium feels high; wants an easier comparison or is changing vehicle | Compare guarantees, excesses, and price for the stated driver/vehicle | Vehicle/use category, postcode, desired date, broad driver/bonus information |
| Auto: insurer-cancelled applicant | Previous cancellation or rejection creates uncertainty and urgency | An adviser examines the declared situation against available insurer criteria; explain required documents and limits | Cancellation category/date where needed, cover end date, vehicle use, contact preference |
| Auto: claims history or malus | Repeated claims or a malus may narrow options or raise price | Transparent examination of options and guarantees; non-judgmental help | Necessary high-level claims/bonus-malus information, licence history, effective date |
| Auto: urgent quotation seeker | Vehicle acquisition or ending coverage creates a short decision window | Clear next steps and realistic adviser availability; separate quote request from actual cover activation | Desired date, vehicle readiness, callback availability; no assumption of immediate acceptance |

Do not promise universal acceptance, immediate cover, the lowest price, or unsupported percentage savings. Service Public describes the BCT route for certain refusal situations and its scope as mandatory liability coverage; it is not a brokerage guarantee of comprehensive cover. [Source: Service Public](https://www.service-public.gouv.fr/particuliers/vosdroits/F2660)

For TNS, any tax-benefit messaging must be reviewed against the individual's situation and applicable conditions; avoid a universal “tax deductible” headline.

**Secondary product ICPs:**

- **Habitation:** tenants, owners, and other supported occupancy situations, especially a move or contract review. Qualify occupancy, property type, location, and date before detailed quotation.
- **Décennale:** supported building trades seeking suitable cover for declared activities. Qualify professional activity, experience, turnover band, prior insurance, geography, and timing only as needed. Avoid implying that a generic policy covers every trade or an already-started project.

## 4. Channel and messaging strategy

### Google Ads: capture expressed demand

Organize campaigns by brand/non-brand, product, and meaningful intent:

| Intent cluster | Illustrative query themes | Landing-page focus |
| --- | --- | --- |
| Santé particuliers | devis mutuelle santé, comparer complémentaire santé | Cost versus appropriate guarantees |
| Santé TNS | devis mutuelle TNS, complémentaire indépendant | Independent-worker needs and simple advice |
| Auto standard | devis assurance auto, comparer assurance voiture | Vehicle/driver fit, cover, and price |
| Auto complex profiles | assurance auto résilié devis, assurance auto malus | Eligibility examination and next steps |
| Habitation | devis assurance habitation | Occupancy and property-specific request |
| Décennale | devis assurance décennale + supported trade | Declared activity and professional qualification |

These examples are research seeds, not verified keyword volumes or approved ad text. Review actual search terms and negatives regularly. Exclude irrelevant recruitment, training, and customer-service traffic where appropriate, without accidentally excluding intended complex Auto profiles.

Check applicable Google financial-services verification for French insurance advertising before activation; no account verification is confirmed here. [Source: Google Ads](https://support.google.com/adspolicy/answer/15332527?co=GENIE.CountryCode%3DFR&hl=en-GB)

### Meta Ads: create consideration

Test neutral benefit-led and educational creative against product-matched landing pages: understandable comparison, adviser support, and a simple request process. Example hypotheses:

- Santé: “Comparez des garanties adaptées à votre budget.”
- TNS: “Une complémentaire santé à étudier selon votre activité et vos besoins.”
- Auto: “Des solutions d'assurance auto à étudier selon votre profil.”

Do not write copy that claims to know a person's medical condition, financial hardship, or cancellation status. Do not build condition-based audiences or transmit health or cancellation details to advertising systems. Verify the current product/country/account-specific audience and category requirements before launch.

Start with website landing-page conversion campaigns. Native lead forms are a later experiment only after equivalent qualification, disclosure, source attribution, consent evidence, and CRM routing are validated.

### Experiment order

1. Establish separate, functional Santé and Auto journeys with reliable lead delivery.
2. Compare standard versus complex Auto intent and particuliers versus TNS Santé.
3. Test one variable at a time: value proposition, form length, CTA, or reassurance placement.
4. Evaluate qualified-lead and policy outcomes with sufficient cohort maturity.
5. Expand spend and secondary products only when operational and economic evidence supports it.

Avoid arbitrary fixed budget splits. Allocate from an approved test budget using learning needs, adviser capacity, downstream value, and marginal acquisition cost.

## 5. Landing pages, SEO, and conversion experience

Proposed intent paths include `/mutuelle-sante/`, `/mutuelle-tns/`, `/assurance-auto/`, `/assurance-auto-resilie/`, `/assurance-auto-malus/`, `/assurance-habitation/`, and `/assurance-decennale/`. Audit existing URLs before implementation; these are not claims that the paths exist. Create separate résilié/malus pages only when each provides distinct useful content and a supported offer; do not multiply thin near-duplicates.

Each page should contain a matching headline, concise value proposition, eligibility explanation, relevant benefits and limits, clear form, next-step explanation, broker identity, verified registration information, contact details, and accessible privacy information. Use testimonials or comparative claims only with evidence and permission.

**CTA must describe the actual service.** Use “Demander mon devis” where the flow initiates a quotation request. If it only requests adviser contact, use “Être rappelé pour un devis.” A received request is not a completed quotation, a policy, or activated cover. Publish callback time promises only after operational validation.

Use crawlable semantic HTML, a logical heading hierarchy, unique page titles and descriptions, meaningful internal links, and substantive helpful content. Keep useful canonical product pages indexable. Use clean canonical URLs for tracking variants; deliberately excluded confirmation pages and duplicate campaign variants may use `noindex` while remaining crawlable. Do not add `noindex` to every paid landing page.

Across ALM and CPA, create distinct propositions and content. Use self-canonicals for distinct useful pages; use cross-domain canonicals only when deliberately consolidating genuinely duplicate content. [Source: Google Search canonicalization guidance](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)

Prioritize mobile forms with programmatic labels, keyboard operation, accessible error focus, clear errors, progressive enhancement where feasible, stable layout, readable text, and accessible tap targets. Proposed performance objectives are p75 LCP ≤ 2.5 s, INP ≤ 200 ms, and CLS ≤ 0.1, measured separately for mobile and desktop. These are targets, not measured results. [Source: Core Web Vitals](https://web.dev/articles/vitals)

## 6. Funnel and CRM architecture

### Logical flow

```text
Google Ads / Meta Ads
  → brand + product landing page
  → accessible form and relevant disclosures
  → same-origin server: validate, normalize, rate-limit
  → durable receipt / delivery outbox
  → Assurpilot: create or update operational lead
  → authenticated event to Make.com
      → validate brand + product + schema
      → Santé / Santé TNS → AZUR
      → Auto              → ProAssur
      → Habitation / Décennale / unknown → controlled manual triage
  → CRM acknowledgment and adviser assignment
  → contact → qualified lead → quotation → issued policy → retention
```

The durable receipt/outbox is a recommended reliability component, not a confirmed deployed system. It preserves requests if Assurpilot is temporarily unavailable. Show an honest received/pending message only after durable acceptance; never claim CRM delivery merely because a button was clicked.

Assurpilot is the proposed operational lead master. Confirm whether it supports outbound webhooks, the actual trigger, authentication, schema, retry behavior, and identifiers. If it lacks the required event, agree a supported server adapter or polling approach; do not invent an API. Browser code must not contain CRM credentials or public Make webhook secrets.

| Product | Destination specified by owner | Required routing checks |
| --- | --- | --- |
| Santé particuliers | AZUR | Supported product code, brand account, mandatory fields, adviser ownership |
| Santé TNS | AZUR | Explicit TNS segment retained, brand account and assignment mapping |
| Auto, including complex profiles | ProAssur | Driver/profile qualifier mapping and insurer criteria handled by authorized staff |
| Habitation | Not specified | Manual triage with assigned owner until a destination is approved |
| Décennale | Not specified | Separate professional queue until destination and underwriting workflow are approved |
| Missing/unsupported code | No automatic default | Quarantine, alert, correct, and replay |

Preserve originating brand and use separate tenant/account mappings where required. Never route unknown products silently to Santé or Auto.

### Minimum data and conceptual event contract

This is a proposed mapping inventory, not an actual vendor API schema:

| Data group | Proposed fields / rule |
| --- | --- |
| Identity | Stable `lead_id`, `event_id`, event/schema version, creation timestamp, Assurpilot ID, eventual destination CRM ID |
| Routing | Server-derived brand, product enum, market, landing-page version; validate against an allowlist |
| Contact | Name, justified phone/email fields, postcode, callback preference |
| Qualification | Only product-relevant fields needed at this stage; progressively request underwriting details through a secure process |
| Provenance | Allowlisted UTMs, campaign/ad identifiers where permitted, landing path, referral category, attribution model/version |
| Permissions | Separate quote/contact request evidence, optional marketing channel permissions, partner disclosure/permission evidence where applicable, analytics/ad consent state and notice version |
| Delivery | Current stage, attempt count, last error code, next retry, CRM acknowledgment timestamp and owner |

Initial forms should avoid medical histories, diagnoses, NIR, payment data, document uploads, and unnecessary free text. Ask high-level coverage priorities rather than detailed medical information. For Auto, collect cancellation reasons only as needed for quotation qualification. Keep detailed risk data out of URLs, UTMs, pixels, analytics events, and advertising audience exports.

### Reliability and security requirements

- Deduplicate transport retries with stable event IDs; make CRM writes idempotent through a verified external-ID mapping or equivalent controlled ledger.
- A repeated request for another product may be legitimate. Do not erase it through phone-only global deduplication or merge brand records without a defined policy.
- Use authenticated server-to-server delivery, TLS, scoped credentials, schema validation, payload limits, rate limiting, and replay protection where supported.
- Retry transient timeouts/rate limits with bounded backoff. Send invalid payloads, mapping errors, and exhausted retries to an owned recovery queue with alerts.
- Record delivery outcomes separately from commercial rejection. Daily reconciliation compares durable receipts, Assurpilot records, Make processing, and destination CRM acknowledgments.
- Minimize and redact logs, restrict access, define retention/deletion across all vendors, and verify vendor processing agreements and hosting/transfer arrangements.
- Do not equate HTTP receipt with downstream success. Make documents queue-based webhook acceptance; require explicit destination confirmation before `crm_delivered`. [Source: Make webhooks](https://help.make.com/webhooks)

## 7. Consent, contact, and attribution boundaries

Keep three decisions separate in both UX and data: processing the requested quote/callback, optional subsequent marketing, and optional advertising/analytics tracking. A rejected advertising-cookie choice must not prevent the requested service.

CNIL guidance states that consent is required before certain advertising trackers are stored/read. Gate relevant tags through the consent configuration; withdrawal must propagate. Server-side tracking and hashed contact data do not automatically remove privacy or platform-policy obligations. [Source: CNIL cookies and trackers](https://cnil.fr/fr/cookies-et-autres-traceurs/que-dit-la-loi)

As of this document's date, CNIL describes prior consent for consumer telephone prospecting from 11 August 2026, subject to the stated existing-contract exception. Have the owner/privacy reviewer validate the precise treatment of requested quote callbacks, subsequent prospecting, and insurance-specific contact requirements. Record the purpose, actor, channel, timestamp, and notice version; do not rely on acceptance of general terms as blanket marketing consent. [Source: CNIL prospecting guidance](https://www.cnil.fr/fr/demarchage-commercial)

Distinguish CRM processors performing the requested service from independent partners reusing leads for marketing. Determine the actual entity roles; where partner prospecting consent is required, obtain appropriate specific evidence and identify the partners transparently. Do not treat transfer to software as automatic permission to resell or market a lead. [Source: CNIL partner data transmission](https://www.cnil.fr/fr/la-prospection-b-to-c-quelles-regles-pour-transmettre-des-donnees-des-partenaires)

Capture UTMs and permitted click identifiers consistently, with an explicit unknown/direct state when unavailable. Preserve first acquisition and latest qualifying touch separately. Do not silently reattribute retries. Match permitted CRM feedback to the original lead; export only eligible events and fields after privacy and platform review. Sensitive segments must remain in authorized operational systems. Generic public product page names are content taxonomy; do not encode an individual's answers or sensitive underwriting status in URLs or uploaded event labels.

## 8. Conversion definitions and economics

| Stage | Definition / trigger |
| --- | --- |
| Form attempt | User attempts submission; diagnostic only |
| Lead accepted | Valid request durably recorded with unique lead ID |
| Assurpilot recorded | Operational lead creation/update acknowledged |
| CRM delivered | AZUR/ProAssur confirms the mapped lead; triage is reported separately |
| Contacted | Meaningful two-way contact, distinct from an unanswered attempt |
| Qualified | Unique legitimate inquiry, valid/reachable contact, explicit quote/contact intent, serviceable location, and apparent product eligibility under documented criteria |
| Quote issued | Actual quotation recorded |
| Policy issued | Confirmed policy record; distinguish from a verbal agreement or quote |
| Cover in force | Insurer confirms effective cover under the policy's actual terms and start date; distinct from issuing a record |
| Retained policy | Policy survives the agreed retention window; cancellations/clawbacks recorded |

Count accepted conversions once per defined inquiry, not on button clicks or thank-you reloads. Use common event IDs to deduplicate browser/server events where supported. Use accepted leads as an early learning signal when necessary, then introduce eligible qualified/policy feedback as volume and latency permit. When qualified-lead volume and accuracy are sufficient, make that the primary acquisition goal and upstream events secondary. Do not make all funnel stages primary bidding goals simultaneously and count one inquiry several times.

Report by brand, product, channel, campaign, and acquisition cohort. Include EUR spend, Europe/Paris date windows, attribution settings, consent coverage, conversion lag, and cohort maturity. Reconcile ad-platform attribution with the CRM without assuming they must match.

Core metrics:

- Accepted unique CPL = media spend / accepted unique inquiries.
- Cost per qualified lead = spend / qualified inquiries from the same acquisition cohort.
- Contact and quotation rates, with explicit denominators.
- Cost per issued policy = spend / issued policies.
- Lead-to-issued rate, delivery success rate, duplicate rate, unresolved routing failures, and time to first human response.
- Retention, net commission contribution, and acquisition contribution after handling costs.

Set allowable CPL from internal economics:

```text
Expected allowable accepted-lead CPL
  = P(issued policy | accepted lead) × expected retained contribution per issued policy
    − expected handling cost per accepted lead
    − desired profit / risk reserve per accepted lead
```

Define retained contribution after relevant cancellations, commission clawbacks, and variable policy costs, without double-counting handling costs. Insurance premium volume is not brokerage revenue. Use net brokerage contribution for profitability decisions, not a premium-based ROAS presented as revenue. No numeric target is asserted until observed data and accounting definitions are agreed.

## 9. Delivery priorities and acceptance criteria

### Foundation

The Team Lead confirms product/geographic eligibility, brand roles, adviser capacity, contact wording, and business metric definitions. Paid Ads supplies the campaign/intent matrix; the Web Developer specifies the form and routing contract; SEO checks content hierarchy, claims, indexation, and intent alignment.

### End-to-end validation before scale

Use synthetic records in an approved test environment. Cover Santé, TNS, standard/complex Auto, unsupported products, invalid fields, repeat delivery, destination timeout, expired credentials, permission refusal/withdrawal, and failed recovery replay.

Acceptance requires:

- One valid test inquiry is durably received, recorded in Assurpilot, and confirmed in the correct CRM with source brand preserved.
- Retries create no duplicate commercial inquiry; distinct legitimate product inquiries remain traceable.
- Unknown products and failures have visible owners and recovery paths.
- UTMs and allowed identifiers survive routing; PII and sensitive qualifiers do not leak to analytics/ads.
- Relevant tags respect consent; service requests still work when optional tracking is declined.
- Mobile/keyboard form behavior, product copy, confirmation state, and canonical/indexation rules are checked.
- Dashboard counts reconcile with delivery records and defined commercial stages.

These are required future checks, not tests already performed.

### Controlled learning and expansion

Launch only under separately authorized campaign/deployment scope. Review routing health and adviser backlog daily; review query quality, lead quality, and cohort economics regularly. Expand only after reliable delivery and sufficiently mature commercial results.

## 10. Collaboration review and open decisions

Paid Ads defined ICPs, intent groups, acquisition economics, and messaging constraints. Web Development reviewed CTA accuracy, form relevance, durable acceptance, stage definitions, and routing resilience. SEO reviewed page intent, product-copy consistency, canonicalization, and mobile/performance requirements. Cross-review corrected the distinction between a quote request and a completed quote, and between a webhook receipt and CRM delivery.

Still to confirm with the business and vendors:

1. Product availability by geography, eligibility, and insurer; intended brand differentiation.
2. Exact Assurpilot event/API capability and AZUR/ProAssur field and account mappings.
3. Destinations and owners for Habitation and Décennale.
4. Adviser hours, callback service levels, staffing, and escalation ownership.
5. Entity roles, permissions, retention periods, consent text, and approved tracking/export configuration.
6. Actual CPL, qualification and issued-policy rates, retained commission economics, budget, and learning thresholds.

Follow [the collaboration protocol](agent-collaboration-workflow.md) and [team workflow](team-workflow.md) for implementation handoffs.
