# Changelog

## Unreleased

- Pin the default Keycloak server image to 26.8.0 by digest across the configured
  cluster templates (#357923). Keycloak instances remain disabled in this chart.
  Deployments from this repository are unverified; the inspected hub Argo CD
  applications use platform-gitops-w4. Upgrade the operator and CRDs together
  after the server; Adfinis has no chart for 26.8.0 as of 2026-10-05.
