# .github

Organization profile and community health defaults for the Hyland Labs organization.

| Path | Purpose |
| --- | --- |
| `profile/README.md` | The organization profile page shown at `github.com/HylandLabs` |
| `SECURITY.md` | Default security policy for Labs repositories without their own |
| `CONTRIBUTING.md` | Default contribution guidelines for Labs repositories without their own |

Community health files here apply to every repository in the organization that does not
provide its own copy. A repository's own file always wins. `LICENSE` is not inherited:
each repository needs its own.

## Contributing to this repository

This repository is public. Everything merged to the default branch is visible to everyone
and is inherited by other repositories in the organization, so changes go through a pull
request with code-owner review. A continuous integration check fails any pull request that
introduces internal references or unresolved placeholders.
