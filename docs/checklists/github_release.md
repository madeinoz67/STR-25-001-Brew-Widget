# GithHub Release Checklist [on main branch]

see Project documentation for GitHub [Release process](../github.md#release-process)

- [ ] manually Bump version in pyproject.toml and push to main
- [ ] pull from main branch as CHANGELOG is auto generated
- [ ] tag head with release version (same as entered in pyproject.toml) prepend version with "v" e.g. "v1.0.2"
- [ ] push tag to origin
