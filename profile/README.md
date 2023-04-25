# sigstore-conformance

This organization exists to provide isolated support for Sigstore's
[conformance suite].

It's isolated from the [main Sigstore GitHub organization] because it
contains a workflow that [intentionally leaks] an OIDC credential for testing
purposes. Keeping this workflow in an isolated organization minimizes
the possibility that users might confuse it for a legitimate, non-testing
Sigstore workflow identity.

[conformance suite]: https://github.com/sigstore/sigstore-conformance

[main Sigstore GitHub organization]: https://github.com/sigstore

[intentionally leaks]: https://github.com/sigstore-conformance/extremely-dangerous-public-oidc-beacon
