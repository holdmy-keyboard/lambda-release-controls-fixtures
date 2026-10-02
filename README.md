# Lambda release-control fixtures

Companion source for controlled, harmless fixtures in the [Lambda release-control study](https://github.com/holdmy-keyboard/lambda-release-controls-study).

This researcher-owned repository supplies the alternative repository identity needed for the prospective comparison. Its tiny application ignores invocation inputs and returns a fixed release marker. It is not an attacker infrastructure or a production service.

Setup and validation are in progress as of 2 October 2026. No experimental results have been collected or published. The committed cloud runtime is disabled. The identity-only workflow records only nonsecret OIDC identity claims without assuming an AWS role.

Credentials, raw private evidence and account bindings must never be committed here. Local tests are synthetic and are not experiment observations.
