# okta-access-drift-ledger

Board-readable Kinetic Gain proof repo for **Okta** platform and company signal coverage.

## Product thesis

SaaS identity estates grow faster than ownership, MFA posture, app retirement, and access-review evidence can stay aligned.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** CISOs, identity owners, platform leaders, and diligence teams
- **Signal domain:** IAM / Security
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product turns app ownership, privileged group drift, stale access, MFA gaps, and remediation queues into one board-ready identity-control lane.
- **Value architecture:** Leaders can see which identity controls reduce breach exposure, license waste, and audit scramble before the next access-review cycle.

## What this repo proves

- **Normalize:** messy Okta operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Okta apps, groups, lifecycle events, MFA policies, and review packets.

This is synthetic proof only. It does not connect to live Okta tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Okta
- identity governance
- access review
- MFA posture
- SaaS sprawl
