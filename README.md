# Gyanu Mayank

Independent researcher in agent evaluation and agentic systems.

B.Tech, Computer Science and Engineering, National Institute of Technology Patna. Pune, India.

Research focus: evaluation integrity for agent benchmarks. Outcome tests alone can certify no-op methods, cosmetic adaptation, and fixture edits. Technical report *When the delta is fake* proposes a pass-bar for task authorship and a construction that catches fake deltas under ranking AUROC (mean-shift invariance + train-site shortcut flip + frozen verifier-recomputed control). DOI: [10.5281/zenodo.23829461](https://doi.org/10.5281/zenodo.23829461).

Also works on eval inside product agent loops (draft → score → revise) and reliability through tool layers (cancel, timeouts, evidence grounding).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gyanu-mayank-0b4019203/) [![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:viratmayank2507@gmail.com) [![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat-square)](https://portfolio-gyanu.vercel.app) [![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/25mayank) [![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/25mayank/) [![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://www.codechef.com/users/winner32)

## Projects

- [agent-eval-suite](https://github.com/gyanu2507/agent-eval-suite): reference tasks and the technical report on fake deltas in agent evals. One-command repro.
- [workspace-brief](https://github.com/gyanu2507/workspace-brief): brief a live GitHub workspace with a planner, citations, memory and JSON traces.
- [brief-desk](https://github.com/gyanu2507/brief-desk): CopilotKit + AG-UI chat desk with MCP tools for workspace and corpus briefing.

## Open source

Selected merged fixes:

- celery: [don't fail a task whose SUCCESS was stored before the worker was lost](https://github.com/celery/celery/pull/10752), [don't record FAILURE when on_success raises after SUCCESS](https://github.com/celery/celery/pull/10759)
- kombu: [stop channel retries at the connection max_retries bound](https://github.com/celery/kombu/pull/2671)
- asyncpg: [bound close(timeout) around a pending cancel](https://github.com/MagicStack/asyncpg/pull/1361)
- go-yaml: [end tags at flow indicators in flow content](https://github.com/yaml/go-yaml/pull/435)
- mlx-lm: [fix mlx_lm.server model-swap leak and dead generation thread](https://github.com/ml-explore/mlx-lm/pull/1837)
- gunicorn: [stop writing a 500 on top of a response that already started](https://github.com/benoitc/gunicorn/pull/3715)

In review on eval harnesses: [Harbor #4003](https://github.com/harbor-framework/harbor/pull/4003), [Terminal-Bench #2480](https://github.com/harbor-framework/terminal-bench/pull/2480). [All merged PRs](https://github.com/search?q=is%3Apr+author%3Agyanu2507+is%3Amerged&type=pullrequests).
