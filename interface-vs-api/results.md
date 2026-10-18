# Interface vs API — 100 questions

| Measure | UI vs UI | UI vs API+search (gpt-6-sol) | UI vs API+search (small) | UI vs API, no search |
|---|---|---|---|---|
| Brand overlap | 78% (95% CI 73%–82%) | 65% (95% CI 60%–70%) | 72% (95% CI 67%–76%) | 67% (95% CI 62%–72%) |
| Same top pick | 73% (95% CI 64%–81%) | 57% (95% CI 49%–66%) | 68% (95% CI 61%–76%) | 65% (95% CI 56%–73%) |
| Cited-domain overlap | 47% (95% CI 43%–51%) | 27% (95% CI 24%–30%) | 30% (95% CI 27%–33%) | — |
| Cited-page overlap | 30% (95% CI 27%–33%) | 8% (95% CI 6%–10%) | 10% (95% CI 8%–11%) | — |

## Per answer

| Arm | Brands named | Cited domains | Words |
|---|---|---|---|
| ui-a | 3.8 | 7.8 | 596 |
| ui-b | 3.8 | 7.4 | 582 |
| api-search | 2.9 | 3.2 | 196 |
| api-search-small | 3.9 | 3.6 | 389 |
| api-plain | 3.2 | 0.0 | 132 |

## Categories (mean absolute share-of-voice gap per brand)

| Category | UI vs UI | API+search | API plain | UI top 3 | API+search top 3 | Widest gap |
|---|---|---|---|---|---|---|
| CRM | 6% | 8% | 4% | HubSpot, Pipedrive, Zoho CRM | HubSpot, Zoho CRM, Pipedrive | Pipedrive: UI 65%, API 40% |
| Project management | 5% | 10% | 10% | ClickUp, Trello, Jira | Trello, ClickUp, Asana | Monday: UI 45%, API 10% |
| Email marketing | 5% | 8% | 9% | Brevo, Mailchimp, MailerLite | ConvertKit, Klaviyo, Omnisend | Brevo: UI 55%, API 30% |
| Password managers | 12% | 12% | 10% | Bitwarden, 1Password, Proton Pass | Bitwarden, 1Password, Proton Pass | Proton Pass: UI 70%, API 30% |
| VPNs | 10% | 17% | 16% | Proton VPN, NordVPN, Surfshark | Proton VPN, Mullvad, NordVPN | Surfshark: UI 60%, API 20% |
| Running shoes | 8% | 14% | 9% | Asics, Hoka, Brooks | Asics, Brooks, Nike | Hoka: UI 80%, API 10% |
| Robot vacuums | 8% | 17% | 16% | Roborock, Dreame, Eufy | Roborock, Dreame, Mova | Eufy: UI 50%, API 10% |
| Small-business accounting | 8% | 9% | 9% | QuickBooks, Xero, Wave | QuickBooks, Wave, Xero | Xero: UI 80%, API 60% |
| Web hosting | 9% | 10% | 8% | SiteGround, Hostinger, Kinsta | SiteGround, Hostinger, Kinsta | Bluehost: UI 40%, API 10% |
| AI visibility tools | 8% | 9% | 13% | Semrush, Profound, Peec AI | Otterly.AI, Peec AI, Semrush | Rankscale: UI 25%, API 0% |

## Most-cited domains (share of answers)

| Domain | UI | API+search |
|---|---|---|
| rtings.com | 15% | 13% |
| hubspot.com | 13% | 11% |
| techradar.com | 18% | 3% |
| zoho.com | 12% | 8% |
| tomsguide.com | 16% | 3% |
| bitwarden.com | 10% | 8% |
| tryprofound.com | 8% | 7% |
| peec.ai | 8% | 7% |
| otterly.ai | 7% | 8% |
| protonvpn.com | 8% | 6% |
| semrush.com | 8% | 6% |
| quickbooks.intuit.com | 8% | 5% |
| xero.com | 7% | 6% |
| waveapps.com | 7% | 5% |
| clickup.com | 6% | 5% |

Brand-owned share of cited domains: UI 41%, API+search 64%, small 59%

UI only: dupple.com 8%, technologyadvice.com 7%, brevo.com 6%, surfshark.com 6%, dickssportinggoods.com 5%, itechguides.com 5%, dreametech.com 5%, reddit.com 4%, stackfyi.com 4%, security.org 4%

API only: odoo.com 2%, developers.google.com 2%, lessannoyingcrm.com 1%, official.lofty.com 1%, thesaascfo.com 1%, linkedin.com 1%, cmicglobal.com 1%, wac-cdn.atlassian.com 1%, support.productboard.com 1%, apps.shopify.com 1%

Models: {"ui-a":["gpt-6"],"ui-b":["gpt-6"],"api-search":["openai/gpt-6-sol"],"api-search-small":["openai/gpt-5.6-luna"],"api-plain":["openai/gpt-6-sol"]}

Cost: {"ui-a":0.4,"ui-b":0.4,"api-search":9.176,"api-search-small":2.632,"api-plain":0.329}
