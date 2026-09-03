# Fluveo OpenAPI

This repository contains the public OpenAPI specification for the Stripe-shaped
Fluveo API. It is generated from Fluveo's private monorepo for API version
`2026-05-27.dahlia`.

## Contents

| Path | Description |
| --- | --- |
| `openapi/spec3.json` | OpenAPI 3 specification in JSON format. |
| `openapi/spec3.yaml` | The same OpenAPI 3 specification in YAML format. |
| `VERSION` | The Fluveo API version contained in this release. |

JSON and YAML describe the same document. Use whichever format your OpenAPI
tooling supports.

The specification is generated from the private Fluveo monorepo. Do not edit
generated files in this repository; changes must be made in the source
repository and published by its release workflow.

API guides and reference documentation are available at
[docs.fluveo.com](https://docs.fluveo.com).

Clients should omit `Stripe-Version` or send the pinned value
`Stripe-Version: 2026-05-27.dahlia`.

## License

MIT. See [LICENSE](./LICENSE).
