# Can we check each direction of the 3-SAT to CLIQUE reduction?

Prove the standard construction and check it against independently enumerated small instances.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/3sat-to-clique/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-3sat-to-clique/pulls)

## Why this matters

A clique of size equal to the number of clauses picks one consistent literal from each clause. Repeated literals and contradictions are useful fixtures because they expose mistakes in a graph generator or witness translator.

## What to contribute

Run the repository’s checker, then add a bounded fixture family with known outcomes or formalize one direction and connect it to the exact graph construction.

## How reviewers check it

Include the formula family, expected decision and witness checks. State what the finite run checks and give the general proof for the reduction.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/3sat-to-clique
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/3sat-to-clique/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-3sat-to-clique/security/advisories/new) for security reports.

## Sources

- [MIT 18.404J, NP-completeness and the 3-SAT-to-CLIQUE reduction](<https://learn.mit.edu/video/7035/lecture-15-np-completeness?playlist=7021>)

## Starter

[Proof and executable checker](contributions/3sat-clique/README.md)
