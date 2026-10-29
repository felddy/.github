# Community health files for felddy ⚕️ #

Account-wide default community health files for every felddy
repository. GitHub falls back to the files in this repository when a
repository does not provide its own file of the same type — see
[creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

Provided defaults:

| File | Purpose |
| --- | --- |
| `.github/ISSUE_TEMPLATE/` | Generic bug report and feature proposal forms |
| `.github/pull_request_template.md` | Pull request description template |
| `.github/FUNDING.yml` | Sponsor button configuration |
| `SECURITY.md` | How to report security problems |
| `SUPPORT.md` | Where to get help |

Fallback is all-or-nothing per file type: a repository with any issue
template of its own uses none of the defaults in that folder. Labels
assigned by the default issue forms are kept in sync everywhere by the
central label definitions in
[reusable-workflows](https://github.com/felddy/reusable-workflows).
