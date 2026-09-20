# deploy branch

This orphan branch holds only environment values for Argo CD.
It is NOT protected on purpose: CI commits image tags here after each merge.

- envs/dev/values.yaml  - updated on merge to `development`
- envs/prod/values.yaml - updated on merge to `main`

The Helm chart itself lives in `infra/helm/pet-project` on the code branches.
