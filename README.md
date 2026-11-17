# .github

This repository provides **default community health files** for all repositories in this organization.  

For more details on how GitHub uses this repo, see the [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Shared workflows

- `.github/workflows/zizmor.yml` audits a repository's GitHub Actions workflows, composite actions, and Dependabot configuration with [zizmor](https://docs.zizmor.sh). It is written to be required by an organization ruleset, so it runs on every repository's pull requests and merge queue. A repository's own `zizmor.yml` configuration is honored, and a repository with nothing to audit passes.
