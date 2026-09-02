# collective-cognition-bootstrap-20260825

Throwaway package used once to settle two npm registry facts before the
first `collective-cognition-sdk` release:

1. whether a trusted publisher can be configured for a package that does not
   yet exist on the registry;
2. whether the first publication of a package with `--tag next` leaves the
   `latest` dist-tag unset.

It has no functionality and is not for use. Published versions are never
unpublished; the observed results are recorded in the collective-cognition-sdk
repository under `docs/acceptance/releases/bootstrap-verification.md`.

Licensed under Apache-2.0.
