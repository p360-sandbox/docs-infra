# docs-infra (sandbox)

Placeholder copy of the platform infrastructure repository, for testing the docs portal.

- `redirects.json` is published from `redirects_dev` and `redirects_prod`; `main` is refused.
- `admin_config` and `admin_requests` are orphan branches the portal reads and writes. They carry no
  workflows, so a commit there deploys nothing.
- Every workflow here is a dry run: it checks the branch and prints what it would deploy.
