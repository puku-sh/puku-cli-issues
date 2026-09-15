# Contributing to Puku CLI

Thank you for using Puku CLI and for taking the time to share feedback. This repository is dedicated to **filing and tracking issues** for Puku CLI.

## Filing issues — at a glance

| What you want to do                              | Template                                                                                |
| ------------------------------------------------ | --------------------------------------------------------------------------------------- |
| Report a bug or unexpected behavior              | [Bug Report](https://github.com/puku-sh/puku-cli-issues/issues/new?template=bug_report.yml) |
| Suggest a feature or enhancement                 | [Feature Request](https://github.com/puku-sh/puku-cli-issues/issues/new?template=feature_request.yml) |
| Report a documentation problem                   | [Documentation Issue](https://github.com/puku-sh/puku-cli-issues/issues/new?template=documentation.yml) |

> **Found a security vulnerability?** Please don't file a public issue — see [`SECURITY.md`](./SECURITY.md) for private disclosure instructions.

## Before you file

A little prep goes a long way toward a fast resolution:

- **Search existing issues.** Use the [issue search](https://github.com/puku-sh/puku-cli-issues/issues) to check whether your problem or idea has already been reported. If you find a duplicate, add a 👍 reaction or a comment with additional context instead of opening a new issue.
- **Use the latest version.** Run `puku-cli --version` and update to the newest release before filing. Many issues are already fixed in newer versions.
- **One issue per report.** Don't bundle multiple bugs or feature ideas together — each gets its own thread and label.
- **Never paste secrets.** API keys, tokens, passwords, `.env` contents, and personal data should never appear in an issue. Redact or omit them.

## Writing a good bug report

The best bug reports answer four questions clearly:

1. **What did you do?** — exact command(s), inputs, files involved.
2. **What happened?** — the actual behavior, including error output.
3. **What did you expect?** — the behavior you were hoping for.
4. **Can you reproduce it?** — every time? sometimes? once?

Additional tips:

- Include the **Puku CLI version** (`puku-cli --version`), **operating system**, and **terminal/shell**.
- Paste **complete error messages and stack traces** — don't paraphrase.
- If the issue involves specific files or code, create a **minimal reproduction** that anyone can follow.
- **Screenshots and short screen recordings** are welcome — drag and drop them into the issue.

## Writing a good feature request

The most useful feature requests focus on the **problem** first, the **solution** second.

- **Problem statement:** What are you trying to accomplish? Why is it hard today? Describe your current workflow.
- **Proposed solution:** How do you imagine this working? Be specific about commands, settings, or interactions.
- **Alternatives considered:** What workarounds have you tried? Are there existing tools that solve part of this?
- **Priority:** How much does this block your work?
- **Category:** Which area of Puku CLI does this relate to?
- **Use case:** Walk through a concrete, real-world scenario where this feature would help.

This helps us understand the use case, even if we end up implementing the feature differently than you envisioned.

## Reporting documentation problems

When something in our documentation is wrong or missing:

- **Link to the page** (or quote the section title) so we can find it quickly.
- **Quote the current text** that's wrong or unclear.
- **Explain what's wrong** — is it missing, confusing, outdated, or just a typo?
- **Suggest a fix** — proposed replacement text or examples are incredibly helpful.

## Issue lifecycle

Every issue moves through a predictable lifecycle:

```
open → triage (label applied) → needs-info / in-progress → resolved / closed
```

You'll see maintainers (and occasionally automated bots) add comments as the issue moves through these stages.

### Labels you'll see

We use labels to organize and prioritize issues. Common ones include:

| Label           | Meaning                                                       |
| --------------- | ------------------------------------------------------------- |
| `bug`           | Confirmed bug report                                          |
| `enhancement`   | Feature request                                               |
| `documentation` | Documentation problem                                         |
| `duplicate`     | Already reported elsewhere                                    |
| `invalid`       | Not related to Puku CLI                                       |
| `needs-info`    | Awaiting more information from the reporter                   |
| `needs-repro`   | Bug needs reproduction steps before we can investigate        |
| `regression`    | Worked in a previous version, broken now                      |
| `stale`         | Inactive for a long time; will be closed if there's no update |

## What we'll close without action

To keep the issue tracker focused and useful, we may close issues that are:

- **Duplicates** of existing issues — we'll point you to the original.
- **Invalid** — not related to Puku CLI.
- **Need more info** — if we ask for clarification and don't hear back within a reasonable window.
- **Support questions** — questions about *how* to use Puku CLI are best handled in our [community channels](https://puku.sh/community), not as GitHub issues.

## Community guidelines

We want this to be a welcoming space for everyone. When participating:

- **Be respectful.** Disagree on ideas, not on people.
- **Assume good faith.** Most questions and reports come from people genuinely trying to help.
- **Stay on topic.** Keep discussion focused on the issue at hand.
- **No harassment, discrimination, or personal attacks** of any kind.
- **No spam, advertising, or off-topic promotion.**

Maintainers reserve the right to remove content or close issues that violate these guidelines.

## Getting help

For general questions, troubleshooting, and conversation with other users:

- **Community page:** https://puku.sh/community
- **Help resources:** https://puku.sh/help

These channels are usually the fastest way to get unblocked for usage questions.

## License

By submitting documentation or other written contributions to this repository, you agree that your contributions are licensed under the [MIT License](./LICENSE.md).
