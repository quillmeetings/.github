# .github

Organization-level configuration and community health files for
[Quill](https://github.com/quillmeetings).

This is a GitHub "magic" repository: files placed here apply as **defaults**
across every repository in the organization that does not provide its own
equivalent.

## What lives here

| Path | Purpose |
|------|---------|
| `profile/README.md` | Public organization profile shown on [github.com/quillmeetings](https://github.com/quillmeetings) |
| `CODE_OF_CONDUCT.md` | Default code of conduct |
| `CONTRIBUTING.md` | Default contribution guidelines |
| `SECURITY.md` | Default security and vulnerability disclosure policy |
| `SUPPORT.md` | Default support routing |
| `.github/ISSUE_TEMPLATE/` | Default issue templates |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default pull request template |

The member-only profile and any internal-facing defaults live in the private
companion repository, [`.github-private`](https://github.com/quillmeetings/.github-private).

## Editing

Changes here are high blast radius — they affect every repository in the
organization at once. This repo is managed under the `meta` archetype in the
infrastructure GitHub Terraform configuration; edits go through a pull request
reviewed by `@quillmeetings/build-managers`.
