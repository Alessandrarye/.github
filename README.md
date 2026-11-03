# Shared workflows

Reusable GitHub Actions called by every project repo in the portfolio.
`terraform.yml` runs fmt, validate, and plan on pull requests and apply on merge to main,
authenticating to Azure with a federated (OIDC) credential. No stored secrets.
