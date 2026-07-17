# Open Modeling Foundation RFCs

This repository contains Requests for Comments (RFCs) for proposed Open Modeling Foundation (OMF) standards, governance changes, and other significant community decisions.

RFCs provide an open, transparent process for discussing ideas before they become official OMF standards.

## When is an RFC needed?

An RFC is appropriate for changes that have broad impact, including:

* New OMF standards
* Major revisions to existing standards
* Changes to governance or community processes
* Other proposals that benefit from public review and long-term documentation

Small editorial fixes and clarifications should be made directly to the relevant documents and generally do not require an RFC. If you're unsure which category a change falls into, open a GitHub Discussion — that's what step 1 below is for.

## RFC Process

1. **Discuss the idea**
   Before writing an RFC, start a [GitHub Discussion](../../discussions) or issue to gather early feedback and determine whether the proposal is worth pursuing. This step is optional but strongly encouraged — it surfaces prior art and objections before you've invested time in a full draft.

2. **Write the RFC**
   Copy [`template.md`](./template.md) to a new file and describe the motivation, proposed specification, rationale, alternatives considered, and any open questions. Name the file `NNNN-short-descriptive-title.md`, using `0000` as a placeholder for the RFC number (see [Repository Structure](#repository-structure) for how the real number gets assigned).

3. **Open a Pull Request**
   Submit the RFC as a pull request against this repository. Community discussion and revisions take place in the PR and any linked GitHub Discussions. Once the PR is opened, a maintainer will assign the RFC its permanent number and you can rename the file accordingly.

4. **Community Review**
   Contributors are encouraged to review the proposal, ask questions, suggest improvements, and identify potential issues. Authors should update the RFC in response to constructive feedback. There's no fixed review period, but substantive RFCs should stay open for comment for at least two weeks before a decision is made.

5. **Decision**
   Maintainers will determine whether the RFC is:
   * **Accepted** — The proposal is approved and merged.
   * **Rejected** — The proposal is closed with rationale.
   * **Deferred** — The proposal has merit but is not actionable right now; it may be revisited in the future.

6. **Implementation**
   Accepted RFCs become the basis for OMF standards or governance changes. Acceptance represents agreement on the direction, not necessarily immediate implementation — implementation may be tracked in a separate issue linked from the RFC.

## RFC Lifecycle

```
Idea
  ↓
Discussion (optional)
  ↓
Draft RFC
  ↓
Pull Request → Public Review
  ↓
Accepted / Rejected / Deferred
  ↓
Implementation
```

## Repository Structure

```
rfcs/
├── README.md
├── template.md
├── 0001-model-documentation-standard.md
├── 0002-...
└── ...
```

RFC numbers are assigned sequentially by a maintainer at PR-open time and remain permanent, regardless of whether an RFC is accepted or rejected. Each RFC file should begin with a short metadata block (number, title, status, author, date) as shown in `template.md`, so status is visible without checking PR history.

## Guiding Principles

The RFC process aims to be:

* **Open** — Anyone may propose ideas and participate in discussion.
* **Transparent** — All proposals, reviews, and decisions are public.
* **Collaborative** — Consensus is preferred over voting whenever possible.
* **Documented** — Decisions and their rationale are preserved for future contributors.
* **Lightweight** — The process should encourage participation rather than create unnecessary bureaucracy.

Our goal is to build high quality, community-driven standards through open discussion and thoughtful iteration.

## Questions

If you're not sure whether your idea needs an RFC, or you're stuck on process, open a [Discussion](https://github.com/openmodelingfoundation/rfcs/discussions) or [issue](https://github.com/openmodelingfoundation/rfcs/issues).
