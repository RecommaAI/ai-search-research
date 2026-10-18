# AI search research

Open data from [Recomma](https://recomma.ai)'s studies of how AI assistants answer buying questions — which brands they name and which sources they cite. Each folder holds the data as published and the results table. The method and discussion are in the linked write-up.

Recomma tracks what ChatGPT, Gemini and Google's AI Overviews and AI Mode say about a brand, captured from the interfaces readers use.

## Studies

### [ChatGPT's interface vs its API](interface-vs-api) — 100 questions, 500 answers

Write-up: https://recomma.ai/blog/chatgpt-interface-vs-api · Collected 12 October 2026

100 buying questions in ten categories (CRM, project management, email marketing, password managers, VPNs, running shoes, robot vacuums, small-business accounting, web hosting, AI visibility tools). Each was answered twice by the chatgpt.com interface and three times through the OpenAI API: with web search, with web search on a smaller model, and without search.

| Measure | Interface vs interface | Interface vs API + search |
|---|---|---|
| Brands named in both | 78% | 65% |
| Same top pick | 73% | 57% |
| Cited domains in both | 47% | 27% |
| Cited pages in both | 30% | **8%** |

The interface cited 7.8 domains per answer; the API with search, 3.2. Brand-owned sites were 41% of the domains the interface cited and 64% of those the API cited.

`interface-vs-api/data.csv` — one row per answer: `category, question, arm, model, collected_at, words, brands_named, cited_urls` (lists separated by ` | `).

### [AI search volume, tested](ai-search-volume) — 308 phrases

Write-up: https://recomma.ai/blog/ai-search-volume-study · Collected 14 October 2026

308 phrases — full questions, head-to-long-tail ladders, reversed-word variants and brand names — with DataForSEO's AI search volume beside Google Ads search volume, for the US and the UK.

- Reversing a phrase's word order left the AI figure unchanged in **60 of 60** cases (Google: 7 of 38).
- Adding words to make a phrase more specific raised the AI figure in **0 of 68** steps.
- The AI figure was a median **3%** of Google's for the same phrase (IQR 2–10%, n=100), and ranked phrases almost exactly as Google does (Spearman 0.92).

`ai-search-volume/data.csv` — one row per phrase: `category, kind, phrase, ai_volume_us, google_volume_us, ai_volume_uk, google_volume_uk`.

## Using the data

CC BY 4.0: use it for anything, with credit to Recomma and a link to the write-up. See [CITATION.cff](CITATION.cff).

Questions or corrections: hello@recomma.ai, or open an issue.
