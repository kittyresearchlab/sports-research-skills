# Research records

Adapt to an existing schema where available. Otherwise preserve these fields in JSONL, a table, or another suitable format. Omit optional values rather than inventing them.

| Field | Meaning |
| --- | --- |
| id / revision | Stable lead identity; explicit revisions for corrections |
| sport / competition | Explicit competition and men's/women's designation where relevant |
| team / player | Verified identity; unresolved mappings stay unresolved |
| claim | One short attributed observation or factual claim |
| reddit_url / subreddit | Thread and exact comment permalink where available; actual community |
| access | Read, partial/preview-only, or blocked |
| published_at / precision | Actual time or date; null and unknown when unavailable |
| observed_at_utc | Actual UTC collection time |
| event_time / phase | Supported event time; pregame, live, postgame, or unknown |
| origin_url | Original source of a repeated claim, if any |
| status | Fan observation, attributed report, independently verified, conflicting, unresolved |
| verification | Exact supported claim, verification URL, and actual verification time |
| relevance / next_check | Why it matters and a proportionate next step |
| related_ids | Reposts, contradictions, supersession, correction references |

Store run metadata separately: run ID, collection window, actual start/end times, communities and threads attempted, gaps, previous successful run, output destination, and write/read-back result. Advance a successful-run watermark only for completed collection. Keep partial coverage visible and carry failed areas forward rather than declaring them reviewed. Deduplicate overlapping windows.

Group Reddit reposts linking one report under one origin. Keep separate observations without labeling them independent factual confirmation. Date verification revisions so later confirmation cannot appear as pregame knowledge.

Distinguish collected leads, verified claims, saved records, and admitted model inputs. This skill handles the first three where authorized and supported. Model admission belongs to the project's separate validation process.
