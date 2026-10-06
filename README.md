# Multi-Cloud Policy-as-Code Engine

This project stops unsafe cloud infrastructure before it is deployed.

It uses Terraform, GitHub Actions, Azure Policy, AWS controls, and automated compliance evidence.

## First control

The first control blocks public cloud storage. This reduces the risk of data being exposed to the internet.

## Project status

The project structure is ready. Azure Policy is the first build step.

## Planned controls

| Risk | Azure control | AWS control |
| --- | --- | --- |
| Public storage | Deny unsafe storage settings | Block public S3 settings |
| Missing logs | Require diagnostic logs | Require CloudTrail |
| Wrong region | Allow approved regions only | Restrict regions with SCPs |
| Missing owner | Require an `owner` tag | Require an `Owner` tag |

## Documentation

- [Control catalogue](docs/control-catalogue.md)
- [Threat model](docs/threat-model.md)
- [Architecture](docs/architecture.md)
