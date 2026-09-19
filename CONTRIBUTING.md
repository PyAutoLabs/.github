# Contributing to PyAutoLabs

Welcome! This is the shared contribution guide for all [PyAutoLabs repositories](https://github.com/PyAutoLabs): scientific libraries, workspaces, tutorials, assistants, and development tools.

If you arrived from PyAutoFit, PyAutoGalaxy, PyAutoLens, PyAutoArray, or another repository, you are in the right place. You do not need to install PyAutoScientist or use AI to contribute. Questions, scientific examples, documentation, bug reports, tests, and conventional pull requests are welcome.

## Start a conversation

Questions, help with your code or your analysis, and ideas: the
[PyAutoLabs Discussions](https://github.com/orgs/PyAutoLabs/discussions).
Bug reports with a reproducer (a snippet, the traceback, your versions):
an issue on the library's tracker. The Slack is for collaborators, by
invitation.

The shared discussion categories are:

- [Help & Questions](https://github.com/orgs/PyAutoLabs/discussions/categories/help-questions): installation, using the software, and scientific or analysis questions.
- [Ideas & Proposals](https://github.com/orgs/PyAutoLabs/discussions/categories/ideas-proposals): feature suggestions and concrete implementation proposals.
- [Bugs & Errors](https://github.com/orgs/PyAutoLabs/discussions/categories/bugs-errors): unexpected behaviour or an error that needs investigation.
- [Announcements](https://github.com/orgs/PyAutoLabs/discussions/categories/announcements): maintainer news and releases.
- [Show and tell](https://github.com/orgs/PyAutoLabs/discussions/categories/show-and-tell): results, examples, and projects to share.

Mention the repository or package you are using. Search existing discussions and issues first. For substantial changes, discuss the approach before investing in implementation. A plain-English explanation is enough to begin; example code and links to relevant methods help.

Once a proposal is agreed or a defect is reproducible, create or link an implementation issue in the repository that owns the change. Keep the discussion and issue linked so the original context is not lost. Where available, mark a helpful resolution or settled proposal verdict as the accepted answer.

## Report a reproducible bug

Use the affected repository's issue tracker for confirmed reproducible defects, not the PyAutoScientist tracker unless the problem is with PyAutoScientist itself. Include:

- a minimal runnable example and any small, shareable input needed to reproduce it;
- the full traceback or incorrect output;
- expected versus actual behaviour;
- operating system, Python version, and relevant package versions.

If you are unsure whether it is a bug, start in Bugs & Errors. Never post secrets, private data, or collaborator-controlled material publicly. For security-sensitive reports, follow the affected repository's security policy instead of opening a public discussion. If no private reporting route is listed, email James Nightingale at [james.w.nightingale@durham.ac.uk](mailto:james.w.nightingale@durham.ac.uk) to arrange one; do not include sensitive details in the initial message.

## Submit a change

Contributions with or without AI assistance are assessed against the same scientific, testing, and documentation standards.

1. Read the target repository's README, contribution instructions, and AGENTS.md where present. Local setup, architecture, and validation requirements still apply.
2. For a non-trivial change, agree the scope in Discussions and link the resulting repository issue.
3. Fork the relevant repository or use an authorized branch. Keep the pull request focused.
4. Add or update tests, examples, and documentation appropriate to the change.
5. Open a pull request explaining what changed, why, the evidence that it works, and any downstream impact. Link its issue and originating discussion.

Maintainers may use automation or agents to assist triage and review. Humans remain responsible for contributor communication, consequential decisions, and accepting changes. No contribution is accepted merely because generated code runs or looks plausible.

### Libraries, workspaces, and tutorials

For source libraries, install from source and run the documented tests. Describe changes to public APIs and effects on downstream libraries or workspaces.

For workspaces and tutorials, preserve scientific intent and teaching context. Where notebooks are generated, edit the source scripts and regenerate notebooks through the repository's documented process rather than hand-editing generated notebooks.

Workspace-test repositories are integration suites, not tutorials. Never weaken or remove checks to conceal a regression.

## Validation and responsibility

Validation should match the risk: unit tests for components, runnable examples and smoke tests for user workflows, integration tests across packages, and scientific comparisons where numerical behaviour changes. Repository guidance and release-readiness checks determine the applicable gates.

Be able to explain the intended behaviour, scientific assumptions, important decisions, and how correctness was checked. Document API changes and their downstream effects. Check the provenance and licence of adapted code, and cite published methods and existing software where appropriate.

AI-assisted work must follow the shared [PyAuto AI Policy](https://github.com/PyAutoLabs/PyAutoScientist/blob/main/AI_POLICY.md), including its requirements for expertise, validation, attribution, privacy, and human responsibility. Do not send private or embargoed information to an AI service without appropriate authorization.

## Optional: PyAutoScientist

[PyAutoScientist](https://github.com/PyAutoLabs/PyAutoScientist) is James Nightingale's experimental, human-led AI development ecosystem. It is optional: neither using the scientific libraries nor contributing to them requires adopting it.

If you want to explore its workflows, read its [adoption guide](https://pyautoscientist.readthedocs.io/en/latest/adoption/guide.html) and discuss setup with the maintainer. Its own README and organ-specific instructions describe development inside that ecosystem.

## Community standards

Participation is governed by the [PyAutoLabs Code of Conduct](https://github.com/PyAutoLabs/.github/blob/main/CODE_OF_CONDUCT.md). Use its private reporting contact for conduct concerns, not a public issue.

This guide, the Code of Conduct, and [support guidance](https://github.com/PyAutoLabs/.github/blob/main/SUPPORT.md) are maintained in PyAutoLabs/.github. GitHub displays supported defaults for repositories without a local override; these files are not automatically copied into repository clones or distributions.
