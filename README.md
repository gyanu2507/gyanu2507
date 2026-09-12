# Gyanu Mayank

B.Tech in Computer Science, NIT Patna. Based in Pune.

I work on agent loops: tools, MCP, human-in-the-loop resume, and retrieval. When a library drops a tool call or a resume path, I patch it.

[LinkedIn](https://www.linkedin.com/in/gyanu-mayank-0b4019203/) · [Email](mailto:viratmayank2507@gmail.com) · [Portfolio](https://portfolio-gyanu.vercel.app)

## Open source

A few merged patches:

- [AG-UI #2715](https://github.com/ag-ui-protocol/ag-ui/pull/2715): on Mastra resume, emit `TOOL_CALL` start/args/end before `RESULT` so the client still has the tool
- [Spec Kit #4401](https://github.com/github/spec-kit/pull/4401), [#4402](https://github.com/github/spec-kit/pull/4402): drop the unused `scope` input from the bundled SDD workflow, and make assess-clarifications edit the artifact in place
- [FastMCP #358](https://github.com/punkpeye/fastmcp/pull/358): send `WWW-Authenticate` on 401 when `authenticate()` fails with no OAuth config
- [mlx-lm #1777](https://github.com/ml-explore/mlx-lm/pull/1777), [#1848](https://github.com/ml-explore/mlx-lm/pull/1848): prefill tokens reach logits processors, and `BatchKVCache` rebinds offset instead of mutating it
- [Haystack #12624](https://github.com/deepset-ai/haystack/pull/12624): type routers reject reserved output names instead of failing later
- [Gunicorn #3715](https://github.com/benoitc/gunicorn/pull/3715): stop writing a 500 over a response that already started
- [Logfire #2308](https://github.com/pydantic/logfire/pull/2308): tail sampling keeps the buffer until every span in the trace has ended
- [Python-Markdown #1625](https://github.com/Python-Markdown/markdown/pull/1625): parse inline code by walking backtick spans instead of a regex

[All merged pull requests](https://github.com/search?q=is%3Apr+author%3Agyanu2507+is%3Amerged&type=pullrequests)

## Projects

- [Workspace Brief](https://github.com/gyanu2507/workspace-brief): an agent over a live GitHub workspace (planner, tool loop, BM25, citations)
- [Advanced RAG](https://github.com/gyanu2507/advanced-rag): document Q&A over PDF, DOCX, CSV
- [Llama 2 Chat](https://github.com/gyanu2507/Chatbot-Llama): streamed chat on 7B / 13B / 70B ([demo](https://gyanu-chatbot-llama.streamlit.app))
- [LinkedIn Posts Generator](https://github.com/gyanu2507/Linkedin-Posts-Generator): few-shot posts with Groq

## Competitive programming

[CodeChef](https://www.codechef.com/users/winner32) 4★, peak 1917. [Codeforces](https://codeforces.com/profile/25mayank) Specialist, peak 1455. [LeetCode](https://leetcode.com/25mayank/) Knight, 1000+ problems.

Scaler HACKX 2021: 44 / 15,500. Google Kick Start 2022 Round H: 1264. TechGig Code Gladiators 2023 finalist.
