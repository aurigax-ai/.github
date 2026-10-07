# aurigax-ai/.github

The default community health files and the organization profile for
[AurigaX](https://github.com/aurigax-ai).

GitHub uses a file here for every repository in the organization that has no file of the same kind
of its own. These files do not appear in those repositories' file lists or history; they only show
up in GitHub's interface.

| File | What it is | Used by other repositories |
|---|---|---|
| `CODE_OF_CONDUCT.md` | Contributor Covenant 3.0 | Yes |
| `CONTRIBUTING.md` | How to contribute | Yes, except where a repository has its own (Ostia does) |
| `SECURITY.md` | How to report a vulnerability | Yes |
| `SUPPORT.md` | Where to get help | Yes |
| `.github/ISSUE_TEMPLATE/` | Issue forms: Bug report, Feature request, Question | Yes, as a whole folder: a repository with its own `ISSUE_TEMPLATE` folder uses only its own |
| `.github/pull_request_template.md` | Pull request template | Yes |
| `AI_POLICY.md` | AI policy for contributors | No, GitHub does not inherit it; the other files link to it |
| `profile/README.md` | The page shown at [github.com/aurigax-ai](https://github.com/aurigax-ai) | — |

The issue forms add labels (`type: bug`, `type: feature`, `question`, `status: needs triage`). A
label is applied only in a repository where it exists.

## Changing these files

Change them through a pull request. A change applies to every repository that uses the file as soon
as it is merged.

## Licence

[MIT](LICENSE), except `CODE_OF_CONDUCT.md`. That file is adapted from the
[Contributor Covenant](https://www.contributor-covenant.org/version/3/0/), version 3.0, and stays
under the Contributor Covenant's own licence,
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
