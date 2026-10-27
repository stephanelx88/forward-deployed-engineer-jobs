# Forward Deployed Engineer jobs dataset

Every open Forward Deployed Engineer (FDE) role that [FDE Times](https://fdetimes.net/en/jobs/) tracks, collected mostly from the public
Greenhouse, Ashby and Lever career boards of the companies that hire FDEs. Updated daily.

**As of 2026-10-27: 624 open roles at 96 companies.** Median posted base pay (midpoint of the range) across 224 US posts: **$216k**.

- Live tracker: [FDE Hiring Tracker](https://fdetimes.net/en/fde-hiring/)
- Pay analysis: [FDE salary: what job posts actually pay](https://fdetimes.net/en/fde-salary/)
- What the role is: [What is a Forward Deployed Engineer?](https://fdetimes.net/en/forward-deployed-engineer/)

## Files

`data/fde-jobs.csv`, one row per open role:

| Column | Meaning |
|---|---|
| id | Stable role id |
| company | Employer |
| title | Job title as posted |
| location | Location as posted |
| country | ISO country code read from the location, when it can be read |
| seniority | early, mid or senior, read from the title |
| pay_low_usd, pay_high_usd | Annual base-pay range published in the post (US posts only; empty when none is published) |
| first_seen | Date FDE Times first saw the role |
| fdetimes_url | The role's page on FDE Times |

The same file is served at https://fdetimes.net/data/fde-jobs.csv.

## Companies with the most open roles

| Company | Open roles |
|---|---|
| Databricks | 119 |
| Palantir | 105 |
| OpenAI | 31 |
| Salesforce | 29 |
| Rogo | 17 |
| Scale AI | 15 |
| ElevenLabs | 12 |
| Cognition | 11 |
| Cohere | 11 |
| Cloudflare | 11 |

## Licence and citation

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit: FDE Times, "Forward Deployed Engineer jobs
dataset", https://fdetimes.net/en/fde-hiring/.
