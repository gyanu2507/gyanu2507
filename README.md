# Gyanu Mayank

**Generative AI Engineer.** I build RAG systems and multi-cloud AI pipelines — and I spend a good part of my week fixing bugs in the open-source libraries the rest of us build on.

B.Tech in Computer Science, NIT Patna. Based in Pune, India.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gyanu-mayank-0b4019203/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:viratmayank2507@gmail.com)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/25mayank)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/25mayank/)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://www.codechef.com/users/winner32)

---

## Open Source

I contribute upstream fixes to widely used libraries — mostly small, well-scoped patches with a regression test, in whatever language the project is written in. Selected merged work:

| Project | Stars | Contribution |
| --- | --- | --- |
| [Chainlit](https://github.com/Chainlit/chainlit) | ![](https://img.shields.io/github/stars/Chainlit/chainlit?style=flat-square&label=%20&color=444) | Made CI fail when a `pnpm.overrides` pin is declared but silently never applied ([#3017](https://github.com/Chainlit/chainlit/pull/3017)) |
| [Gunicorn](https://github.com/benoitc/gunicorn) | ![](https://img.shields.io/github/stars/benoitc/gunicorn?style=flat-square&label=%20&color=444) | Stopped the worker writing a 500 on top of a response that had already started ([#3715](https://github.com/benoitc/gunicorn/pull/3715)) |
| [django-extensions](https://github.com/django-extensions/django-extensions) | ![](https://img.shields.io/github/stars/django-extensions/django-extensions?style=flat-square&label=%20&color=444) | Fixed a `print-sql` crash when the backend returns no last executed query ([#1997](https://github.com/django-extensions/django-extensions/pull/1997)) |
| [Pydantic Logfire](https://github.com/pydantic/logfire) | ![](https://img.shields.io/github/stars/pydantic/logfire?style=flat-square&label=%20&color=444) | Held tail-sampling buffers until every span in a trace has ended, so traces stopped being dropped ([#2308](https://github.com/pydantic/logfire/pull/2308)) |
| [Python-Markdown](https://github.com/Python-Markdown/markdown) | ![](https://img.shields.io/github/stars/Python-Markdown/markdown?style=flat-square&label=%20&color=444) | Replaced the backtick-span regex with a walk over the spans, fixing inline-code edge cases ([#1625](https://github.com/Python-Markdown/markdown/pull/1625)) |
| [Waitress](https://github.com/Pylons/waitress) | ![](https://img.shields.io/github/stars/Pylons/waitress?style=flat-square&label=%20&color=444) | Kept the event loop alive when `select` hits `EBADF` after a socket close ([#506](https://github.com/Pylons/waitress/pull/506)) |
| [environs](https://github.com/sloria/environs) | ![](https://img.shields.io/github/stars/sloria/environs?style=flat-square&label=%20&color=444) | Returned `None` for invalid values under `eager=False` instead of raising early ([#487](https://github.com/sloria/environs/pull/487)) |

Currently open, across languages and ecosystems:

- **JavaScript / TypeScript** — [marked](https://github.com/markedjs/marked/pull/4077) (Unicode case folding for reference link labels, flipping a CommonMark spec test from expected-fail to passing) · [cheerio](https://github.com/cheeriojs/cheerio/pull/5465) (camelCase property support in `.css()`) · [yargs](https://github.com/yargs/yargs/pull/2583) (`showHidden(false)` now actually hides) · [Hono](https://github.com/honojs/hono/pull/5302)
- **Go** — [go-yaml](https://github.com/goccy/go-yaml/pull/926) (inline key comments no longer produce invalid YAML) and [#927](https://github.com/goccy/go-yaml/pull/927) (value-less anchors at end of stream)
- **Python** — [psutil](https://github.com/giampaolo/psutil/pull/2986) · [attrs](https://github.com/python-attrs/attrs/pull/1614) · [Sphinx](https://github.com/sphinx-doc/sphinx/pull/14654) · [Alembic](https://github.com/sqlalchemy/alembic/pull/1861) · [spaCy](https://github.com/explosion/spaCy/pull/14022) · [pydantic-settings](https://github.com/pydantic/pydantic-settings/pull/949) · [LiteLLM](https://github.com/BerriAI/litellm/pull/37927) · [mlx-lm](https://github.com/ml-explore/mlx-lm/pull/1777)

[All merged pull requests →](https://github.com/search?q=is%3Apr+author%3Agyanu2507+is%3Amerged&type=pullrequests)

---

## What I Work On

- **RAG systems** — retrieval pipelines over vector databases, tuned for precision and grounded answers
- **LLM serving** — deploying and optimising frontier models for low-latency inference at scale
- **Multi-cloud infrastructure** — automated deployments across AWS, Azure and GCP with Terraform
- **Backend systems** — Python APIs, service boundaries, correctness under failure
- **Algorithms** — active competitive programmer; it is where the debugging instinct comes from

## Tech

**Languages** — Python, C++, JavaScript / TypeScript, C, Java, Go (reading and patching)

**AI / ML** — LLM APIs, RAG, embeddings and vector search, inference optimisation

**Cloud & DevOps** — AWS, Azure, GCP, Terraform, Docker, CI/CD

**Backend** — REST APIs, Node.js, MongoDB, MySQL

**Frontend** — React, Tailwind CSS

---

## Competitive Programming

| Platform | Standing |
| --- | --- |
| [CodeChef](https://www.codechef.com/users/winner32) | 4★ — peak rating 1917 |
| [Codeforces](https://codeforces.com/profile/25mayank) | Specialist — peak rating 1455 |
| [LeetCode](https://leetcode.com/25mayank/) | Knight — 1000+ problems solved |

Rank **44 of 15,500** at Scaler HACKX 2021 · Rank **1264** in Google Kick Start 2022 Round H · Finalist, TechGig Code Gladiators 2023 (150,000+ entrants) · Finalist, NIT Silchar inter-college contest 2022
