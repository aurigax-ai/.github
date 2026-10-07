# Security policy

## Scope

This policy covers the public repositories in [aurigax-ai](https://github.com/aurigax-ai): the Ostia
app, the extension marketplace, the Homebrew tap, the APT repository, ghostty-web and the website.

## Supported versions

Only the latest stable release gets security fixes. For Ostia, that is the release marked Latest on
the [releases page](https://github.com/aurigax-ai/ostia/releases/latest). Release candidates
(`-rc.N`) and older versions are not supported.

## Reporting a vulnerability

Do not open a public issue. Report it privately through GitHub: open the repository's Security tab
and choose Report a vulnerability, or use the link below.

| Repository | Report |
|---|---|
| ostia | <https://github.com/aurigax-ai/ostia/security/advisories/new> |
| ostia-extensions | <https://github.com/aurigax-ai/ostia-extensions/security/advisories/new> |
| homebrew-tap | <https://github.com/aurigax-ai/homebrew-tap/security/advisories/new> |
| apt | <https://github.com/aurigax-ai/apt/security/advisories/new> |
| ghostty-web | <https://github.com/aurigax-ai/ghostty-web/security/advisories/new> |
| aurigax-ai.github.io | <https://github.com/aurigax-ai/aurigax-ai.github.io/security/advisories/new> |

If you are not sure which repository it belongs to, report it in ostia. A short paragraph that
explains the problem is a complete report. If you can, include:

- the affected version
- your operating system
- the steps to reproduce it
- what an attacker could do with it

If an AI tool found the problem, confirm it yourself before you report it (see the
[AI policy](https://github.com/aurigax-ai/.github/blob/main/AI_POLICY.md)).

## What happens next

We are a team of two. We aim to confirm that we have received your report within 7 days; this is a
best effort, not a guarantee. We discuss the problem with you in the private advisory, fix it, and
then publish a GitHub Security Advisory, mention the fix in the release notes and credit you, unless
you ask us not to.

We do not offer a bug bounty or other rewards.
