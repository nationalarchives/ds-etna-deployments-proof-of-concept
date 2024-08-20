# ETNA Deployments Proof of Concept

> Moved to https://github.com/nationalarchives/ds-infrastructure-web

## Working on new features

![Proposed feature branch deployment process](/img/1.feature.drawio.png)

- [Feature deployment workflow](https://github.com/nationalarchives/ds-etna-deployments-proof-of-concept/actions/workflows/deploy-feature.yml)

## Code is tested in feature environment and is "releasable"

![Proposed deployment process to develop environment](/img/2.develop.drawio.png)

- [Example push process from a service](https://github.com/nationalarchives/ds-etna-frontend/blob/main/.github/workflows/cd.yml#L54-L78)
- [Develop deployment workflow](https://github.com/nationalarchives/ds-etna-deployments-proof-of-concept/actions/workflows/deploy-develop.yml)

## All changes tested in develop environment and ready to release to staging environment

![Proposed deployment process to staging environment](/img/3.staging.drawio.png)

- [Staging deployment workflow](https://github.com/nationalarchives/ds-etna-deployments-proof-of-concept/actions/workflows/deploy-staging.yml)

## All changes tested in staging environment and ready to release to production environment

![Proposed deployment process to production environment](/img/4.production.drawio.png)

- [Example release tag (already published)](https://github.com/nationalarchives/ds-etna-deployments-proof-of-concept/releases/tag/v24.06.24.2)
